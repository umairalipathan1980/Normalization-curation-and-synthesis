FAIR AI ADVISORY - MEETING NOTES
=================================

Company:        Lumivaara Logistics Oy (fictional example company)
Business ID:    3187654-2 (fictional)
Location:       Logistiikkatie 14, 01530 Vantaa, Finland
Meeting date:   2 October 2026, 13:00-14:30
Meeting type:   Initial AI assessment and consultation (Teams + on-site visit to Vantaa warehouse afterwards)
Notes by:       Elina Rautio (FAIR AI advisor)

Attendees
---------
Company:
  - Kaisa Lindholm, CEO (joined for the first 40 minutes)
  - Mikko Saarinen, Operations Director
  - Jari Koskela, IT Manager
  - Anna Virtanen, Customer Service Team Lead (joined for the customer service part)
FAIR:
  - Elina Rautio, AI advisor (business)
  - Daniel Okafor, AI advisor (technical)


1. COMPANY BACKGROUND
---------------------
- Third-party logistics (3PL) company founded in 2009 by the Lindholm family. Second-generation
  management since 2021 (Kaisa Lindholm took over as CEO).
- Services: contract warehousing, domestic road freight, e-commerce fulfilment, customs clearance
  for customers importing from outside the EU, and value-added services (labelling, kitting,
  returns handling).
- Three warehouses: Vantaa (main site and head office), Tampere and Oulu. Oulu opened in 2023.
- About 130 employees in total; on top of that, temporary agency staff in peak seasons
  (November-December is the clear peak because of e-commerce customers).
- Revenue 2025 approx. EUR 24.6 million, growth around 7 % per year over the last three years.
- Own fleet of 38 trucks plus a network of roughly 25 subcontracted hauliers.
- Around 210 active B2B customers. Largest segments: retail and e-commerce, industrial spare parts,
  chilled food and beverage, and a small but growing pharma/healthcare segment (GDP-certified area
  in Vantaa since 2024).
- Kaisa described margins as "thin and getting thinner" - fuel, wage settlements and price
  pressure from large customers. Growth must come without a matching increase in office staff.


2. CURRENT USE OF AI AND DIGITAL TOOLS
--------------------------------------
- Microsoft 365 in use company-wide. Microsoft 365 Copilot licences purchased for 25 office staff in
  spring 2026 as a pilot. Usage is uneven: some people use it daily for emails and meeting summaries,
  others "have not opened it". No guidelines or training beyond a one-hour vendor webinar.
- Several employees use free ChatGPT for translations (Swedish, English, Estonian drivers) and for
  drafting customer letters. Jari is worried about customer data being pasted into free tools; there
  is no AI usage policy yet.
- An RPA bot (UiPath) was implemented in 2023 for matching supplier invoices to purchase orders in
  Business Central. Works for ~70 % of invoices; the rest go to manual handling. This is rule-based,
  not AI, but it is the company's main automation experience.
- The TMS has a built-in route planning module. Planners use it for Vantaa-area distribution but
  override it often because "it does not know the customers' unloading times".
- No machine learning models in production. No data warehouse; reporting is done in Excel exports
  and a few Power BI reports that Jari maintains.
- Preliminary AI maturity rating by FAIR: LOW. Strong operational digitalisation (WMS, TMS, EDI) but
  AI use is individual and ad hoc; no strategy, policy, roadmap or AI-specific skills in house.


3. IDENTIFIED AI USE CASES
--------------------------

3.1 Freight document processing (highest priority for the company)
- Every day the company receives CMR waybills, delivery notes, proof-of-delivery (POD) documents,
  packing lists and customs documents. Mikko estimated about 1,200 documents per day across all
  sites. (To be checked against the volume data Jari will send - the TMS log may give a different
  number.)
- Documents arrive as email attachments (PDF, some JPG photos taken by drivers), via the driver app
  (photos) and on paper at the warehouse gates. Paper documents are scanned in batches.
- Six document clerks (4 in Vantaa, 1 in Tampere, 1 in Oulu) key in the data manually into the TMS
  and, for invoicing-relevant fields, into Business Central.
- Fields entered: shipment/consignment number, customer reference, sender, receiver, number of
  packages, gross weight, pallet count and type, delivery date and time, signature present Y/N,
  remarks (damage, shortages).
- Mikko's estimate of the error rate in manual entry: around 4 %. Errors lead to wrong invoices,
  credit notes, and disputes; the finance team spends "a day a week" on corrections.
- Biggest pain: PODs with handwritten remarks ("1 lava rikki", "vastaanotettu varauksin") are
  missed, so damage claims are raised late and the company loses the right to claim against the
  haulier.
- Desired outcome: automatic extraction of the fields into the TMS with a human check only for
  low-confidence documents; flagging of handwritten remarks.
- Documents are in Finnish, Swedish, English, Estonian and some Polish and Lithuanian (international
  hauliers). Quality varies a lot - photos taken in truck cabins at night.

3.2 Warehouse labour demand forecasting
- Staffing for each warehouse is planned weekly by shift supervisors using experience and the
  customer forecasts that arrive by email (if they arrive at all).
- Overtime and last-minute agency staff are costly. Mikko: overtime costs were about EUR 410,000 in
  2025, with the Tampere site the worst because of one large spare-parts customer with very
  irregular volumes.
