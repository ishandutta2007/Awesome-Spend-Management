# Awesome-Spend-Management

## Top Spend Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Procurement Spend Control, Expense Automation & Corporate Cards*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Spend Management**. These tools enable organizations to control procurement spend, automate expense reporting, manage corporate cards, and enforce budget policies—providing visibility and governance over every dollar leaving the business.



**Examples** include Workday Spend Management, Coupa, SAP Ariba, Ivalua, Jaggaer, Brex, Ramp, Tipalti, GEP SMART, and Airbase (the category leaders).



**Open-source emphasis**: Spend Management is a domain where open-source tooling is **fragmented and largely immature**. Unlike accounting (ERPNext, Dolibarr) or procurement (VendSync), full spend management—spanning corporate cards, expense policies, procurement approvals, and budget enforcement—lacks a comprehensive self-hosted platform. The strongest projects address specific slices: **Shillinq** for procurement and supplier spend on Nextcloud, **dubbl** for accounting with expense and bill management, and **FinPilot** for expense approval workflows. Organizations seeking complete spend management should plan for commercial platforms or significant custom assembly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Spend Management](https://www.workday.com/)**  

  Spend management within Workday's financial suite, covering procurement, expenses, and supplier management integrated with Workday Financial Management and HCM for unified spend visibility.



- **[Coupa](https://www.coupa.com/)**  

  AI-native total spend management platform unifying procurement, invoicing, and supply chain; features prescriptive AI insights trained on $8T+ in transactional spend, guided buying, and intelligent fraud detection.



- **[SAP Ariba](https://www.sap.com/)**  

  Comprehensive source-to-pay suite with procurement, supplier management, and spend analytics; Joule AI assistant provides guided decision-making and intelligent sourcing automation.



- **[Ivalua](https://www.ivalua.com/)**  

  Source-to-pay platform with AI-powered Intake Management, sourcing workflows, and spend analytics; highly configurable for complex procurement methods.



- **[Jaggaer](https://www.jaggaer.com/)**  

  Spend management suite with procurement orchestration, supplier management, and spend analytics; features 1,000+ ERP connectors and 600+ REST API endpoints.



- **[Brex](https://www.brex.com/)**  

  Corporate card and spend management platform with AI-powered expense policies, automated receipt matching, and budget controls for startups and enterprises.



- **[Ramp](https://ramp.com/)**  

  Corporate card and spend management with AI that identifies savings opportunities proactively—flagging duplicate subscriptions, negotiating better SaaS contracts, and alerting finance teams to unusual spending patterns .



- **[Tipalti](https://tipalti.com/)**  

  AI-powered accounts payable automation with procurement and spend controls; processes invoices in ~2 minutes with line-level AI capture, supports payments to 200+ countries, and includes built-in tax compliance.



- **[GEP SMART](https://www.gep.com/)**  

  AI-powered source-to-pay software covering spend visibility, sourcing, contract management, supplier performance, and procure-to-pay with guided buying and autonomous procurement capabilities.



- **[Airbase](https://www.airbase.com/)**  

  Procure-to-pay solution (now part of Paylocity) with guided procurement intake, spend analytics, vendor management, AP automation, expense management, and corporate cards in a unified platform.



## Open-Source GitHub Projects



- **[Shillinq](https://github.com/ConductionNL/shillinq)**  

  Complete open-source business administration suite (EUPL) built as a Nextcloud app; covers **procurement management** with purchase orders and approval chains, **supplier management** with qualification questionnaires and document requirements, **budget planning & forecasting**, and **contract spend dashboards**; integrates bookkeeping, invoicing, and bank reconciliation; free plan available for basic procurement management without cost . **This is the most comprehensive open-source project touching procurement spend control**, though it is business administration-focused rather than a dedicated spend management platform with corporate cards or expense policies.



- **[dubbl](https://github.com/dubbl-org/dubbl)**  

  Full-featured open-source alternative to Xero and QuickBooks (API-first); includes **bills and purchase orders** with accounts payable, purchase requisitions, and landed costs; **expense management** with claims, receipt OCR, approval workflows, and recurring expenses; **budgets** with variance analysis and budget vs actual; and 25+ financial reports . **Accounting-focused**—provides the financial backbone for spend visibility but lacks procurement sourcing, supplier management, and corporate card controls.



- **[FinPilot](https://github.com/Abhinavhaldiya/FinPilot)**  

  Open-source enterprise expense approval system (React/Node.js/PostgreSQL); features **smart claim submission** with receipt uploads and auto-categorization, **multi-currency support**, **receipt OCR** for data extraction, **multi-level approval workflows** with configurable chains based on amount thresholds, **budget tracking** for departmental budgets and spending limits, and **audit trail** for compliance . **Expense-focused**—addresses employee reimbursements and approval workflows but not procurement spend or corporate cards.



- **[Rever](https://dev.to/githubopensource/stop-the-spreadsheet-scramble-meet-rever-the-open-source-ai-finance-copilot-built-on-django-and-3c3m)**  

  AI-powered finance automation platform (Django/React); features **vendor management** with a Vendor Master, **purchase order management**, **bill management with two-way matching** comparing bills against approved POs to catch discrepancies, **approval workflows**, and detailed **audit history** . **Procure-to-payment focused**—provides spend control through PO-to-bill matching but lacks sourcing, supplier scorecards, and card programs.



- **[VendSync (BidFlow)](https://github.com/RavalMunjal/VendSync)**  

  Full-stack procurement and vendor management ERP (React/Node.js/MongoDB); covers RFQ creation, quotation comparison, approval workflows, purchase order generation, and invoice creation with PDF export; includes **real-time analytics dashboards** for spending trends . **Procurement transaction-focused**—handles the RFQ-to-invoice workflow but not expense management, corporate cards, or budget enforcement.



- **[procure-to-pay-system](https://github.com/manziosee/procure-to-pay-system)**  

  Django REST API backend with React TypeScript frontend for procure-to-pay; features **multi-level approval workflows** (Staff → Approver Level 1 → Approver Level 2 → Finance), automatic PO generation on final approval, receipt validation, and AI-powered document processing with OCR . **P2P workflow-focused**—demonstrates approval chains and PO automation but lacks spend analytics and supplier management depth.



### Additional Strong Open-Source Options



- **SAP Tail Spend Management (sample)** — Open-source SAP BTP CAP application addressing tail spend with Preferred Supplier Management, region/commodity code mapping, and auto RFP event rules; a reference implementation for SAP customers rather than a standalone product .

- **spendctl** — Open-source corporate card and expense policy for AI agents, with budgets, approvals, and receipts for x402/HTTP 402 APIs; a novel niche tool for agent spend control, not human employee expense management .



**Frameworks for building custom systems**: No open-source platform provides the full spend management lifecycle (procurement + expenses + corporate cards + budget enforcement). **Shillinq** provides the broadest procurement and budget foundation on Nextcloud. **dubbl** provides accounting with bills and expense management. **FinPilot** and **Rever** provide expense approval and PO-to-bill matching respectively. A complete spend management system would require integrating these components with custom development for supplier management, card programs, and unified spend analytics—a substantial engineering effort with no ready-made starting point.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Spend management platforms handling corporate cards and financial data must comply with applicable regulations (PCI DSS for card data, SOX for financial controls, GDPR for employee data); segregation of duties and audit trails are critical.

- **Open-source spend management remains fragmented**—Shillinq covers procurement and budgets, dubbl covers accounting and expenses, FinPilot covers expense approvals, and Rever covers PO-to-bill matching; none provide corporate card programs, unified spend analytics, or supplier management depth comparable to Coupa or Brex. Organizations requiring full spend management should budget for commercial platforms.

- Verify license terms for commercial use; Shillinq uses EUPL , dubbl is open-source , FinPilot is open-source , and Rever is open-source .



---



**Made for finance leaders, procurement managers, controllers, and spend operations teams.**  

Let's make spend management more open, but with clear eyes about what open-source can currently deliver in this domain.
