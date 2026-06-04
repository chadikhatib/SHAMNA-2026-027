SHAMNA-2026-027: Raw Data Repository
Study Title: From Steroid Misuse to Supportive Dermatologic Care: A KAP-Informed Translational Pilot Study in Atopic-Prone Xerotic Skin
Protocol: SHAMNA-2026-027 | ClinicalTrials.gov: NCT07618234
Authors: Chadi Khatib, Mahmoud Bitar, Haya Farhat, Nagham Saleh
Institution: Faculty of Pharmacy, Manara University, Latakia, Syria
Corresponding Author: chadi.khatib@manara.edu.sy
________________________________________
Repository Overview
This repository contains the de-identified raw datasets supporting the manuscript and supplementary materials. All data are provided in UTF-8 encoded CSV format with Arabic text preserved for the public survey dataset.
________________________________________
File Inventory
File	Description	N	Encoding
00_Data_Dictionary.csv	Comprehensive variable documentation	104 variables	UTF-8
01_HCP_KAP_Raw_Data_n120.csv	Healthcare Professional KAP survey raw data	120	UTF-8
02_Clinical_Trial_Raw_Data_n30.csv	Pilot clinical trial participant-level data	30	UTF-8
03_Public_KAP_Survey_Raw_Data_n306.csv	Public KAP survey raw data (Arabic)	306	UTF-8 with BOM
________________________________________
Dataset Descriptions
01. HCP KAP Raw Data (01_HCP_KAP_Raw_Data_n120.csv)
Population: Healthcare professionals (Dermatologists, Pharmacists, Nurses)
Sample Size: n = 120
Domains: - Demographics: Profession, experience, workplace, TCS training status - Knowledge (K1-K12): Dichotomous scoring (0/1) on TCS management principles - Attitude (A1-A12): 5-point Likert scale (1=Strongly disagree to 5=Strongly agree) - Practice (P1-P12): 5-point frequency scale (1=Never to 5=Always)
Key Features: - Reverse-scored items marked in variable names (e.g., a2_tcs_always_dangerous) - Zero-variance ceiling-effect items documented in data dictionary - Discriminating-item subset analyses supported by variable naming
________________________________________
02. Clinical Trial Raw Data (02_Clinical_Trial_Raw_Data_n30.csv)
Design: Double-blind, randomized, vehicle-controlled pilot trial (1:1:1 allocation)
Sample Size: n = 30 (10 per group)
Treatment Groups: - EEP_3pct: Ethanolic Extract of Propolis 3% - Crude_5pct: Micronized Crude Propolis 5% - Vehicle: Placebo control
Outcome Measures: | Variable | Timepoints | Scale | Type | |———-|———–|——-|——| | Clinical Dryness Score | Baseline, Week 2, Week 4 | 0-4 (ordinal) | Primary | | Local SCORAD† | Baseline, Week 2, Week 4 | Continuous | Exploratory | | Pruritus VAS | Baseline, Week 2, Week 4 | 0-10 | Secondary | | Skin Comfort | Baseline, Week 2, Week 4 | 1-5 (Likert) | Secondary | | Subject Satisfaction | Week 4 only | 1-5 (Likert) | Secondary |
† Exploratory endpoint — see manuscript Section 2.8 and SAP v2.0
________________________________________
03. Public KAP Survey Raw Data (03_Public_KAP_Survey_Raw_Data_n306.csv)
Population: Members of the Syrian public
Sample Size: n = 306 (after excluding non-consenting participants)
Language: Arabic (original response text preserved)
Encoding: UTF-8 with BOM for Excel compatibility
Domains: - Demographics: Age, sex, education, occupation, marital status, residence, insurance - Knowledge (K1-K12): Multiple-choice responses (Arabic text) - Attitude (A1-A12): 5-point Likert scale responses (Arabic text) - Practice (P1-P12): Multiple-choice and multi-select responses (Arabic text)
Note: P6 and P12 are multi-select items with comma-separated values.
________________________________________
Data Dictionary
The 00_Data_Dictionary.csv file provides comprehensive metadata for all variables:
Column	Description
dataset	Source CSV file
variable_name	Standardized variable name
data_type	Variable type (binary, ordinal, categorical, continuous, text)
description	Full variable description with scoring notes
dataset_category	Dataset category (HCP / Clinical / Public)
________________________________________
Usage Notes
For Researchers
1.	All datasets are de-identified — no personally identifiable information is included
2.	Arabic text in the public survey dataset requires UTF-8 compatible software
3.	Reverse-scored items are indicated in variable names and descriptions
4.	Multi-select items (P6, P12 in public survey) contain comma-separated values
For Reproducibility
•	Datasets correspond to the final locked database used for all manuscript analyses
•	All statistical outputs in supplementary tables are traceable to these raw data
•	Analysis code (Python/SPSS) is available in the main study GitHub repository
________________________________________
Citation
If using these data, please cite:
Khatib C, Bitar M, Farhat H, Saleh N. From Steroid Misuse to Supportive Dermatologic Care: A KAP-Informed Translational Pilot Study in Atopic-Prone Xerotic Skin. Manuscript under review. 2026.
________________________________________
Ethics and Permissions
•	Ethics Approval: SHAMNA Biomedical Ethics Committee (SHAMNA-2026-027)
•	ClinicalTrials.gov: NCT07618234
•	Data Sharing Plan: Per ClinicalTrials.gov registration — de-identified individual participant data available within 6 months following publication
•	Restrictions: Clinical photographs excluded to protect participant privacy
________________________________________
Contact
For data access inquiries or collaboration requests:
📧 chadi.khatib@manara.edu.sy
________________________________________

