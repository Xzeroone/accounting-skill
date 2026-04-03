---
name: accounting
version: "1.2.0"
data_as_of: "2026-Q1"
description: "International accounting & bookkeeping for any country. Covers IFRS, US GAAP, global tax systems, e-invoicing compliance, entity types, and regional software recommendations."
---

# Accounting & Bookkeeping — International Reference

Messy books cost you money in taxes, missed deductions, and accountant fees. This skill helps you set up clean financial tracking from day one — regardless of which country you operate in. 30 minutes a week keeps you legal, informed, and out of trouble.

## Agent Instructions

**Before giving any accounting advice, always ask the user:**
1. What country are you operating in?
2. What type of entity (sole proprietor, Ltd, GmbH, LLC, etc.)?
3. What stage (pre-revenue, early revenue, growing, established)?
4. Approximate annual revenue range (helps determine which thresholds and regimes apply)?
5. What industry (SaaS, retail, professional services, manufacturing, etc. — affects COGS structure and applicable deductions)?

**Behavioral rules:**
- Filter your response to only the relevant country/region. Do NOT dump the entire reference at the user.
- Never give specific tax advice — always recommend consulting a local qualified professional (CPA, CA, ACCA, Steuerberater, etc.).
- When the user mentions a specific country, use that country's terminology (e.g., "Trade Debtors" not "Accounts Receivable" for UK users).
- Tax rates and e-invoicing mandates change frequently. When in doubt, advise the user to verify current rates with their local tax authority.
- For multi-country operations, address each country separately and flag potential transfer pricing / double taxation issues.

## Quick Start

Use this decision tree to navigate the reference:

```
User's question is about...
│
├── Which accounting standard? → Section 1 (Accounting Standards Worldwide)
├── Setting up bookkeeping?    → Section 2 (Getting Started) + Section 7 (Chart of Accounts)
├── Taxes / VAT / GST?         → Section 3 (Tax Systems) — find their country
├── Which entity type?         → Section 4 (Business Entity Types)
├── Which software?            → Section 5 (Accounting Software) — find their region
├── E-invoicing compliance?    → Section 6 (E-Invoicing) — find their country
├── Weekly/monthly routine?    → Section 8 (Bookkeeping Routine)
├── Revenue recognition?       → Section 9 (Revenue Recognition)
├── Financial reports?         → Section 10 (Financial Reports)
├── Multi-currency?            → Section 11 (Multi-Currency Accounting)
├── Common mistakes?           → Section 12 (Common Mistakes)
├── Payroll / employees?       → Section 15 (Payroll & Employer Obligations)
├── Multi-country / cross-border? → Section 16 (Transfer Pricing & Double Taxation)
├── Tax credits / R&D?         → Section 17 (Tax Credits & Incentives)
└── Terminology differences?   → Section 18 (Key Terminology: US vs UK)
```

## Core Principles

- Bookkeeping is not optional. Messy books cost you money in taxes, missed deductions, and accountant fees.
- Separate business and personal finances completely. Day one. No exceptions.
- Revenue recognition has rules. Payment received is not the same as revenue earned.
- Your country's accounting standards, tax system, and legal requirements dictate how you track and report. Always confirm with a local professional.
- 30 minutes a week keeps your books clean. 30 hours at year-end fixes what you ignored all year.

---

## 1. Accounting Standards Worldwide

### The Two Major Frameworks

**IFRS (International Financial Reporting Standards)**
- Used in **169+ jurisdictions** worldwide — the dominant global standard
- Issued by the IASB (International Accounting Standards Board), headquartered in London
- Principles-based (broader guidance, requires professional judgment)
- Required for listed companies in the EU, UK, Australia, most of Africa, most of Asia-Pacific, and most of the Middle East

**US GAAP (Generally Accepted Accounting Principles)**
- Used only in the United States — the most significant non-IFRS system
- Issued by FASB (Financial Accounting Standards Board)
- Rules-based (detailed, specific guidance for every scenario)
- No current plans to converge with IFRS

**IFRS for SMEs (Small and Medium-sized Entities)**
- Simplified version of full IFRS, designed for private companies without public accountability
- Used in 80+ jurisdictions for qualifying SMEs — especially common in Africa, Caribbean, parts of Latin America
- Significantly less complex than full IFRS (~300 pages vs ~3,000+ pages)
- If the user's country allows IFRS for SMEs and they are a private company, this is often the simplest compliant option

### Key IFRS vs US GAAP Differences

| Aspect | US GAAP | IFRS |
|---|---|---|
| Approach | Rules-based | Principles-based |
| LIFO inventory | Allowed | **Prohibited** |
| Development costs | Generally expensed | Capitalized when criteria met |
| Reversal of impairment | Prohibited | Allowed |
| Lease accounting | Single lessee model (ASC 842) | Single lessee model (IFRS 16) — largely converged |

### Standards by Region

| Region | Standard | Notes |
|---|---|---|
| **United States** | US GAAP | No IFRS adoption for domestic companies |
| **Canada** | IFRS (public) / ASPE (private) | Private companies can use simpler ASPE |
| **United Kingdom** | IFRS (listed) / UK GAAP FRS 102 (private) | FRS 105 for micro-entities |
| **Germany** | IFRS (listed consolidated) / HGB (private) | HGB is more conservative, tax-driven |
| **France** | IFRS (listed) / PCG (private) | PCG is a prescriptive national chart of accounts |
| **Australia** | AASB (IFRS-aligned) | IFRS with minor Australian modifications |
| **Japan** | J-GAAP / IFRS (mandatory for some listed, voluntary for others) | Large listed companies increasingly required to adopt IFRS. Many voluntarily use it. |
| **China** | CAS (China GAAP) | ~90-95% converged with IFRS |
| **India** | Ind AS | Substantially converged with IFRS (with carve-outs) |
| **Brazil** | BR GAAP (CPC) | Substantially converged with IFRS |
| **Singapore** | SFRS(I) | IFRS-aligned |
| **South Korea** | K-IFRS | Mandatory for listed companies |
| **UAE** | IFRS | Required for most entities |
| **South Africa** | IFRS / IFRS for SMEs | Widely adopted |
| **Most of EU** | IFRS (listed) / National GAAP (private) | Each country has its own GAAP for private entities |
| **Most of Africa** | IFRS | Required in most countries |
| **OHADA countries** | OHADA Uniform Act | 14+ francophone West/Central African countries |
| **Switzerland** | Swiss GAAP FER / OR (Code of Obligations) | FER is a recognized framework for SMEs. OR is the legal basis. Large companies use IFRS. |