- Idea: forecast daily inbound pallets and outbound order lines per warehouse 1-3 weeks ahead, using
  history from the WMS plus customer forecasts, calendar effects (holidays, campaigns), and maybe
  weather for the chilled food customers.
- Six years of history exist in the WMS, but the system was replaced/upgraded in 2020 and Jari is not
  sure whether pre-2020 data is comparable. Oulu has only data since 2023.

3.3 Customer service email triage and reply drafting
- Anna's team (7 people) handles the shared customer service mailbox. Roughly 380 emails per day on
  average, peaking at over 600 in December.
- Main categories (Anna's estimate): track & trace questions about half, booking changes, delivery
  time requests, damage and claims, invoicing questions, and new quote requests that should go to
  sales but often sit in the mailbox.
- Target response time is 4 working hours; actual average is around 9 hours in peak periods.
- Idea: automatically classify incoming emails, route them, look up shipment status from the TMS and
  draft a reply for the agent to approve. Not interested in fully automatic replies at this stage.
- Emails contain personal data (names, phone numbers, home delivery addresses of consumers for
  e-commerce customers). GDPR and AI Act transparency questions came up - who can see what, where the
  data is processed.

3.4 Other ideas mentioned (not prioritised)
- Route optimisation using real unloading times (TMS vendor may provide an update in 2027).
- Predictive maintenance for trucks and forklifts (telematics data exists, but the fleet manager was
  not present).
- Automatic generation of customs declarations - Kaisa sees this as too risky for now.


4. DATA AND SYSTEMS
-------------------
- WMS: on-premise system from a Finnish vendor, current version since 2020. SQL Server database.
  Jari has read access. Contains receipts, putaways, picks, shipments, inventory movements.
- TMS: cloud TMS ("RouteLine", fictional name used in these notes) since 2018. REST API available
  but limited (no bulk export; vendor offers a paid data export).
- ERP: Microsoft Dynamics 365 Business Central (cloud) since 2022 - invoicing and finance.
- EDI: through an EDI operator with the 15 largest customers (orders, ASNs, invoices).
- Document archive: scanned documents stored as PDFs on a file server, folder per site and month.
  Not indexed. Estimated 1.5 million documents since 2019.
- Customer service: shared Outlook mailbox, no ticketing system. Anna keeps a manual Excel tally of
  categories for one week per month.
- Data quality concerns: customer master data duplicated between TMS and Business Central; no common
  customer ID. Pallet types recorded inconsistently.
- No data owner roles defined. No data strategy. Jari is the only IT person and also handles
  hardware, phones and user support.


5. TECHNICAL CAPABILITY AND RESOURCES
-------------------------------------
- One-person IT function (Jari). Good SQL and Power BI skills, no Python/ML experience.
- External partners: WMS vendor (support contract), Business Central partner (Dynamics consultancy),
  IT outsourcing for network and security.
- Operations team is process-savvy and open to change; supervisors are worried about extra work
  during the implementation.
- Budget: Kaisa said the board would be open to investing EUR 60,000-80,000 in AI-related projects in
  2027 if the first pilot shows results. (Note: the company's strategy document mentions a different
  figure - check.)
- Funding: interested in Business Finland or ELY Centre funding for the pilot. Has not applied before.


6. EXPECTATIONS FROM FAIR
-------------------------
- Help to choose and scope the first proof of concept - the company leans towards freight document
  processing.
- Technical advice on document extraction approach (OCR vs. vision language models), on how to
  integrate with the TMS API, and on human-in-the-loop design.
- An assessment of whether the WMS data is good enough for forecasting.
- Guidance on an AI usage policy for staff, GDPR and AI Act obligations (especially for the customer
  service use case).
- Possibly a Master's thesis student for the forecasting topic (spring 2027).
- Help with a funding application if the PoC looks promising.


7. ADVISORS' OBSERVATIONS (internal, Elina & Daniel)
----------------------------------------------------
- Document processing is the best first candidate: high volume, measurable baseline (clerk hours,
  error rate), clear ROI, and modern vision language models handle mixed-quality photos and
  multilingual documents reasonably well. Handwriting is the main risk; must be tested on real
  samples.
- Start with one document type (POD) and one site (Vantaa) before scaling.
- Forecasting is valuable but depends on data quality - need a data extract first. Could be a
  classic time-series ML task rather than generative AI.
- Email triage is relatively easy technically but has the most compliance work; good second step
  once an AI policy exists.
- An AI usage policy and short Copilot training are quick wins regardless of the PoC.
- Risk: single IT person = bottleneck. Any solution must be low-maintenance or partner-operated.


8. ACTION ITEMS
---------------
[ ] Jari: send anonymised sample of 200 freight documents (mix of types, sites, languages, at least
    50 with handwritten remarks) - by 30 October 2026.
[ ] Jari: export daily WMS volumes per site 2020-2026 and the TMS document log for 2025 - by
    30 October 2026.
[ ] Anna: share the customer service category tally for the last 6 months.
[ ] Mikko: collect current clerk time per document type (one-week time study in Vantaa).
[ ] Daniel: prepare a short note on document extraction options and a PoC outline.
[ ] Elina: send an AI usage policy template and a list of funding instruments.
[ ] Next meeting: 12 November 2026, on-site in Vantaa, to review sample documents and data.
