# SHAMNA-2026-027: Raw Data Repository

**Study Title:** From Steroid Misuse to Supportive Dermatologic Care: A KAP-Informed Translational Pilot Study in Atopic-Prone Xerotic Skin

**Protocol:** SHAMNA-2026-027 | **ClinicalTrials.gov:** NCT07618234
**Authors:** Chadi Khatib, Mahmoud Bitar, Haya Farhat, Nagham Saleh
**Institution:** Faculty of Pharmacy, Manara University, Latakia, Syria
**Corresponding Author:** chadi.khatib@manara.edu.sy

**تاريخ الرفع على ملفات الإيداع:** 5 يونيو 2026
**Deposit Date:** 5 June 2026

---

## Repository Overview

This repository contains the de-identified raw datasets, analysis code, and study materials supporting the manuscript and supplementary materials. All data are provided in UTF-8 encoded CSV format with Arabic text preserved for the public survey dataset.

---

## Study Timeline

| Phase | Component | Start Date | End Date | Notes |
|-------|-----------|------------|----------|-------|
| Phase 1 | KAP Surveys (Public + HCP) | **11 March 2026** | — | Behavioral epidemiology phase; conducted under Faculty of Pharmacy graduation project approval (Ref. 01, dated 8 March 2026) |
| Phase 2 | Clinical Pilot Trial | 15 April 2026 | 24 May 2026 | Randomized, double-blind, vehicle-controlled |
| — | Ethics Approval | 12 April 2026 | — | SHAMNA Biomedical Ethics Committee (SHAMNA-2026-027) |
| — | Protocol Finalization | 01 April 2026 | — | Version 03, MU-URO-260426-01 |
| — | Deposit Date | 05 June 2026 | — | Repository upload to GitHub/Zenodo |

> **Note on KAP Survey Timing:** Phase 1 KAP surveys commenced on 11 March 2026 under the Faculty of Pharmacy graduation project approval (Ref. 01, dated 8 March 2026), prior to formal SHAMNA Biomedical Ethics Committee approval (12 April 2026). This reflects the academic nature of the KAP behavioral epidemiology component as a student graduation project, which was subsequently integrated into the broader translational study protocol SHAMNA-2026-027. All KAP data collection followed informed consent procedures and confidentiality protections consistent with the ethics approval.

---

## File Inventory

| File | Description | N | Encoding | Size (est.) |
|------|-------------|---|----------|-------------|
| `00_Data_Dictionary.csv` | Comprehensive variable documentation | 104 variables | UTF-8 | ~45 KB |
| `01_HCP_KAP_Raw_Data_n120.csv` | Healthcare Professional KAP survey raw data | 120 | UTF-8 | ~28 KB |
| `02_Clinical_Trial_Raw_Data_n30.csv` | Pilot clinical trial participant-level data | 30 | UTF-8 | ~12 KB |
| `03_Public_KAP_Survey_Raw_Data_n306.csv` | Public KAP survey raw data (Arabic) | 306 | UTF-8 with BOM | ~185 KB |
| `SAP_v3_0.md` | Statistical Analysis Plan (SAP) v3.0 (Final) | — | UTF-8 | ~18 KB |
| `ICF_v4_Final_IRB.md` | Informed Consent Form (English) | — | UTF-8 | ~12 KB |
| `CONSORT_2010_Pilot_Checklist.md` | CONSORT 2010 Pilot Extension Checklist | — | UTF-8 | ~22 KB |
| `SPIRIT_2013_Checklist.md` | SPIRIT 2013 Protocol Checklist | — | UTF-8 | ~16 KB |
| `Two_Bilingual_Questionnaires_SHAMNA-2026-027.md` | Two bilingual KAP questionnaires (Arabic/English) | — | UTF-8 with BOM | ~85 KB |
| `Supplementary_Tables.txt` | Supplementary materials and tables (S1–S18) | — | UTF-8 | ~155 KB |

**Total Repository Size (estimated):** ~578 KB

---

## Dataset Descriptions

### 01. HCP KAP Raw Data (`01_HCP_KAP_Raw_Data_n120.csv`)

**Population:** Healthcare professionals (Dermatologists, Pharmacists, Nurses)
**Sample Size:** n = 120

**Domains:**
- **Demographics:** Profession, experience, workplace, TCS training status
- **Knowledge (K1-K12):** Dichotomous scoring (0/1) on TCS management principles
- **Attitude (A1-A12):** 5-point Likert scale (1=Strongly disagree to 5=Strongly agree)
- **Practice (P1-P12):** 5-point frequency scale (1=Never to 5=Always)

**Key Features:**
- Reverse-scored items marked in variable names (e.g., `a2_tcs_always_dangerous`)
- Zero-variance ceiling-effect items documented in data dictionary
- Discriminating-item subset analyses supported by variable naming

