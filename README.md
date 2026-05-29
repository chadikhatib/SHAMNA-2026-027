# SHAMNA-2026-027: KAP-Guided Translational Pilot Study in Atopic Dermatitis

**ClinicalTrials.gov:** NCT07618234  
**Protocol:** SHAMNA-2026-027 v1.0 | **Design:** Quadruple-Blind, Randomized, Vehicle-Controlled, Parallel-Group  
**N = 66** (33 Active / 33 Placebo) | **PP = 63** (33 Active / 30 Placebo)

---

## 📁 Repository Structure

| Directory | Contents |
|-----------|----------|
| `protocol/` | Study protocol (S1), SAP v1.0 (S2), amendments (S3) |
| `data/` | Raw and processed datasets (CSV) + data dictionary |
| `analysis/` | Python statistical analysis scripts |
| `figures/` | Publication-ready images (300 dpi) |
| `supplementary/` | Supplementary tables and methods |
| `checklists/` | CONSORT 2010, SPIRIT 2013, STROBE checklists |
| `docs/` | Ethics approvals and regulatory documents |

---

## 🔬 Study Overview

| Parameter | Value |
|-----------|-------|
| **Registration** | NCT07618234 |
| **Status** | Registered, posting within 2 business days |
| **Population** | Adults with mild-to-moderate atopic dermatitis |
| **Intervention** | Active: Propolis-based formulation |
| **Control** | Vehicle (placebo) |
| **Primary Endpoint** | SCORAD-50 response at Week 6 |
| **Secondary Endpoints** | SCORAD-75, SCORAD-90, VAS, Comfort, Shine |
| **Analysis Population** | Per-Protocol (PP) = 63 |

---

## 📊 Key Verified Results (PP Population)

| Outcome | Active (n=33) | Vehicle (n=30) | p-value | Effect Size |
|---------|---------------|----------------|---------|-------------|
| SCORAD-50 | 78.8% | 20.0% | p = 0.0003 | Cliff's delta = 0.852 (Large) |
| SCORAD-75 | 36.4% | 6.7% | p = 0.005 | Cliff's delta = 0.801 (Large) |
| SCORAD-90 | 12.1% | 0.0% | p = 0.114 | — |
| VAS delta | -52.7% | -19.0% | p = 0.0003 | Cliff's delta = 0.801 (Large) |
| Comfort delta | +1.73 | +0.60 | p = 0.001 | Cliff's delta = 0.712 (Large) |

*All p-values exact. Effect sizes per Romano et al. (2006).*

---

## ⚠️ Critical Rules

- **NEVER** use old incorrect values (pre-correction SCORAD-75, VAS delta, Comfort delta)
- **NEVER** SMS/SPS in any file (deleted from all materials)
- **ALWAYS** "Quadruple-Blind" (not "Double-Blind")
- **ALWAYS** exact p-values (e.g., p = 0.0003, not p less than 0.05)

---

## 🚫 Retired Metrics

The following were removed due to lack of established methodology:
- **SMS** (Steroid Misuse Score)
- **SPS** (Steroid Phobia Score)

---

## 📚 Citation

```bibtex
@dataset{shamna2026,
  author = {Khatib, Chadi and [Co-authors]},
  title = {SHAMNA-2026-027: KAP-Guided Translational Pilot Study in Atopic Dermatitis},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/chadikhatib/SHAMNA-2026-027}
}


  title = {SHAMNA-2026-027: KAP-Guided Translational Pilot Study in Atopic Dermatitis},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/chadikhatib/SHAMNA-2026-027}
}

⚠️ Academic Access Only
This repository is intended for academic researchers and health professionals only.
Permitted:

    Viewing protocol and datasets
    Citation in published research (with attribution)
    Scientific correspondence with authors

Prohibited:

    Commercial use in any form
    Modification or redistribution of modified data
    Use in training commercial AI models
    Claiming authorship or ownership

📧 Contact
For academic inquiries:
Chadi Khatib — Manara University
Last updated: 2026-05-30 | Verified against Protocol S1 and raw data
