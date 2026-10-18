# AI ASSESSMENT AND CONSULTATION REPORT

# 1. Report Details

| Company | Harmaja Bakery Oy (business ID 2954410-8) |
| --- | --- |
| Industry | Food manufacturing - industrial bakery products |
| Assessment date | 14 May 2026 |
| Advisors | Laura Nieminen (AI advisor, business), Tomas Berg (AI advisor, technical) |
| Company participants | Petri Harmaja (Managing Director), Sari Kallio (Production Manager), Ville Ojala (Quality Manager) |
| Report version | 1.0, 28 May 2026 |

# 2. Executive Summary

Harmaja Bakery Oy is a family-owned industrial bakery in Lahti producing fresh and frozen bread and pastry products for grocery retail and food service. The company's AI maturity is assessed as low: generative AI is used by a few individuals, but there is no AI strategy, policy or systematic use in production or planning. The most promising use case is AI-based demand forecasting for fresh products, which addresses daily overproduction and returns that currently cost the company an estimated EUR 520,000 per year. The main recommendation is to start with a forecasting proof of concept for the twenty highest-volume fresh products, supported by a review of sales and returns data, and to introduce an AI usage policy in parallel.

# 3. Company Overview

Harmaja Bakery Oy was founded in 1987 and is run by the second generation of the Harmaja family. The company employs 86 people and had revenue of EUR 14.2 million in 2025. Production takes place in a single plant in Lahti with three production lines: a fresh bread line, a pastry line and a frozen products line operating in two shifts. The product range includes about 140 products, of which 60 are fresh products with a shelf life of one to four days.

Around 70 % of revenue comes from the two largest Finnish grocery retail chains, and the rest from food service wholesalers, cafés and a small export business to Estonia. Rising raw material and energy costs and the retail chains' growing private-label competition put pressure on margins. The company's strategic goal is to improve profitability by reducing waste and to grow the frozen product range, which is less exposed to daily demand fluctuation.

# 4. AI Maturity Level

The company has a modern ERP system and an automated production line control system, but AI is not used in any business process. A few office employees use free generative AI tools for marketing texts and product descriptions, and the quality manager has experimented with a chatbot to draft HACCP documentation. Use is individual and unguided: there is no AI policy, no training and no assessment of what data may be entered into public tools. Management is motivated to adopt AI but lacks an overview of where it would create value. The company's AI maturity is rated Low.

# 5. Current Solution Development Stage

Harmaja Bakery is at the ideation stage. Three use cases have been identified: demand forecasting for fresh products, camera-based quality inspection on the packaging line, and automated checking of product labels against recipes and allergen information. Production quantities for fresh products are currently set each afternoon by the production planner based on retail orders, previous weeks' sales and personal experience. Quality inspection is visual and manual, and label checks are done by the quality manager with printed checklists. The objective is to reduce waste and returns, lower the risk of product recalls, and free the time of key persons for development work.

# 6. Identified Use Cases and Prioritisation

| Use case | Current process and pain point | Expected benefit | Feasibility | Priority |
| --- | --- | --- | --- | --- |
| Demand forecasting for fresh products | Daily quantities set manually; overproduction and returns about 9 % of fresh volume (approx. EUR 520,000/year) | Waste reduction of 20-30 %; more stable planning | Good: three years of daily sales and returns data in ERP | 1 |
| Label and allergen compliance checking | Manual comparison of labels with recipes; two label errors led to product withdrawals in 2024-2025 | Lower recall risk; faster product launches | Good: recipes and label files are digital | 2 |
| Visual quality inspection on packaging line | Manual visual checks; defects (shape, colour, packaging seal) found late | Fewer customer complaints; consistent quality | Moderate: requires cameras, lighting and labelled images | 3 |

Demand forecasting is prioritised because it addresses the largest cost item, its benefits are easy to measure, and the required data already exists. Label checking is a smaller but low-risk second step. Visual inspection requires hardware investments and a data collection phase, and is therefore planned for a later stage.

# 7. Validity of Concept and Authenticity of Problem Addressed

All three use cases address real and measurable business problems. Overproduction and returns of fresh products amount to roughly nine percent of fresh volume, and retail contracts make the bakery responsible for unsold products. Label errors have caused two product withdrawals in the last two years, each with direct costs and reputational damage. Quality defects are a recurring theme in customer feedback. The forecasting concept is closest to implementation, because the process, data and success metrics are clearly defined, while the inspection concept is still at an early idea stage.

# 8. Integration and Importance of AI in the Idea

In demand forecasting, AI is central: a machine learning model would predict daily demand per product and customer, taking into account seasonality, holidays, weather and retail campaigns, and propose production quantities to the planner, who keeps the final decision. In label checking, a language model would compare label texts with recipe and allergen data and highlight discrepancies for the quality manager to review. In visual inspection, computer vision would classify product and packaging defects in real time. In all cases AI supports human decisions rather than replacing them.