**Ceiling Effect Note:** 41.7% of items exhibited zero variance (Knowledge: K1-K6; Attitude: A4, A6, A8, A10; Practice: P2, P4, P6, P8, P10). Discriminating-item subset analyses exclude these items for accurate expertise gradient assessment.

---

### 02. Clinical Trial Raw Data (`02_Clinical_Trial_Raw_Data_n30.csv`)

**Design:** Double-blind, randomized, vehicle-controlled pilot trial (1:1:1 allocation)
**Sample Size:** n = 30 (10 per group)

**Treatment Groups:**
- **EEP_3pct:** Ethanolic Extract of Propolis 3%
- **Crude_5pct:** Micronized Crude Propolis 5%
- **Vehicle:** Placebo control

**Outcome Measures:**

| Variable | Timepoints | Scale | Type |
|----------|------------|-------|------|
| Clinical Dryness Score | Baseline, Week 2, Week 4 | 0-4 (ordinal) | Primary |
| Local SCORAD† | Baseline, Week 2, Week 4 | Continuous | Exploratory |
| Pruritus VAS | Baseline, Week 2, Week 4 | 0-10 | Secondary |
| Skin Comfort | Baseline, Week 2, Week 4 | 1-5 (Likert) | Secondary |
| Subject Satisfaction | Week 4 only | 1-5 (Likert) | Secondary |

† Exploratory endpoint — see manuscript Section 2.8 and SAP v4.0

---

### 03. Public KAP Survey Raw Data (`03_Public_KAP_Survey_Raw_Data_n306.csv`)

**Population:** Members of the Syrian public
**Sample Size:** n = 306 (after excluding non-consenting participants)
**Language:** Arabic (original response text preserved)
**Encoding:** UTF-8 with BOM for Excel compatibility

**Domains:**
- **Demographics:** Age, sex, education, occupation, marital status, residence, insurance
- **Knowledge (K1-K12):** Multiple-choice responses (Arabic text)
- **Attitude (A1-A12):** 5-point Likert scale responses (Arabic text)
- **Practice (P1-P12):** Multiple-choice and multi-select responses (Arabic text)

**Note:** P6 and P12 are multi-select items with comma-separated values.

**Attitude Scoring Note:** Items A4, A5, A8, A9, A10, A11 are reverse-scored (formula: 6 - response value) as they represent negatively worded statements. Higher composite scores consistently reflect positive/professional attitudes.

---

### 04. Statistical Analysis Plan (`SAP_v3_0.md`)

**Version:** v4.0 (Final)
**Date Finalized:** 2026-05-20
**Database Lock:** 2026-05-24
**Unblinding:** 2026-05-24 (after locked analysis report approval)

**Amendment History:**
- v1.0: 2026-04-01 (locked before enrollment)
- v2.0: 2026-04-12 (added SCORAD† exploratory endpoint)
- v3.0: 2026-05-15 (minor clarifications)
- v4.0: 2026-05-20 (finalized before database lock)

**Certification:** This SAP v4.0 was finalized and locked on 2026-05-20, before database lock (2026-05-24) and treatment unblinding. No post-hoc modifications to outcomes, analyses, or interpretation frameworks were introduced after unblinding.

---

### 05. Informed Consent Form (`ICF_v4_Final_IRB.md`)

**Version:** 003 / 01 April 2026
**Language:** English
**Compliance:** Declaration of Helsinki, ICH-GCP guidelines
**Ethics Approval:** SHAMNA Biomedical Ethics Committee (SHAMNA-2026-027), dated 12 April 2026

---

### 06. CONSORT 2010 Pilot Extension Checklist (`CONSORT_2010_Pilot_Checklist.md`)

**Compliance:** 96% fully reported (74/77 items)
**Partially Reported:** 2 items (3c: progression criteria; P2: Go/Amend/Stop criteria)
**Not Applicable:** 2 items (14b, 17b)
**Date:** 2026-06-05

---

### 07. SPIRIT 2013 Checklist (`SPIRIT_2013_Checklist_Updated.md`)

**Compliance:** 97% fully reported (33/34 items)
**Partially Reported:** 1 item (26: Auditing — pilot phase; independent auditing deferred to definitive trials)
**Date:** 2026-06-05

---

### 08. Two Bilingual Questionnaires (`Two_Bilingual_Questionnaires_SHAMNA-2026-027.md`)

**Contents:**
- Questionnaire 1: Public KAP Survey (Arabic + English)
- Questionnaire 2: Healthcare Professional KAP Survey (Arabic + English)
- Scoring Key and Notes (Public + HCP)
- Ceiling Effect Notes
- Data Dictionary References
- Ethics and Permissions

**Version:** 1.0 (Final) | **Date:** 2026-06-05

