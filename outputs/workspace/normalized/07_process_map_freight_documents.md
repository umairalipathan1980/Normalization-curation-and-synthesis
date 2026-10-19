# Freight document handling – current state (AS-IS)

Lumivaara Logistics Oy · Process mapping workshop, Vantaa, 24 Sept 2026 · drawn by M. Saarinen & J. Koskela

## Driver / subcontractor

**1. Delivery made**  
Recipient signs CMR / POD on paper

→

**2. Document sent**  
Own drivers: photo in app.  
Subcontractors: email or paper in batch  
Delay 2–10 days (subcontractors)

→

**3. Paper at gate**  
Paper documents left in tray at warehouse gate

## Document clerk (6 FTE)

**4. Scan paper**  
Batch scanning at end of shift  
~25 min / batch

→

**5. Open & read**  
Photos often blurry, night shots, 6+ languages  
Handwritten remarks missed

→

**6. Find shipment in TMS**  
Search by consignment no. or customer ref.  
~1 min

→

**7. Key in data**  
Packages, weight, pallets, date, signature, remarks  
3–4 min / doc · ~4 % errors

→

**8. Re-enter in ERP**  
Invoicing fields typed again into Business Central  
Double entry

## Systems

**RouteLine TMS**  
POD status, shipment data  
(API: single records only)

→

**Business Central**  
Invoicing, credit notes

→

**File server archive**  
PDF per site/month, no index,  
~1.5 M docs since 2019

## Finance / claims

**9. Invoice shipment**  
Only after POD processed

→

**10. Corrections**  
Wrong invoices → credit notes, disputes  
~1 day / week

→

**11. Damage claim**  
Raised against haulier  
7-day deadline often missed

## Legend

- Process step
- Pain point
- System / data store

## Metrics

**71 %**  
PODs processed within 2 days  
(target 95 %)

**3.1 %**  
Invoice correction rate (target < 1 %)

**6 FTE**  
Document clerks (Vantaa 4, Tampere 1, Oulu 1)

**5**  
Document types: CMR, delivery note, POD, packing list, customs

## Ideas from the workshop (TO-BE)

1. AI reads documents from email + app automatically
2. Fields extracted → TMS via API, human checks only uncertain ones
3. Flag handwritten damage remarks → claims same day
4. Pilot: PODs in Vantaa first?
5. Open question: how to get paper docs digital faster?

Fictional example company – created for report-generation testing.