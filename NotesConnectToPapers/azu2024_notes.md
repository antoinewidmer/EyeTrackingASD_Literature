---
citekey: azu2024
category:
  main: 
  sub: 
device:
  Type: 
  sampling_rate: 
Participants:
  Total: 
  ASD_boys: 
  ASD_girls: 
  TD_boys: 
  TD_girls: 
code_repo: 
dataset:
---

### 📌 Summary

- The study examines **clinician–caregiver informant discrepancies** in autism diagnosis and how they relate to **sex, age at diagnosis, and intervention use**.
- **280 autistic children (6–11 years old)** were analyzed using **ADOS-2 (clinician assessment)** and **SRS-2 (caregiver report)**.
- **Clinicians rated autism features higher than caregivers for boys** and **lower than caregivers for girls**, highlighting potential biases in diagnostic assessments.
- **Greater discrepancies** (clinicians rating lower than caregivers) were associated with **later autism diagnosis and reduced intervention hours**.
- The study underscores the need for **improving diagnostic procedures** to **better capture the female autism phenotype** and ensure **timely interventions**.

---

### 🔬 Methods

#### Study Design

- **Cross-sectional study** using **variable-centered and person-centered approaches** to analyze informant discrepancies.
- **Autism features were assessed using two measures**:
    - **ADOS-2 (Autism Diagnostic Observation Schedule, 2nd edition)** – clinician report.
    - **SRS-2 (Social Responsiveness Scale, 2nd edition)** – caregiver report.
- **Statistical analyses** included **latent profile analysis (LPA)** to identify subgroups based on clinician–caregiver rating differences.

---

#### Participants

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 280 autistic children (6–11 years old) |
| **Sex Distribution** | 215 males (76.8%), 65 females (23.2%) |
| **Race/Ethnicity**  | 67.9% White, 7.9% Black, 5.4% Asian, 16.1% Multiracial |
| **Average Full-Scale IQ** | 96.6 (SD = 18.1) |
| **ADOS-2 Calibrated Severity Score** | Mean = 7.65 (SD = 1.77) |
| **Age at Diagnosis** | Mean = 47.93 months (~4 years) |
| **Hours of Intervention** | Mean = 38.46 hours in past 6 weeks |

**Criticism**:

- **Predominantly male sample** limits **generalizability to autistic females**.
- **Lack of racial/ethnic diversity analysis**—differences in **diagnosis rates across racial groups** were not explored.
- **Participants were required to have an IQ above 60**, excluding **lower-functioning autistic individuals**.

---

#### Tasks for Participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **ADOS-2 Assessment** | Standardized autism diagnosis | Structured clinician-led assessment | Social affect, repetitive behaviors |
| **SRS-2 Questionnaire** | Parent-reported autism traits | 65-item caregiver questionnaire | Social communication, restricted interests |
| **Developmental History Survey** | Collect age of diagnosis data | Parent report | Age at first ASD diagnosis |
| **Intervention Use Survey** | Measure intervention exposure | Parent report | Number of therapy hours received |


**Criticism**:

- **ADOS-2 may not fully capture the female autism phenotype**, leading to **underdiagnosis in girls**.
- **SRS-2 relies on parental perception**, which may introduce **subjective biases**.

---

#### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **ADOS-2 Standardized Materials** | Structured behavioral observation | Includes toy-based social interaction tasks |
| **Survey Software (REDCap)** | Parent questionnaire administration | Web-based data collection tool |
| **SPSS & R Software** | Statistical Analysis | Used for discrepancy modeling |


**Criticism**:

- **No AI-driven or eye-tracking tools used**, which could **objectively quantify social gaze and interaction differences**.
- **Potential rater bias in ADOS-2 evaluations** due to **subjectivity in clinician scoring**.

---

#### Data Analysis

