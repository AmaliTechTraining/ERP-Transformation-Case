# Alpha Manufacturing Group (AMG): ERP Transformation Case

## 1. Company Context
You are advising **Alpha Manufacturing Group (AMG)**, a mid-sized North American industrial equipment manufacturer.

### Company Profile (Anonymized)
* **Personnel:** ~200 employees
* **Revenue:** ~$100m annual revenue
* **Footprint:** 5 operating locations (US & Canada)
* **Business Model:** Engineer-to-order capital equipment; Aftermarket parts and service business
* **Structure:** Multi-entity structure

> **Note:** Most customer orders are customized. Engineering complexity and Bill of Materials (BOM) accuracy are critical to operations and profitability.

---

## 2. Current-State Overview

### 2.1 Application Landscape (As-Is)
AMG operates a fragmented system landscape:

* **Core ERP (20+ years old)**
    * Finance (GL, AP, AR)
    * Manufacturing / MRP
    * Procurement & Inventory
    * Basic reporting (SQL → Excel)
    * ~80 users (Hosted in private cloud)
* **Engineering System (Separate database)**
    * Part number generation
    * Bill of Materials (BOM) management
    * Engineering Change Notices (ECNs)
    * Nightly file-based sync to ERP
* **Other Key Systems**
    * CAD + PDM (no workflow enforcement)
    * Cloud CRM (not integrated to ERP)
    * HRIS (US) + separate payroll (Canada)
    * Time tracking tool (partial integration)
    * Asset monitoring platform (separate Azure environment)
    * Warehouse scanning add-on
    * Heavy Excel-based reporting across functions

**Financial Metrics:**
* Total annual IT spend: **~$1.5m**
* Core application spend (excl. infra): **~$500k**

### 2.2 Structural Weaknesses
* Two separate “ERP-like” cores (Finance vs Engineering BOM).
* Nightly FTP-based file transfers (one-way, fragile).
* Manual intervention required when part import fails.
* CRM not integrated with manufacturing or finance.
* HR tools disconnected.
* Asset data siloed.
* No single KPI definition across departments.
* High reliance on individual system knowledge.

### 2.3 Observed Business Impact
* **Margin Erosion:** ~80% of custom orders experienced margin erosion last year.
* **Tracking Issues:** Labor tracking against work orders is unreliable.
* **Operations:** Manufacturing delays due to BOM sync failures.
* **Visibility:** No reliable contribution margin view; limited end-to-end visibility across value chain.
* **Governance:** Historical data is inconsistent and poorly governed.

---

## 3. Board Mandate
The Board has approved a transformation program with the following objectives:

1.  **Replace** the legacy ERP with a modern cloud ERP.
2.  **Rationalize** the application landscape.
3.  **Improve** data quality and governance.
4.  **Ensure** uninterrupted business operations.
5.  **Improve** margin transparency and KPI reporting.

**Target go-live:** ~12 months from now.

---

## 4. Take-Home Assignment
Prepare a 2–3 page executive memo addressed to AMG’s Executive Team. You may make reasonable assumptions.

### Prompt 1 – Overall Approach
How would you structure the ERP replacement program to maximize success and minimize operational risk?
* **Address:** Key objectives, Phasing approach, Top 3–5 risks, and how to control scope.

### Prompt 2 – Scope & Sequencing
What should be included in the initial ERP go-live vs. deliberately deferred?
* **Address:** Day-1 must-haves, what not to migrate initially, and customization discipline.

### Prompt 3 – Data & Reporting
Leadership wants uninterrupted access to historical data and KPIs.
* **Address:** Historical data migration, reporting during transition, and month-end close continuity.

---

### Deliverable Expectations
We are assessing:
* Clear structure
* Prioritization discipline
* Trade-off awareness
* Practical judgment
* Executive-level communication