**When advising:** Always identify which standard applies to the user's country and entity type. Listed/public companies typically use IFRS or US GAAP. Private/small companies often use simplified national standards.

---

## 2. Getting Started: Financial Foundation

### Day 1 Checklist (Universal)

```
Before your first dollar of revenue:
- [ ] Open a separate business bank account
- [ ] Get a business payment method (credit card or dedicated personal card for business only)
- [ ] Set up accounting software appropriate for your country (see Section 5)
- [ ] Create a chart of accounts appropriate for your business model
- [ ] Set up payment processors to deposit to business account
- [ ] Create a system for storing receipts/invoices (digital)
- [ ] Note your fiscal year and tax year dates (varies by country — see Section 3)
- [ ] Register for required tax IDs (VAT/GST number, tax registration, etc.)
- [ ] Understand your country's e-invoicing requirements (see Section 6)
```

### Separate Your Finances

**Why it matters (universal):**
- Legal protection (entity separation requires it)
- Tax deductions are easy to prove with clean records
- Makes tax prep faster and cheaper
- Investors and lenders need clean books
- Many countries legally require separate business accounts for incorporated entities

**How:**
- Open a dedicated business bank account
- Use a separate card for business expenses
- Never mix personal and business transactions
- If you must transfer, document it properly (owner draw, director's loan, capital contribution — terminology varies by country)

---

## 3. Tax Systems by Region

### Fiscal Year Differences

Not every country uses January–December:

| Fiscal Year | Countries |
|---|---|
| **Jan 1 – Dec 31** | Most of the world: US, Germany, France, China, Brazil, most of EU |
| **Apr 1 – Mar 31** | India, Japan, UK (corporations), Canada, Singapore, South Africa, Hong Kong, NZ |
| **Jul 1 – Jun 30** | Australia, Egypt, Kenya, Pakistan, Tanzania, Uganda |
| **Apr 6 – Apr 5** | UK (personal tax — unique) |
| **Oct 1 – Sep 30** | US federal government, Thailand |

**Important:** Companies in most countries can elect a non-standard year-end for corporate tax. Personal tax almost always follows the country's standard fiscal year.

### Corporate Tax Rates (Key Countries, 2026)

| Country | Rate | Notes |
|---|---|---|
| United States | 21% federal + ~4.5% state avg | Combined ~25.5% |
| United Kingdom | 19–25% | Marginal rate based on profit level |
| Germany | ~30% | 15% federal + trade tax (varies ~7–17% by municipality; ~15% average) |
| France | ~25% | |
| Japan | ~29.7% | Combined national + local |
| Australia | 25–30% | 25% for small businesses |
| Canada | ~26% | 15% federal + provincial |
| India | 25–30% | + surcharge and cess |
| Singapore | 17% | With significant exemptions |
| UAE | 9% | Introduced 2023; 15% for large MNCs |
| Ireland | 12.5% | 15% effective for large MNCs |
| Brazil | 34% | Combined |
| China | 25% | 15% for qualifying high-tech |
| South Africa | 27% | |

### VAT / GST / Sales Tax

Over **170 countries** use VAT/GST. The US is the only major developed economy without a national VAT.

| Region | System | Key Rates |
|---|---|---|
| **EU** | VAT | 17% (Luxembourg) to 27% (Hungary). Germany 19%, France 20%, UK 20%, Italy 22%, Spain 21% |
| **UK** | VAT | 20% standard, 5% reduced. Registration threshold: £90,000 |
| **Australia** | GST | 10%. Registration threshold: A$75,000 |
| **New Zealand** | GST | 15%. No threshold |
| **Canada** | GST/HST | 5% federal + provincial. Registration: C$30,000 |
| **India** | GST | 18% standard (also 5%, 12%, 28%). Registration: ₹20–40 lakh |
| **Singapore** | GST | 9%. Registration: S$1M |
| **Japan** | Consumption Tax | 10% (8% for food). No threshold for registration |
| **UAE** | VAT | 5%. Registration: AED 375,000 |
| **Saudi Arabia** | VAT | 15% |
| **South Africa** | VAT | 15% |
| **Brazil** | ICMS/IPI/PIS/COFINS | Complex multi-layered system, varies by state |
| **Mexico** | IVA | 16% (8% border zones) |
| **US** | Sales Tax | State-level, 0–10%+. No federal VAT |

### Advance Tax Payment Systems

Most countries require periodic advance tax payments:

| Country | System | Schedule |
|---|---|---|
| **US** | Quarterly estimated | Apr 15, Jun 15, Sep 15, Jan 15 |
| **UK** | Payments on Account | Jan 31 + Jul 31 (each 50% of prior year) |
| **Germany** | Vorauszahlungen | Quarterly: Mar 10, Jun 10, Sep 10, Dec 10 |
| **France** | Acomptes | Quarterly installments |
| **Australia** | PAYG Installments | Quarterly via BAS |
| **Canada** | Instalments | Mar 15, Jun 15, Sep 15, Dec 15 |
| **India** | Advance Tax | 15% by Jun 15, 45% by Sep 15, 75% by Dec 15, 100% by Mar 15 |
| **Japan** | Interim returns | 2 installments per fiscal year |
| **Spain** | Pagos fraccionados | Quarterly (Apr, Jul, Oct, Jan) |
| **Brazil** | Carnê-Leão | Monthly advance payments |

**Rule of thumb:** Set aside 25–35% of net profit for taxes, adjusted for your country's rates. Transfer to a separate savings account each month.

### Global Minimum Tax (Pillar Two)

Over 140 countries signed onto the OECD/G20 Inclusive Framework's Pillar Two rules, introducing a **15% global minimum effective tax rate** for multinational enterprises with consolidated revenue above **€750 million**. Key points:

- Applies to groups with revenue >€750M in at least 2 of the 4 preceding years
- Top-up tax imposed in the parent company's jurisdiction if subsidiaries in other countries are taxed below 15%
- Implementation is rolling out 2024–2026 across most jurisdictions
- Even businesses below the €750M threshold may be affected if they are part of a larger group
- **For most SMEs and startups, Pillar Two does not apply.** But if the user is part of a large multinational group or growing toward that scale, flag this.

### Common Business Deductions (Universal)

Most countries allow deductions for:
- Operating expenses (rent, utilities, office supplies, insurance)
- Employee wages and benefits
- Cost of goods sold
- Depreciation/amortization of capital assets
- Business travel (meals often limited to 50%)
- Professional fees (accounting, legal)
- Marketing and advertising
- Interest on business loans
- Bad debts written off
- Home office (rules vary significantly by country)

**Commonly non-deductible worldwide:**
- Fines and penalties
- Personal expenses
- Political contributions
- Dividends paid to shareholders
- Entertainment (restricted in many countries)

### Self-Employment / Freelancer Tax Highlights

| Country | Key Requirements |
|---|---|
| **US** | Self-employment tax 15.3% + income tax. Quarterly estimates. Schedule C + SE. |
| **UK** | Self-Assessment. Class 4 National Insurance (Class 2 voluntary only since Apr 2024). Trading allowance: £1,000 tax-free. |
| **Germany** | Income tax 14–45%. VAT registration. Kleinunternehmerregelung exempts <€22K turnover from VAT. |
| **France** | Micro-entrepreneur regime: flat-rate social charges ~22% for services. URSSAF collects. |
| **Australia** | ABN required. GST at A$75K threshold. PAYG quarterly installments. |
| **Canada** | Report on personal return. GST/HST at C$30K. CPP contributions both portions. |
| **India** | Presumptive taxation (Section 44AD): 6% of digital turnover / 8% of non-digital turnover deemed income for <₹2Cr. GST at ₹20–40L. |
| **Singapore** | Taxed at personal rates (0–22%). No separate SE tax. No capital gains tax. |
| **UAE** | No personal income tax. 9% corporate tax above AED 375K. No personal tax for freelancers. |
| **Spain** | Autónomo registration. Social security ~€300/month minimum. Quarterly filings. |

---

## 4. Business Entity Types by Country

### Common Entity Types

| Country | Entity Types | Key Characteristics |
|---|---|---|
| **US** | LLC, S-Corp, C-Corp, Sole Proprietorship | LLC = pass-through, flexible. S-Corp = pass-through, shareholder limits. C-Corp = double taxation, VC-friendly. |
| **UK** | Ltd, LLP, Sole Trader, PLC | Ltd = most common. LLP = professionals. Sole Trader = simplest, unlimited liability. |
| **Germany** | GmbH, UG, GbR, e.K., AG | GmbH = €25K min capital. UG = "mini-GmbH" from €1. AG = public, €50K. |
| **France** | SARL, SAS/SASU, EURL, Auto-entrepreneur | SAS = flexible, increasingly popular. Auto-entrepreneur = simplified micro regime. |
| **Australia/NZ** | Pty Ltd, Sole Trader, Partnership, Trust | Pty Ltd = most common. Trust = common for tax planning. |
| **Singapore** | Pte Ltd, LLP, Sole Proprietorship | Pte Ltd = most common, max 50 shareholders. |
| **India** | Pvt Ltd, LLP, OPC, Sole Proprietorship | OPC = One Person Company. Pvt Ltd = most common for startups. |
| **Japan** | KK, GK | KK = stock company, prestigious. GK = LLC-like, simpler, cannot go public. |
| **Brazil** | LTDA, S.A., MEI | MEI = simplified micro-entrepreneur (~R$81K revenue cap). LTDA = most common. |
| **UAE** | FZ-LLC, LLC, FZE | FZ-LLC = 100% foreign ownership in free zones. Mainland LLC = 100% foreign now possible in most sectors. |
| **Switzerland** | AG (SA), GmbH (Sàrl), Sole proprietorship | AG = stock corporation, min CHF 100K capital. GmbH = limited liability, min CHF 20K. Popular for holding companies. |

### Bookkeeping Legal Requirements

**Double-entry bookkeeping:** Required for incorporated entities in virtually every jurisdiction. Sole proprietors and micro-businesses often have simplified requirements.

**Certified software requirements:**
| Country | Requirement |
|---|---|
| **Germany** | Strict — GoBD compliance required. Software must ensure immutability, traceability, completeness. Tax authorities require direct digital access. |
| **Brazil** | Strict — ECD/SPED requires government-approved format transmission. Certified software required for e-invoicing. |
| **France** | Partial — Must produce FEC-compliant files for tax audits. |
| **Italy** | Strict — All B2B e-invoicing via SDI. POS systems must use certified devices. |
| **India** | Partial — GST e-invoicing for businesses above thresholds. Must comply with GSTN formats. |
| **UK** | MTD-compatible software required for VAT filing. HMRC maintains compatible list. |
| **US** | No certification required. Any accurate system accepted. SOX internal controls for public companies. |
| **Japan** | No certification. Qualified Invoice System (Oct 2023) requires registration numbers on invoices. |
| **UAE** | No certification. FTA requires specific format records. |

**Record retention periods:**
| Country | Period |
|---|---|
| US | 3–7 years (IRS standard 3, up to 7 for bad debts, indefinite for fraud) |
| UK | 6 years from accounting period end |
| Germany | 10 years (HGB) |
| France | 10 years |
| Australia | 5 years |
| New Zealand | 7 years |
| Singapore | 5 years |
| India | 8 years (Companies Act), 7 years (Income Tax) |
| Japan | 7 years |
| Brazil | 10+ years |
| UAE | 5–7 years |
| China | 15 years (among the longest globally) |
| Switzerland | 10 years |
| **Global baseline** | **5–7 years** is the most common worldwide; 10 years in many EU/BR/CH |

**Mandatory audit thresholds (key countries):**
| Country | Threshold |
|---|---|
| UK | Turnover > £15M, balance sheet > £7.5M, or > 50 employees (fail 2 of 3) |
| Germany | Medium/large: > €12M turnover, > €6M balance sheet, or > 50 employees |
| France | Medium: > €6M turnover, > €3M balance sheet, or > 25 employees |
| Australia | Large proprietary: revenue > A$50M, assets > A$25M, or > 50 employees |
| Singapore | All companies unless exempt (revenue ≤ S$10M, ≤ 20 shareholders) |
| India | All companies unless exempt (small companies below thresholds) |
| Japan | Large: capital ≥ ¥500M or liabilities ≥ ¥20B |

---

## 5. Accounting Software by Region

### Global Software

| Software | Best For | Regions Supported | Notes |
|---|---|---|---|
| **QuickBooks** | US, Canada, UK, AU | 33+ countries | Deep US tax/payroll. Limited EU/Asia localization. |
| **Xero** | NZ, AU, UK, US, SA, SG | 180+ countries | Multi-currency, IFRS-aligned. Strong in English-speaking markets. |
| **Zoho Books** | India, UAE, EU, global SMBs | 100+ countries | Affordable, country-specific tax editions (GST, VAT, sales tax). |
| **Sage** | UK, Europe, South Africa | Global | Strong UK VAT (MTD compliant). Sage/Pastel dominates South Africa (~90% market). |
| **FreshBooks** | Service businesses, US/CA/UK/AU | English-speaking | Best for invoicing-focused service businesses. |
| **Wave** | Freelancers, US/Canada/UK | US, Canada, UK | Free but very limited international support. |
| **SAP Business One** | Mid-market, global | 100+ countries | Extensive localization. Requires significant implementation. |
| **Oracle NetSuite** | Scaling internationally | Global | Multi-subsidiary, multi-currency, multi-tax. Strong for global expansion. |
| **Odoo** | Open-source, global | Global | Community-built localizations. Coverage varies by country. |
| **Microsoft Dynamics 365 Business Central** | Mid-market, global | 100+ countries | Strong localization, integrates with Microsoft ecosystem. Growing cloud presence. |

### Europe-Specific

| Region | Software | Notes |
|---|---|---|
| **Germany** | DATEV, Lexware/Lexoffice | DATEV is industry standard for tax advisors. GoBD compliant. Lexoffice for freelancers/SMBs. |
| **France** | Cegid, Pennylane, Sage France | Cegid is major player. Pennylane fast-growing cloud platform. |
| **UK** | Sage, Xero, QuickBooks, FreeAgent | All MTD-compliant. FreeAgent popular with freelancers (owned by NatWest). |
| **Nordics** | Visma, Fortnox, Tripletex | Visma dominates Scandinavia. Fortnox major in Sweden. |
| **Netherlands** | Exact, AFAS | Exact Online strong for SMEs with local tax compliance. |
| **Italy** | TeamSystem, Fatture in Cloud | Must integrate with SDI e-invoicing system. |
| **Spain** | Grupo Primavera, Sage Spain, A3 | Must comply with SII (4-day VAT reporting for large companies). |
| **Poland** | Comarch, Symfonia | Must integrate with KSeF e-invoicing platform (mandatory 2026). |

### Asia-Pacific

| Region | Software | Notes |
|---|---|---|
| **Australia/NZ** | MYOB, Xero, Reckon | MYOB dominant in AU. Xero founded in NZ, strong in both. |
| **Japan** | freee, Money Forward, Yayoi | freee = cloud-native, consumption tax auto-calc. Yayoi = traditional "national standard." |
| **China** | Kingdee, Yonyou | Must handle China GAAP and fapiao (official tax invoice) compliance. |
| **India** | Tally Prime, Zoho Books, Busy | Tally = dominant market leader. Built for Indian GST, e-invoicing, e-way bills. |
| **Singapore** | Xero, QuickBooks, Sleek | Sleek = Singapore-founded digital corporate services + accounting. |
| **Malaysia** | SQL Account, AutoCount | Must comply with MyInvois e-invoicing (phased 2025–2026). |

### Latin America

| Region | Software | Notes |
|---|---|---|
| **Brazil** | Conta Azul, Omie, Domínio Sistemas | Must handle NF-e/NFS-e e-invoicing, SPED, complex multi-layered tax. |
| **Mexico** | CONTPAQi, AdminPAQ, Facturama | Must handle CFDI 4.0 e-invoicing, PAC stamping, DIOT reporting. |
| **Argentina** | Tango Gestión, Xubio, Libro | Must integrate with AFIP electronic invoicing. |
| **Colombia** | Helisa, Siigo | Must comply with DIAN e-invoicing (CUFE validation). |

### Middle East & Africa

| Region | Software | Notes |
|---|---|---|
| **UAE** | Xero, QuickBooks, Zoho Books, Tally | All FTA-compliant for VAT. E-invoicing mandate coming 2027. |
| **Saudi Arabia** | QuickBooks, Xero, Tally, SowaanERP | Must comply with ZATCA FATOORAH e-invoicing (Phase 2). |
| **South Africa** | Sage/Pastel, Xero, QuickBooks | Sage/Pastel dominates (~90% market). VAT compliant. |
| **Pan-Africa** | Sage, QuickBooks, local solutions | Sage has deepest historical penetration across Africa. |

### Software Selection Guide

| Stage | Recommendation |
|---|---|
| **Pre-revenue / Micro** | Spreadsheet or free tool (Wave in US/CA, Zoho Books free tier globally) |
| **Early revenue** | Country-specific tool (Tally in India, freee in Japan, Lexoffice in Germany, Xero in AU/NZ/UK) |
| **Growing ($5K–50K MRR)** | QuickBooks Online, Xero, Zoho Books, or regional leader |
| **Scaling internationally** | NetSuite, SAP Business One, or multi-entity Xero/QBO |
| **Need done-for-you** | Bench (US/CA), local bookkeeping service, or regional equivalent |

**Key rule:** Choose software that is compliant with your country's tax filing, e-invoicing, and reporting requirements. Don't use US-centric tools in countries with strict fiscal compliance unless they have proper localization.

---

## 6. E-Invoicing & Fiscalization Compliance

This is one of the most important and rapidly changing areas of global accounting. **90+ countries** have implemented or announced e-invoicing mandates.

> ⚠️ **E-invoicing mandate dates are subject to frequent delays and changes.** Poland KSeF, France PPF, and Germany ZUGFeRD issuance dates have all been pushed back multiple times. Always verify current status with the relevant tax authority before making compliance decisions.

### Clearance Model (Pre-Authorization Required)

These countries require invoices to be validated by the tax authority before or shortly after issuance:

| Country | System | Status | Key Details |
|---|---|---|---|
| **Brazil** | NF-e / NFS-e | Mandatory since 2008 | Real-time SEFAZ authorization. Most complex system globally. |
| **Mexico** | CFDI 4.0 | Mandatory since 2014 | PAC stamping → SAT validation. Timbre fiscal + QR code. 5-year retention. |
| **Italy** | SDI (Sistema di Interscambio) | Mandatory since 2019 | ALL B2B/B2C must route through SDI. First EU country with mandatory B2B e-invoicing. |
| **India** | e-Invoice (IRN) | Phased since 2020 | Invoice Reference Number from NIC portal. Mandatory above ₹5 crore. |
| **Saudi Arabia** | FATOORAH (ZATCA) | Phase 1 since 2021 | Phase 2 (integration) rolling by turnover waves. B2B cleared, B2C within 24 hours. |
| **Chile** | DTE | Mandatory since 2014 | Pre-authorized by SII. |
| **Colombia** | DIAN | Mandatory since 2019 | CUFE/CUDE validation codes. |
| **Turkey** | e-Fatura | Mandatory since 2019 | Cleared through GIB platform. |
| **South Korea** | DPC | Mandatory since 2011 | Real-time tax invoice issuance. |
| **Egypt** | ETA | Mandatory since 2022 | Clearance via ETA platform. E-receipt and e-invoice. |
| **Poland** | KSeF | Mandatory Feb–Apr 2026 | Real-time validation, KSeF number assignment. |
| **France** | PPF | Mandatory Sep 2026–2027 | Y-shaped clearance model. Pre-filled VAT returns. |
| **Greece** | myDATA | 2026 | MARK validation within 48 hours. |
| **Malaysia** | MyInvois | Phased 2025–2026 | 55 mandatory fields, QR code, real-time UIN. |
| **China** | Golden Tax / Fapiao | Ongoing | Fapiao issuance through tax-controlled systems. |
| **Romania** | RO e-Factura | Mandatory since 2024 | Mandatory B2B via SPV portal. First EU country to mandate after Italy. |
| **Peru** | Sistema de Emisión Electrónica (SEE) | Mandatory since 2018 | CPE electronic invoices via SUNAT. |

### Post-Audit / Periodic Reporting Model

Invoices are valid upon issuance but must be reported within a defined period:

| Country | System | Timeline |
|---|---|---|
| **Germany** | EN 16931 (XRechnung/ZUGFeRD) | Receive from Jan 2025, issue from Jan 2027 |
| **Spain** | SII (Suministro Inmediato) | 4-day reporting for large companies. B2B mandate Jul 2027. |
| **UK** | MTD-compatible digital records | Voluntary now. Mandatory estimated Apr 2029. |
| **Singapore** | InvoiceNow (Peppol) | Phased 2025–2031. Mandatory for new businesses ≤S$1M from Apr 2029. |
| **UAE** | Peppol (PINT-AE) | Voluntary Jul 2026. Mandatory Jan 2027 (≥AED 50M), Jul 2027 (all). |
| **Belgium** | Peppol (EN 16931) | Mandatory Jan 2026 |

### Global Trend

The EU's **ViDA (VAT in the Digital Age)** directive will harmonize e-invoicing across all EU member states for intra-EU B2B transactions by **2030–2032**. Expect more countries to adopt real-time or near-real-time reporting.

**When advising:** Always check the current e-invoicing status for the user's country. This area changes frequently. Software choice MUST support the required format and integration.

---

## 7. Chart of Accounts (Universal Template)

Adapt this template to your country's requirements and chart of account standards. In many countries (Germany SKR03/04, France PCG, India Schedule III), the chart of accounts and financial statement formats are legally prescribed — always use the local mandatory format where one exists.

```
ASSETS
  Cash & Bank Accounts
  Accounts Receivable / Trade Debtors
  Inventory / Stock
  Prepaid Expenses
  Fixed Assets (Property, Equipment, Vehicles)
  Accumulated Depreciation

LIABILITIES
  Accounts Payable / Trade Creditors
  Accrued Expenses
  Deferred Revenue / Unearned Income
  Tax Payable (Income Tax, VAT/GST, Payroll Tax)
  Loans & Borrowings

EQUITY
  Share Capital / Common Stock
  Retained Earnings / Profit & Loss Appropriation
  Owner's Draw / Dividends
  Reserves

REVENUE
  Product/Service Revenue
  Other Income

COST OF GOODS SOLD (COGS) / COST OF SALES
  Direct Materials / Raw Materials
  Direct Labour
  Shipping & Delivery
  Subcontractors / Third-Party Services

OPERATING EXPENSES
  Salaries & Wages
  Rent & Utilities
  Software & Subscriptions
  Marketing & Advertising
  Professional Fees (Legal, Accounting)
  Travel & Entertainment
  Depreciation & Amortization
  Insurance
  Office & Equipment
  Education & Training
  Bank Charges & Interest
  Miscellaneous

OTHER
  Tax Expense
  Owner Draw / Distribution
  Owner Contribution / Capital Injection
```

**Industry-specific additions:**
- **SaaS / Tech:** Add `Subscription Revenue (MRR)`, `Hosting & Infrastructure`, `Payment Processing Fees` under Revenue/COGS
- **Retail / E-commerce:** Add `Purchase Returns & Allowances`, `Freight-In`, `Packaging Materials` under COGS
- **Professional Services:** Add `Billable Hours Revenue`, `Contractor Costs` under Revenue/COGS
- **Manufacturing:** Add `Work-in-Progress`, `Finished Goods`, `Manufacturing Overhead` under Assets/COGS

**Country-specific adaptations:**
- **Germany (HGB):** Must follow SKR03 or SKR04 standard chart of accounts
- **France (PCG):** Must use the national chart of accounts numbering system
- **India:** Must comply with Schedule III of Companies Act for presentation
- **Brazil:** Must follow CPC/IFRS-aligned chart with specific account coding

---

## 8. Weekly Bookkeeping Routine

Spend 30 minutes every week. It prevents the year-end panic.

```
Weekly (pick a day, be consistent):
- [ ] Categorize new transactions in accounting software
- [ ] Upload/save receipts for expenses above your country's threshold
- [ ] Reconcile bank account (does your software match your bank?)
- [ ] Note any unusual transactions to discuss with your accountant
- [ ] Check e-invoicing compliance (issued/received invoices properly filed)

Monthly (first week of each month):
- [ ] Review Profit & Loss / Income Statement
- [ ] Check: Is revenue matching what your payment processor shows?
- [ ] Check: Are expenses categorized correctly?
- [ ] Review cash balance — how many months of runway do you have?
- [ ] Set aside estimated tax payment (see Tax section)
- [ ] File VAT/GST return if required monthly/quarterly
- [ ] Reconcile all accounts

Quarterly:
- [ ] Review Balance Sheet
- [ ] Pay advance/estimated tax installments
- [ ] Review cash flow projections
- [ ] Check compliance deadlines (e-invoicing, filings, audits)

Annually:
- [ ] Prepare for year-end tax filing
- [ ] Review and update chart of accounts
- [ ] Assess if you need to upgrade accounting processes or hire help
- [ ] Review insurance coverage
- [ ] Plan next year's budget
```

---

## 9. Revenue Recognition

### The Basic Rule (Universal under IFRS 15 / ASC 606)

Revenue is recognized when you deliver the service or product, not when you receive payment.

```
Example:
- Customer pays $1,200 for annual plan on March 1
- You DON'T book $1,200 as March revenue
- You book $100/month for 12 months (March through February)

Why: You owe them 12 months of service. Until delivered, it's "deferred revenue" (a liability).
```

### Cash vs Accrual Accounting

| Method | When to Use | Notes |
|---|---|---|
| **Cash-basis** | Pre-revenue to ~$50K ARR, small businesses | Revenue = when you get paid. Simpler. Accepted for tax in many countries for small businesses. |
| **Accrual-basis** | Post-$50K ARR, seeking investment, required by IFRS/GAAP for larger entities | Revenue = when earned. More accurate. Required by most accounting standards for incorporated entities above thresholds. |

> **Note:** The $50K ARR thresholds above are approximate US-centric guidelines. Many countries have specific local thresholds that determine cash vs accrual eligibility (e.g., Germany §4(3) EÜR at €75K profit, UK VAT cash accounting at £90K turnover). Always check your country's rules.

**Country-specific notes:**
- Many countries allow small businesses to use cash-basis for tax (e.g., UK cash-basis for VAT, Germany EÜR for small businesses)
- Incorporated entities typically must use accrual-basis for financial reporting
- Always confirm with a local accountant

### When It Matters

- **Pre-$50K ARR / micro-business:** Cash-basis is simpler and usually fine for tax
- **Post-$50K ARR or seeking investment:** Switch to accrual-basis with proper revenue recognition
- **Annual/long-term contracts:** Always recognize over the service period
- **Lifetime deals:** Requires professional judgment under IFRS 15 / ASC 606 — generally recognized over the expected service period, but treatment depends on whether it constitutes a separate performance obligation. No simple rule of thumb; consult a qualified accountant.

---

## 10. Financial Reports You Should Read

### Profit & Loss (Income Statement)

Shows revenue minus expenses = profit (or loss) for a period.

```
Review monthly. Ask:
- Is revenue growing month over month?
- Are expenses growing faster than revenue?
- What are my top 3 expense categories?
- What's my profit margin? (profit / revenue × 100)
```

### Cash Flow Statement

Shows money in and money out, regardless of when revenue is "earned."

```
Review monthly. Ask:
- How much cash do I have today?
- How many months of expenses can I cover? (runway)
- Am I cash-flow positive? (more coming in than going out)
```

### Balance Sheet

Shows what you own (assets), what you owe (liabilities), and your equity.

```
Review quarterly. Needed for:
- Applying for business loans or credit
- Talking to potential investors
- Understanding deferred revenue
- Required by most accounting standards
```

---

## 11. Multi-Currency Accounting

For businesses operating across borders, multi-currency accounting is essential.

### Key Concepts

| Concept | Definition |
|---|---|
| **Functional currency** | The primary currency of the business's main economic environment (usually where it's headquartered) |
| **Presentation currency** | The currency in which financial statements are presented |
| **Foreign currency transaction** | A transaction denominated in a currency other than the entity's functional currency |
| **Exchange rate** | The rate between two currencies. Use spot rate on transaction date for most transactions. |

