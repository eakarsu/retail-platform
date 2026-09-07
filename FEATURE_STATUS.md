# Feature status — Retail, inventory & rental operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 364 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 3 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 14 | 0 | Native records/view |
| Activity & audit trail | audit | 10 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Program authorization library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| End-customer registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product eligibility mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor sales ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resale price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim quantity validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate claim detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorization period control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ship-and-debit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manufacturer claim file | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rejection remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit memo matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program customer analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor contract and rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment and asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispatch delivery and pickup timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| On-rent and off-rent validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily weekly monthly rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter and overtime usage audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel and refueling charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery pickup and mobilization audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance and downtime credits | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage condition comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage estimate and responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate and overlapping rental detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor credit and payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset vendor and project analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Development agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory boundary mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchisee entity registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unit schedule tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site approval milestones | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Opening deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Initial fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Development default detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notice cure workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchisee dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Territory unit analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchise agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location and ownership registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| POS sales ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery-platform reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bank deposit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax-return comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross-sales reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exclusion and discount validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Royalty recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advertising-fund recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Late fee and interest calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchisee audit workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Finding and evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Response and collection tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Systemwide leakage analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program processor agreements | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Card issuance ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activation reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Redemption ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-brand settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchant funding calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processor fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud duplicate redemption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund replacement control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Breakage estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recognition schedules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unclaimed property classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner settlement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash liability reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member account registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Earn-event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Redemption-event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer conversion ratios | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner purchase-rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Redemption reimbursement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Promotional bonus allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reversal refund control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiration breakage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud duplicate events | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner program economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return policy library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| RMA ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier event tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warehouse receipt matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Condition grade validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restock eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refurbishment economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liquidation lot creation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expected resale value | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Channel fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing unit detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liquidator statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product disposition analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retailer program library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store SKU registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Slotting commitment tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| New-store authorization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| POS scan ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scan-back calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Display placement evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advertising compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-performance collection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Earned allowance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier claim package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store SKU program analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consignor Management | records | 1 | 0 | Native records/view |
| Item Cataloging | records | 1 | 0 | Native records/view |
| Auction Calendar | records | 2 | 0 | Native records/view |
| Bidder Registration | records | 1 | 0 | Native records/view |
| Live Auctions | records | 1 | 0 | Native records/view |
| Shipping & Logistics | records | 1 | 0 | Native records/view |
| Condition Reports | records | 1 | 0 | Native records/view |
| Storage & Warehouse | records | 1 | 0 | Native records/view |
| Compliance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI: Lot Description | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI: Valuation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI: Authenticity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI: Marketing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI: Buyer Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI: Market Trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Photography Studio | records | 1 | 0 | Native records/view |
| Catalog Production | records | 1 | 0 | Native records/view |
| Marketing Campaigns | records | 1 | 0 | Native records/view |
| Payments | records | 2 | 0 | Native records/view |
| Unsold Lots | records | 1 | 0 | Native records/view |
| Appraisals | records | 1 | 0 | Native records/view |
| Estate Sales | records | 1 | 0 | Native records/view |
| Similarity matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bidding analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provenance verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi language catalog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Condition report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer preference | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Photo enhancement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic reserve pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict final price | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shill bidding detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| External auction search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance policy recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecast | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Chatbot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Optimizer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Route Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Description Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nearby | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rentals | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bids | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage Reports | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return Inspection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Identity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Claim Assist | records | 1 | 0 | Native records/view |
| Dynamic Seasonal Pricing | records | 1 | 0 | Native records/view |
| Agentic Marketplace Search | records | 1 | 0 | Native records/view |
| Benchmark | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic compliance auditor reviewing pls | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic territory optimization recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time websocket dashboard for corpor | records | 1 | 0 | Native records/view |
| supplier bulk buy advisor aggregating pu | records | 1 | 0 | Native records/view |
| brand standard photo audit via vision | records | 1 | 0 | Native records/view |
| franchisee peer mentoring marketplace wi | records | 1 | 0 | Native records/view |
| territory optimization ai consolidati | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| franchisee ltv or churn prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| marketing spend optimizer across unit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi unit demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| franchise units crud surfaced as | records | 1 | 0 | Native records/view |
| paymentbilling integration | integration | 1 | 0 | Provider request records only |
| real time websocket dashboard updates | records | 1 | 0 | Native records/view |
| vendor contract management | records | 1 | 0 | Native records/view |
| franchisee onboarding workflow | records | 1 | 0 | Native records/view |
| Products | records | 7 | 0 | Native records/view |
| Forecasts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Suppliers | records | 2 | 0 | Native records/view |
| Orders | records | 2 | 0 | Native records/view |
| Demand Predictor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Risk | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Reorder Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Dead Stock | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Warehouse Layout | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Shipment Tracker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Promotion Simulator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Markdown Timing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Disruption Simulator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Warehouse Balancing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pass5 tools | records | 1 | 0 | Native records/view |
| Expiry waste optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic inventory manager autonomously p | records | 1 | 0 | Native records/view |
| demand supply fusion integrating custome | records | 1 | 0 | Native records/view |
| multi warehouse network optimization rec | records | 1 | 0 | Native records/view |
| markdown clearance optimizer balancing d | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| supplier performance reliability trackin | records | 1 | 0 | Native records/view |
| seasonal promotional planning coordinate | records | 1 | 0 | Native records/view |
| markdown timing ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi warehouse balancing ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| sku rationalization which skus to | records | 1 | 0 | Native records/view |
| live erp sap netsuite integrations still | integration | 1 | 0 | Provider request records only |
| financial pl module | records | 1 | 0 | Native records/view |
| notifications module 0 references | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| file upload for supplier docs | records | 1 | 0 | Native records/view |
| real time websocket inventory updates | records | 1 | 0 | Native records/view |
| Inventory | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Pawn Loans | records | 1 | 0 | Native records/view |
| Layaway | records | 1 | 0 | Native records/view |
| Hold Periods | records | 1 | 0 | Native records/view |
| Precious Metals | records | 1 | 0 | Native records/view |
| Firearms Log | records | 1 | 0 | Native records/view |
| Police Reports | records | 1 | 0 | Native records/view |
| Cash Drawer | records | 1 | 0 | Native records/view |
| Receipts | records | 1 | 0 | Native records/view |
| AI Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic valuation | records | 1 | 0 | Native records/view |
| Compliance automation | records | 1 | 0 | Native records/view |
| Pricing recommendation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer segmentation + marketing | records | 1 | 0 | Native records/view |
| Loan default prediction + intervention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auctions without `/auction | records | 1 | 0 | Native records/view |
| Hold | records | 1 | 0 | Native records/view |
| Cash | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Customers without `/customer | records | 1 | 0 | Native records/view |
| No integration with NCIC/stolen goods databases (FBI/Interpol) | integration | 1 | 0 | Provider request records only |
| Limited ATF firearms tracking integration (some integration code exists but no real ATF connector) | integration | 1 | 0 | Provider request records only |
| No customer ID verification system (age, address for regulated items) | records | 1 | 0 | Native records/view |
| No multi | records | 1 | 0 | Native records/view |
| No audit trail dedicated module (grep showed 0 audit mentions) | records | 1 | 0 | Native records/view |
| No webhooks for stolen | integration | 1 | 0 | Provider request records only |
| No mobile app for showroom floor staff | records | 1 | 0 | Native records/view |
| Auction Price Suggest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiration Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Lifetime Value | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Theft Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Price Trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan Risk Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Counterfeit Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Report Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Negotiation Tips | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Price Lookup | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Machines | records | 2 | 0 | Native records/view |
| Planograms | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Route Optimization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Sales Analytics | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Alerts | records | 2 | 0 | Native records/view |
| Maintenance | records | 2 | 0 | Native records/view |
| Pricing v2 | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Predict Maint v2 | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Route Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai demand forecaster by machine location time for | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| route optimizer minimizing collection restocking distance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic pricing recommendations by demand inventory seasonality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive maintenance based on telemetry signatures | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| theft detection identifying cash inventory discrepancies | records | 1 | 0 | Native records/view |
| cashless wallet qr integration for modern vending | integration | 1 | 0 | Provider request records only |
| demand forecasting ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai driven route optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic pricing ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive maintenance ml | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| theft anomaly detection ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited payment processor integration only a stub integrations | integration | 1 | 0 | Provider request records only |
| cashless payment tracking | records | 1 | 0 | Native records/view |
| supplier integration for auto ordering | integration | 1 | 0 | Provider request records only |
| real time gps location tracking for the fleet | records | 1 | 0 | Native records/view |
| notifications subsystem alerts only | records | 1 | 0 | Native records/view |
| multi tenant operator separation | records | 1 | 0 | Native records/view |
| Customer churn | records | 1 | 0 | Native records/view |
| Dynamic discount | records | 1 | 0 | Native records/view |
| Supplier diversification | records | 1 | 0 | Native records/view |
| Pos demand sensing | records | 1 | 0 | Native records/view |
| Collab forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract renewal | records | 1 | 0 | Native records/view |
| Freight optimize | records | 1 | 0 | Native records/view |
| Erp sync | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |
| Guidelines | records | 1 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| Training | records | 1 | 0 | Native records/view |
| SOPs | records | 1 | 0 | Native records/view |
| Checklists | records | 1 | 0 | Native records/view |
| Audits | records | 1 | 0 | Native records/view |
| Issues | records | 1 | 0 | Native records/view |
| Best Practices | records | 1 | 0 | Native records/view |
| Financial Data | records | 1 | 0 | Native records/view |
| Announcements | records | 1 | 0 | Native records/view |
| Knowledge Base | records | 1 | 0 | Native records/view |
| Support | records | 2 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Territories | records | 1 | 0 | Native records/view |
| Royalties | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| POS | records | 2 | 0 | Native records/view |
| Margin Leak | records | 2 | 0 | Native records/view |
| AI Studio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settings | records | 1 | 0 | Native records/view |
| Resources | records | 1 | 0 | Native records/view |
| Solutions | records | 1 | 0 | Native records/view |
| Stripe | integration | 1 | 0 | Provider request records only |
| Quickbooks | integration | 1 | 0 | Provider request records only |
| Shopify | integration | 1 | 0 | Provider request records only |
| Api | records | 1 | 0 | Native records/view |
| Retail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restaurant | records | 1 | 0 | Native records/view |
| Salon | records | 1 | 0 | Native records/view |
| Multi location | records | 3 | 0 | Native records/view |
| Careers | records | 1 | 0 | Native records/view |
| Press | records | 1 | 0 | Native records/view |
| Partners | records | 1 | 0 | Native records/view |
| Community | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demo | records | 1 | 0 | Native records/view |
| App | records | 1 | 0 | Native records/view |
| Upsell | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Demand forecasting | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Drawer anomaly | records | 2 | 0 | Native records/view |
| Payment terminal | records | 2 | 0 | Native records/view |
| Receipt printing | records | 2 | 0 | Native records/view |
| Employee shifts | records | 2 | 0 | Native records/view |
| Tax jurisdictions | records | 2 | 0 | Native records/view |
| Loyalty giftcards | records | 2 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 364 feature pages were visited in the browser; 362 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 228 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

228 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
