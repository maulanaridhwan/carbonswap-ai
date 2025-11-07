# Carbon & Project Compliance (Legal + Operational)

This document outlines the main compliance requirements for carbon-related marketplace projects in Indonesia (e.g., CarbonSwap).  
It summarizes due diligence, carbon unit formatting, and registry integration obligations — aligned with Indonesia’s **National Carbon Economic Value (NEK)** framework.

---

## 1. Project and NGO Verification

**Requirement**  
Implement a formal **due diligence SOP** that verifies:

- The **legal status** of NGOs or implementing organizations (registered foundation or association).
- The **validity of project permits** (environmental permits, conservation, or forestry approvals).
- **Third-party verification** of emission reduction results using MRV standards (Measurement, Reporting, and Verification).
- **Alignment with official guidelines** from the Ministry of Environment and Forestry (KLHK).

**Regulatory Reference**  
- Ministry of Environment and Forestry Regulation No. 7 of 2023  
  *"Procedures for Carbon Trading in the Forestry Sector"*  
   [Official Regulation (BPK RI)](https://peraturan.bpk.go.id/Details/254282/permen-lhk-no-7-tahun-2023)

**Implication for Platform**  
CarbonSwap must ensure that each listed project has valid MRV documentation and NGO registration proof before being published on the marketplace.

---

## 2. Carbon Unit Metadata Format

**Requirement**  
Every **Carbon Unit** listed or traded must include verified metadata fields that comply with KLHK standards.  
Each carbon unit should have:

| Field | Description |
|-------|--------------|
| Registry ID | Unique identifier issued by KLHK or accredited registry |
| Volume (tCO₂e) | The amount of CO₂ equivalent reduced or absorbed |
| Verifier | Accredited third-party entity that verified the data |
| Period | Time period of emission reduction |
| Location | Coordinates / area of project implementation |
| Certificate Status | Active, retired, or pending registration |

**Regulatory Reference**  
- Ministry of Environment and Forestry Regulation No. 21 of 2022  
  *"Implementation Guidelines for Carbon Economic Value and Carbon Units"*  
   [Official Regulation (PDF, BPK RI)](https://peraturan.bpk.go.id/Download/288901/Permen%20LHK%20Nomor%2021%20Tahun%202022.pdf)

**Implication for Platform**  
Your system must standardize project data entry forms and database schema according to this structure.  
The metadata should be displayed transparently to buyers to ensure credibility and compliance.

---

## 3. Integration with National Carbon Registry

**Requirement**  
Plan an integration (via **API** or verified manual reporting) with the **National Registry System for Climate Change Control (SRN PPI)** managed by the KLHK.  
This prevents **double counting** and ensures that each carbon unit traded on CarbonSwap corresponds to an official record.

**Regulatory Reference**  
- Presidential Regulation No. 98 of 2021  
  *"Implementation of Carbon Economic Value for Achieving Nationally Determined Contributions (NDC) and Emission Control"*  
   [Official Regulation (BPK RI)](https://peraturan.bpk.go.id/Details/187122/perpres-no-98-tahun-2021)

**Implication for Platform**  
CarbonSwap must either:
- Connect directly to SRN PPI for automatic validation of project data, or  
- Require NGOs to submit proof of project registration within the SRN PPI system.  

This ensures full traceability of emission reduction certificates traded on the marketplace.

---

## Summary of Compliance Actions

| Compliance Area | Key Action | Legal Reference |
|-----------------|-------------|----------------|
| Project Verification | Verify NGO legitimacy, project permits, MRV results | Permen LHK No. 7/2023 |
| Carbon Unit Format | Use standardized metadata for carbon units | Permen LHK No. 21/2022 |
| Registry Integration | Connect or synchronize with SRN PPI registry | Perpres No. 98/2021 |

---

### Notes
- All regulations listed above are officially published by **Badan Pemeriksa Keuangan (BPK) Republik Indonesia** at [https://peraturan.bpk.go.id](https://peraturan.bpk.go.id).
- This document is for **internal reference and compliance training** within the CarbonSwap project.  
- Always verify updates directly from KLHK and BPK RI, as future amendments to NEK regulations are expected.

---

**Prepared for:**  
CarbonSwap — ESG & Carbon Offset Marketplace (Indonesia)  
**Purpose:** RAG knowledge base document for chatbot & compliance reference.  
**Last updated:** November 2025