### How to Handle Multi-Currency Transactions

**On the transaction date:**
- Record the transaction using the spot exchange rate on that date
- Example: You invoice €1,000 when EUR/USD = 1.08. Record $1,080 as the receivable.

**On the balance sheet date:**
- Revalue foreign currency monetary items (receivables, payables, cash) using the closing rate
- Recognize FX gains/losses in the P&L (required under both IFRS and US GAAP)

**On settlement date:**
- Record the difference between the original rate and the settlement rate as an FX gain or loss

### Practical Tips

- Use accounting software with built-in multi-currency support (Xero, NetSuite, QuickBooks Multi-Currency)
- Maintain separate bank accounts in each major currency to reduce conversion costs
- Consider hedging strategies for large recurring foreign currency exposures
- Track FX gains/losses separately — they have different tax treatment in many countries
- For EU businesses: most accounting software auto-updates ECB daily rates
- For US businesses: use the IRS yearly average rates for tax reporting

### Country-Specific Notes

| Country | Notes |
|---|---|
| **US** | No specific functional currency rules for small businesses. IRS requires USD reporting. Use yearly average rates for tax. |
| **UK** | Companies Act requires GBP presentation. IAS 21 / FRS 102 Section 23 governs foreign currency translation. |
| **EU (IFRS)** | IAS 21 "The Effects of Changes in Foreign Exchange Rates" applies. Strict rules on rate selection and gain/loss recognition. |
| **Australia** | AASB 121 (equivalent to IAS 21). AUD presentation for Australian entities. |
| **India** | AS 11 governs foreign currency transactions. INR functional currency for Indian entities. |
| **Japan** | J-GAAP has specific foreign currency translation rules. JPY functional currency. |
| **Brazil** | CPC 42 / IAS 21 equivalent. BRL functional currency. Central bank publishes official rates. |