| Feature Category        | Feature Name             | Related Task | Measurement Description |
|------------------------|-------------------------|-------------|--------------------------|
| **Autism Severity**   | ADOS-2 Calibrated Severity Score (CSS) | ADOS-2 Assessment | Clinician-rated ASD severity (1-10 scale) |
| **Social Communication** | SRS-2 Social Communication Index | SRS-2 Questionnaire | Parent-reported social communication difficulties |
| **Informant Discrepancy** | Standardized Difference Score (SDS) | ADOS-2 vs. SRS-2 | Difference between clinician and caregiver ratings |
| **Diagnosis Age Impact** | Correlation with Discrepancy | Developmental History | Relationship between rating gaps and age at diagnosis |
| **Intervention Impact** | Correlation with Discrepancy | Intervention Survey | Relationship between rating gaps and intervention hours |

**Criticism**:

- **No direct behavioral data**—only relies on **questionnaires and structured observations**.
- **Informant discrepancies were measured as absolute differences**, which **assume clinicians as the "gold standard"**.

---

### 📊 Results & Key Findings

#### Key Findings:

- **Clinicians rated autism traits higher than caregivers for males** but **lower than caregivers for females**.
- **Larger discrepancies (clinicians rating lower) were associated with later autism diagnosis**.
- **Children with higher clinician ratings relative to caregivers received more intervention hours**.
- **Latent Profile Analysis (LPA) identified two groups**:
    1. **Clinician-Higher than Caregiver Group** (more boys, earlier diagnosis, more intervention).
    2. **Caregiver-Higher than Clinician Group** (more girls, later diagnosis, fewer interventions).

---

### Implications:

- **Reveals gender biases in ASD diagnosis**—female autism traits may be **under-recognized by clinicians**.
- **Supports need for multi-informant diagnostic frameworks** to **reduce gender and age biases**.
- **Suggests that late-diagnosed children may require additional screening for missed early interventions**.

---

### 🔍 Related Work

- **Aligns with past research (Neuhaus et al., 2018) showing informant discrepancies in ASD assessment**.
- **Supports prior findings (Hull et al., 2020) on female camouflaging reducing clinician-detected ASD traits**.
- **Extends work (Kaat et al., 2021) showing that male ASD traits are rated higher in clinical settings**.

---

### 📝 Observations

#### Strengths of the Study

✅ **Largest study to date examining clinician–caregiver discrepancies in autism ratings**.  
✅ **Uses both variable-centered and person-centered analyses** to validate findings.  
✅ **Provides empirical evidence for sex differences in informant discrepancies**.  
✅ **Reinforces the need for tailored diagnostic tools for females**.

---

#### Major Concerns and Challenges

⚠ **Assumes Clinician Ratings as the “Gold Standard”**

- **ADOS-2 may underdiagnose autistic girls**, yet **this discrepancy is framed as an error in caregiver reporting**.
- **Future research should examine if clinicians themselves are systematically misidentifying ASD in girls**.

⚠ **Lack of Longitudinal Follow-Up**

- Study **does not track whether later-diagnosed children eventually receive the same level of intervention**.
- **Would be useful to see if intervention intensity later equalizes outcomes**.

⚠ **Potential Rater Bias in Caregiver Reports**

- Caregivers **may underreport or overreport symptoms** depending on **prior knowledge and expectations**.
- **Cross-validation with real-time behavioral data (e.g., home video analysis, AI-driven assessments) would strengthen conclusions**.

⚠ **Limited Socioeconomic and Racial Analysis**

- **Most participants were White and high-income**, limiting **generalizability to marginalized groups**.
- **Differences in access to diagnosis and intervention across racial/ethnic groups remain unexplored**.

---

### Final Verdict: Important but Needs More Behavioral Data

✅ **Confirms gender biases in ASD diagnosis and intervention access**.  
⚠ **Relies too heavily on subjective reports, requiring behavioral and AI-based verification**.  
🚀 **Future studies should integrate machine learning and real-world behavior tracking to minimize rating biases**.