**Language Note:** Both Arabic and English versions are provided to preserve the original study language (Arabic) while ensuring international accessibility (English). The public survey was administered in Arabic; the HCP survey was administered in Arabic. English translations are provided for international peer review and reproducibility purposes.

---

### 09. Supplementary Tables (`Supplementary_Tables_v8.txt`)

**Contents:** Tables S1–S18 covering:
- S1: Full KAP Public Survey Frequencies (n=306)
- S2: Full KAP HCP Survey Frequencies (n=120)
- S3: Cronbach's Alpha Detailed Breakdown
- S4: Item-Level Variance Analysis (n=120)
- S5: TCS Training vs. KAP Domain Scores
- S6: Distribution of KAP Levels
- S7: Logistic Regression — TCS Training as Predictor
- S8: Correlation Analysis Between KAP Domains
- S9: Fisher Exact Test — Predictors of Adequate Practice
- S10: Detailed Local SCORAD† Data by Participant (n=30)
- S11: Post-Hoc Power Analysis and Sample Size Projections
- S12–S17: Complete Statistical Outputs (Normality, Kruskal-Wallis, Mann-Whitney U, Wilcoxon, Friedman, Cliff's Delta)
- S18: Methodological Footnotes and Statistical Framework

---

## Data Dictionary

The `00_Data_Dictionary.csv` file provides comprehensive metadata for all variables:

| Column | Description |
|--------|-------------|
| `dataset` | Source CSV file |
| `variable_name` | Standardized variable name |
| `data_type` | Variable type (binary, ordinal, categorical, continuous, text) |
| `description` | Full variable description with scoring notes |
| `dataset_category` | Dataset category (HCP / Clinical / Public) |

---

## Usage Notes

### For Researchers

1. All datasets are de-identified — no personally identifiable information is included
2. Arabic text in the public survey dataset requires UTF-8 compatible software
3. Reverse-scored items are indicated in variable names and descriptions
4. Multi-select items (P6, P12 in public survey) contain comma-separated values
5. Discriminating-item subsets for HCP analyses exclude zero-variance ceiling-effect items

### For Reproducibility

- Datasets correspond to the final locked database used for all manuscript analyses
- All statistical outputs in supplementary tables are traceable to these raw data
- Analysis code (Python/SPSS) is available in the main study GitHub repository
- Statistical Analysis Plan (SAP) versions: v1.0 (primary), v2.0 (exploratory SCORAD† added), v3.0 (final locked)

---

## Data Integrity

### Checksums (SHA-256)

| File | SHA-256 Hash |
|------|--------------|
| `00_Data_Dictionary.csv` | [To be generated upon final upload] |
| `01_HCP_KAP_Raw_Data_n120.csv` | [To be generated upon final upload] |
| `02_Clinical_Trial_Raw_Data_n30.csv` | [To be generated upon final upload] |
| `03_Public_KAP_Survey_Raw_Data_n306.csv` | [To be generated upon final upload] |
| `SAP_v4_0.md` | [To be generated upon final upload] |
| `ICF_v4_Final_IRB.md` | [To be generated upon final upload] |
| `CONSORT_2010_Pilot_Checklist.md` | [To be generated upon final upload] |
| `SPIRIT_2013_Checklist.md` | [To be generated upon final upload] |
| `Two_Bilingual_Questionnaires_SHAMNA-2026-027.md` | [To be generated upon final upload] |
| `Supplementary_Tables.txt` | [To be generated upon final upload] |

> **Note:** SHA-256 checksums will be generated and populated upon final repository upload to verify data integrity. Users can verify file integrity by comparing local hash values against those published here.

---

## Citation

If using these data, please cite:

> Khatib C, Bitar M, Farhat H, Saleh N. From Steroid Misuse to Supportive Dermatologic Care: A KAP-Informed Translational Pilot Study in Atopic-Prone Xerotic Skin. Manuscript under review. 2026.

---

## Ethics and Permissions

- **KAP Surveys:** Faculty of Pharmacy graduation project approval (Ref. 01, dated 8 March 2026)
- **Clinical Trial Ethics Approval:** SHAMNA Biomedical Ethics Committee (SHAMNA-2026-027), dated 12 April 2026
- **ClinicalTrials.gov:** NCT07618234 (registered as double-blind, randomized, vehicle-controlled pilot trial)
- **Protocol:** MU-URO-260426-01, Version 03, dated 01 April 2026
- **Data Sharing Plan:** Per ClinicalTrials.gov registration — de-identified individual participant data available within 6 months following publication
- **Restrictions:** Clinical photographs excluded to protect participant privacy

---

## Contact

For data access inquiries or collaboration requests:
📧 chadi.khatib@manara.edu.sy

---

*Repository version: 1.0 | Last updated: 5 June 2026*