---

## 12. Common Mistakes (Global)

| Mistake | Fix |
|---|---|
| Mixing personal and business finances | Separate bank accounts from day one |
| Not tracking expenses | Categorize weekly. 30 minutes prevents 30 hours of cleanup |
| Ignoring advance tax payments | Set aside 25–35% of profit monthly (adjust for your country's rates) |
| No receipts for expenses | Save digital copies. Know your country's minimum threshold. |
| Doing books once a year | Weekly categorization, monthly review |
| DIY taxes past a certain scale | Hire a local CPA/accountant. They pay for themselves. |
| Confusing payment processor revenue with accounting revenue | Payouts include refunds, fees, timing differences, currency conversion |
| No emergency fund for the business | Keep 2–3 months of expenses in the business account |
| Using non-compliant software | Choose software certified/compliant with your country's requirements |
| Ignoring e-invoicing mandates | Check your country's status. Non-compliance can mean significant fines. |
| Not understanding your fiscal year | Know your country's tax year and filing deadlines |
| Using wrong accounting standard | Confirm whether IFRS, US GAAP, or national GAAP applies to you |

---

## 13. When to Hire Professional Help

| Stage | Recommendation |
|---|---|
| **Pre-revenue / Micro** | DIY with good software. Keep clean books from day one. |
| **Early revenue** | DIY bookkeeping. Hire accountant for annual tax filing. |
| **Growing** | Monthly bookkeeper or service. Quarterly accountant review. |
| **Established** | Full-time or outsourced bookkeeper + regular accountant. |
| **Complex (multi-country, multi-entity)** | International accounting firm or specialized advisor. |

**Finding a good accountant:**
- Look for certified professionals in your country (CPA, CA, ACCA, Steuerberater, Expert-Comptable, CA/CPA Australia, etc.)
- Ask other founders for referrals
- A good local accountant saves you more than they cost in missed deductions and avoided mistakes
- For international operations, find someone with cross-border experience

---

## 14. Success Looks Like

- Clean books that take 30 minutes/week to maintain
- Tax payments estimated and saved on schedule (no surprises)
- Clear understanding of monthly profit/loss and cash runway
- Receipts saved and categorized for every business expense
- An accountant relationship in place before you desperately need one
- Business and personal finances completely separated
- Software compliant with your country's tax and e-invoicing requirements
- Understanding of which accounting standard applies to your entity

---

## 15. Payroll & Employer Obligations

Payroll is one of the most compliance-heavy areas of business accounting. Errors lead to penalties in virtually every jurisdiction.

### Key Employer Obligations by Country

| Country | Income Tax Withholding | Social Security / Contributions | Key Filing |
|---|---|---|---|
| **US** | Federal + State withholding | FICA (Social Security 6.2% + Medicare 1.45%, employer-matched). FUTA + SUTA. | Form 941 quarterly, W-2 annually |
| **UK** | PAYE (Pay As You Earn) | Employer NIC: 13.8% above £175/week. Auto-enrolment pension: min 3% employer. | RTI payroll reporting each pay period, P60 annually |
| **Germany** | Lohnsteuer (wage tax) | Employer social: ~20% of gross (pension, health, unemployment, nursing care). | Monthly payroll reports to tax office |
| **France** | Prélèvement à la source | Employer charges: ~25–45% of gross (very high). URSSAF collects. | Monthly DSN (Déclaration Sociale Nominative) |
| **Australia** | PAYG withholding | Superannuation: 11.5% employer contribution (rising to 12% Jul 2025). | Single Touch Payroll (STP) each pay cycle |
| **Canada** | Federal + provincial withholding | CPP + EI employer contributions (1.4× EI rate). | T4 slips annually, payroll remittance monthly/quarterly |
| **India** | TDS (Tax Deducted at Source) | EPF (12% employer + 12% employee), ESI (3.25% employer). | Monthly TDS returns, annual Form 16 |
| **Japan** | Income tax withholding | Social insurance: ~15% combined employer share. | Annual withholding report by January 31 |
| **Singapore** | No withholding on local employees | CPF: 17% employer contribution (age-dependent). | Monthly CPF contribution |
| **UAE** | No income tax | No mandatory social security for expats. GPSSA for UAE nationals (12.5%). | Minimal |
| **Brazil** | IRRF (income tax) | INSS employer: ~20% + FGTS 8% + other charges. | eSocial monthly reporting |

**Key rule:** In most countries, the employer's total cost is **1.2–1.4×** the employee's gross salary (even higher in France at ~1.4–1.6×). Budget accordingly.

---

## 16. Transfer Pricing & Double Taxation

### Transfer Pricing

When a business operates in multiple countries or has related-party transactions, **transfer pricing** rules require that transactions between related entities be priced as if they were between independent parties (the "arm's length principle").

- Governed by OECD Transfer Pricing Guidelines (adopted by 140+ countries)
- Applies to: inter-company sales of goods, services, IP licensing, loans, management fees
- **Documentation requirements:** Most countries require contemporaneous documentation proving arm's length pricing
- **Penalties for non-compliance:** Can be severe — adjustments, interest, and penalties of 20–200% of the tax understated

**When it matters:**
- Multi-entity groups operating across borders
- Parent-subsidiary transactions
- Related-party service agreements
- IP licensing between group companies

### Double Taxation Treaties

Countries sign Double Taxation Agreements (DTAs/DTTs) to prevent the same income from being taxed in both countries. Over 3,000 bilateral tax treaties exist worldwide.

**Key mechanisms:**
- **Exemption method:** Income taxed in one country is exempt in the other
- **Credit method:** Tax paid in one country can be credited against tax owed in the other
- **Tie-breaker rules:** For individuals resident in two countries, treaties determine which country has primary taxing rights

**When to flag:** If the user has income from or operations in multiple countries, always check whether a DTA exists between those countries and how it affects their tax position. Recommend a specialist for cross-border tax planning.

---

## 17. Tax Credits & Incentives

Many countries offer tax credits and incentives that can significantly reduce tax liability:

### R&D Tax Credits / Incentives

| Country | Incentive | Key Details |
|---|---|---|
| **US** | R&D Tax Credit (IRC §41) | ~20% credit on qualifying R&D expenses. Now must be amortized over 5 years (domestic) or 15 years (foreign) under TCJA. |
| **UK** | R&D Tax Credits | SME scheme: up to 33% refundable credit on qualifying spend. RDEC scheme for large companies: 20% credit. |
| **France** | Crédit Impôt Recherche (CIR) | 30% credit on R&D spend up to €100M, 5% above. One of the most generous globally. |
| **Canada** | SR&ED Tax Credit | Up to 35% refundable for Canadian-controlled private corporations. |
| **Australia** | R&D Tax Incentive | 43.5% refundable for companies with <A$20M turnover (18.5% above). |
| **India** | Section 80JJAA | 30% deduction on additional employee costs for new employees in eligible sectors. |
| **Singapore** | Enterprise Development Grant | Covers up to 50% of qualifying project costs. |

### Other Common Incentives

- **Investment allowances:** Accelerated depreciation, investment tax credits (common in developing economies)
- **Regional incentives:** Tax breaks for operating in specific geographic zones (e.g., UAE free zones, India SEZs, China special economic zones)
- **Startup incentives:** Tax holidays or reduced rates for new businesses (Singapore startup tax exemption, France jeunes entreprises innovantes)
- **Green incentives:** Credits for renewable energy, EV purchases, energy-efficient buildings (expanding rapidly)

**When advising:** Always ask if the user is doing any R&D, innovation, or hiring. They may qualify for credits they're not aware of.

---

## 18. Key Terminology: US vs UK

> Note: Many other countries (Australia, Canada, NZ, India, Singapore) use a mix of both terminologies. When in doubt, use the user's country's preferred terms.

| US English | UK English |
|---|---|
| Income Statement | Profit & Loss Account |
| Inventory | Stock |
| Accounts Receivable | Trade Debtors |
| Accounts Payable | Trade Creditors |
| Revenue | Turnover |
| Net Income | Net Profit |
| Common Stock | Ordinary Shares |
| Stockholders' Equity | Shareholders' Equity |
| Checking Account | Current Account |
| Fiscal Year | Accounting Year |
| Bylaws | Articles of Association |

---

## Disclaimer

**This skill provides general reference information, not tax, legal, or accounting advice.** Tax rates, thresholds, e-invoicing mandates, and regulatory requirements change frequently. The data was compiled in **2026-Q1** and may be outdated for any specific country.

- Always verify current rates and requirements with the user's local tax authority or a qualified professional before making any decisions.
- Do not rely solely on this reference for filing taxes, choosing accounting methods, or determining compliance obligations.
- When in doubt, recommend the user consult a local certified professional (CPA, CA, ACCA, Steuerberater, Expert-Comptable, etc.).

---

## License

This skill is released under the MIT License. You are free to use, modify, and redistribute it.