# 9. Identified Target Market and Customer Segments

The company's customers are grocery retail chains (about 70 % of revenue), food service wholesalers, cafés and an Estonian retail partner. The forecasting initiative would first affect the retail chain customers, whose daily orders and returns drive overproduction. Internally, the production planner and the quality manager are the first user groups.

# 10. Data Requirement Assessment

Forecasting requires daily sales, order and returns data per product and customer, product master data, campaign calendars and external data such as weather and public holidays. Three years of daily sales and returns data are stored in the ERP system; campaign information is received from retail chains by email and is not stored systematically. Label checking requires recipe data, allergen information and final label files, which are held in the ERP and as PDF files on a shared drive. Visual inspection would require several thousand labelled product images, which do not yet exist.

# 11. Data Collection Strategy

The company has no structured strategy for collecting data for AI. Operational data is recorded reliably in the ERP, but data from other sources, such as retail campaign plans and customer complaints, is scattered across email and spreadsheets. No data owners have been named. The main gaps are the lack of a systematic record of campaigns and promotions and the absence of image data from production.

# 12. Technical Expertise and Capability

Harmaja Bakery has no in-house IT or AI specialists. IT services are outsourced to a local IT partner, and the ERP system is maintained by its vendor. The production manager has good spreadsheet and reporting skills. Implementation will therefore depend on external partners, and any solution should integrate with the existing ERP and be maintainable without in-house developers.

# 13. Risks, Compliance and Responsible AI

The main risks are dependence on external partners, the use of public AI tools without guidelines, and the possibility that planners stop trusting the forecasts if early results are poor. Recipe information is a trade secret and must not be entered into public AI tools. The label-checking use case is relevant to food safety regulation, so a human must remain responsible for final approval. An AI usage policy, clear human approval steps and a gradual roll-out are recommended mitigations.

# 14. Budget and Funding

The company has not invested in AI so far. Management has indicated a willingness to invest EUR 30,000-40,000 in a first pilot in 2026-2027, and the company is interested in public funding such as the ELY Centre's development grants. The company has used ELY funding before for a production line investment.

# 15. Expectations from FAIR Services

Harmaja Bakery expects FAIR to help scope and plan the demand forecasting proof of concept, assess the quality of its sales and returns data, and advise on suitable forecasting tools and ERP integration. The company also asked for an AI usage policy template, an introductory AI training session for office staff, and support in preparing a funding application. A follow-up meeting was planned for June 2026.

# 16. Recommendations

Start with a demand forecasting proof of concept for the twenty highest-volume fresh products and the two largest retail customers. Measure success by the reduction in returns and overproduction compared with the current manual planning over at least eight weeks.

Before the proof of concept, extract three years of daily sales, orders and returns from the ERP and review data quality, gaps and product code changes. The results will determine whether a standard forecasting service is sufficient or a custom model is needed.

Start recording retail campaigns and promotions systematically in a shared spreadsheet or the ERP. Campaigns are a major driver of demand and the forecast cannot account for them without this data.

Keep the production planner in control: the model proposes quantities and the planner approves or adjusts them. Track adjustments to learn where the model needs improvement.

Run a small pilot of AI-assisted label checking using recipe and label files, with the quality manager reviewing every flagged discrepancy. Use an enterprise AI service that does not store or train on company data.

Introduce an AI usage policy and a short training for office staff that covers which data may be entered into AI tools, with particular attention to recipes as trade secrets.

Postpone visual quality inspection until the forecasting pilot is complete, but begin collecting labelled images of typical defects so that data is available when the use case is taken up.

# 17. Next Steps and Action Items

| Action | Responsible | Deadline |
| --- | --- | --- |
| Export three years of daily sales, orders and returns data from the ERP | Sari Kallio / ERP vendor | 6 June 2026 |
| Collect retail campaign calendars for the past 12 months | Petri Harmaja | 6 June 2026 |
| Share 30 recipe and label file pairs for the label-checking test | Ville Ojala | 13 June 2026 |
| Prepare a data quality review and proof-of-concept plan | Tomas Berg (FAIR) | 20 June 2026 |
| Send AI usage policy template and funding options | Laura Nieminen (FAIR) | 30 May 2026 |
| Follow-up meeting in Lahti | All | 25 June 2026 |

# Appendix: Sources

Assessment meeting with Harmaja Bakery Oy management, 14 May 2026 (recording and advisors' notes)

Harmaja Bakery Oy company presentation, April 2026

Sales and returns summary 2023-2025 (Excel), provided by the production manager

Site visit to the Lahti production plant, 14 May 2026

Harmaja Bakery Oy and all persons and figures in this sample report are fictional.