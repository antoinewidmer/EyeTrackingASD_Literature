---
citekey: pierce2021
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


## 📌 Summary

- The **Get SET Early** model was developed to improve early detection and referral for autism spectrum disorder (ASD).
- The study involved **203 pediatricians** who conducted **57,603 screenings** using the **Communication and Symbolic Behavior Scales (CSBS) Infant-Toddler Checklist**.
- Screening occurred at **12, 18, and 24 months** during well-baby checkups.
- Pediatricians referred only **one-third of screen-positive toddlers**, often citing a lack of confidence in the screening tool.
- If parents **expressed concerns**, the likelihood of referral **doubled**, and the probability of an **ASD diagnosis increased by 37%**.
- **897 toddlers** underwent further evaluation, with **approximately half diagnosed with ASD**, yielding a **1% ASD prevalence** in the screened cohort.
- The model improved **early referral and treatment**, with most referred toddlers beginning treatment by **15-19 months**.

---

## 🔬 Methods

### **Study Design**

- **Objective:** Evaluate the efficacy of the Get SET Early model in improving early ASD detection and treatment.
- **Approach:** Large-scale, community-based **longitudinal study** across **San Diego County**, involving pediatricians in diverse settings.
- **Screening Tool:** CSBS Infant-Toddler Checklist, a broadband tool detecting various developmental delays.
- **Key Metrics:**
    - Referral rates
    - Age at first evaluation
    - Age at treatment initiation
    - Parent concerns' influence on referral

---

### **Participants**

|Characteristic|Details|
|---|---|
|**Total screened**|44,079 unique children (57,603 total screens)|
|**Evaluated children**|897 toddlers aged 12-36 months|
|**Diagnosed with ASD**|403 children|
|**Gender breakdown**|Male: **331**, Female: **72** in ASD group|
|**Ethnicity**|41% Hispanic, 61% Caucasian, 16% Asian, 5% Black, 15% Mixed-race|
|**Socioeconomic diversity**|7% of screened toddlers were at or below the **federal poverty level**|

---

### **Tasks for Participants**

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|**CSBS Infant-Toddler Checklist**|Screen for communication and social delays|Parent-report questionnaire (paper/digital)|Pass/Fail status|
|**Pediatrician Referral Decision**|Determine if child should be further evaluated|Pediatrician's assessment|Referral status, reason for non-referral|
|**Expert ASD Evaluation**|Confirm ASD or other developmental delays|ADOS-2, Mullen Scales of Early Learning, Vineland Adaptive Behavior Scales|Diagnosis, developmental scores|
|**Treatment Referral & Engagement**|Monitor treatment initiation and duration|Referral to state-funded programs|Age at referral, therapy hours|

---

### **System Setup and Hardware**

|Device|Purpose|Specification|
|---|---|---|
|**iPads**|Digital screening tool|Automatic scoring of CSBS Checklist|
|**CSBS Paper Forms**|Alternative screening method|Manual scoring required|
|**Electronic Health Records**|Data tracking for screening and referrals|Multiple systems across clinics|
|**Autism Diagnostic Observation Schedule (ADOS-2)**|ASD diagnostic confirmation|Standardized clinical assessment|

---

### **Data Analysis**

|Feature|Description|Collected From|
|---|---|---|
|**Screening Pass/Fail Rate**|Determined if toddler met ASD risk criteria|CSBS Checklist|
|**Parent Concern**|Measured whether parents expressed concern|CSBS Checklist (final question)|
|**Referral Rate**|Percentage of screen-positive toddlers referred for evaluation|Pediatrician records|
|**Diagnosis**|Final classification (ASD, developmental delay, language delay, etc.)|ADOS-2, clinical judgment|
|**Age at Treatment Start**|How early intervention was initiated|State agency treatment records|

---

## 📊 Results & Key Findings

### **Key Findings**

- **Early Screening Works:** **59.4% of toddlers** were screened by **12 months**, allowing diagnosis as early as **15 months**.
- **Parental Concern is Crucial:** The probability of referral **doubled** if parents expressed concern.
- **Pediatrician Skepticism:** **51% of non-referrals** occurred because pediatricians doubted the screening result.
- **ASD Prevalence:** **1% of the screened population** was diagnosed with ASD.
- **Treatment Began Early:** Median age of treatment initiation was **21 months**, much earlier than the **national average of 4 years**.

---

### **Implications for the Project**

- The **success of digital screening tools** like the CSBS Checklist suggests **automated, AI-based screening approaches** could further enhance early ASD detection.
- The study highlights the **barriers posed by pediatrician hesitation**, emphasizing the **need for improved clinician training and AI-assisted decision-making**.
- The **integration of parent input** into screening tools is critical—future models should incorporate **parental concerns as weighted factors**.
- **Multi-modal diagnostic approaches**, including **eye-tracking or neurophysiological markers**, could **increase sensitivity** where parent-report screening fails.

---

## 🔍 Related Work

- The study builds on previous work showing that **early intervention improves cognitive and social outcomes** for children with ASD.
- The **CSBS Checklist** has been validated in prior research but has known **sensitivity limitations**, supporting the **need for additional screening layers** (e.g., behavioral AI tools).
- The findings align with work showing **pediatricians often delay referrals** due to **uncertainty about early symptoms**, reinforcing the importance of **clinician education and automated screening assistance**.

---

## 📝 Observations

### **Strengths of the Study**

- **Largest study to date** on real-world ASD screening across multiple pediatric clinics.
- **Demonstrates feasibility** of large-scale **digital screening tools** in real-world settings.
- **Empirical analysis** of **pediatrician decision-making** in ASD referral, shedding light on biases.
- **Strong demographic diversity**, including children from **low-income** and **ethnically diverse** backgrounds.

---

### **Major Concerns and Challenges**

1. **Pediatrician Hesitation Delays Diagnosis**
    
    - **Over 50% of failed screenings were not referred** due to pediatrician skepticism.
    - **Possible solution:** Introduce AI-powered clinical decision-support systems that **override pediatrician bias** when high-risk markers are detected.
2. **Screening Tool Sensitivity Issues**
    
    - **22% of toddlers with ASD** **initially passed the screen**, leading to delayed identification.
    - **Potential fix:** **Multi-modal screening**, integrating **behavioral AI, eye-tracking, and neurophysiological markers**.
3. **Parent Concern Drives Referral, But Some Parents May Not Express Concerns**
    
    - **Parents of younger children (12 months) were less likely to report concerns**, affecting referrals.
    - **Solution:** Enhance parent education and **integrate passive monitoring tools** (e.g., **home-based movement tracking**).
4. **No Long-Term Follow-Up on Treatment Outcomes**
    
    - While the study **tracked treatment engagement**, it **did not measure treatment efficacy** over multiple years.
    - **Future direction:** Implement **longitudinal tracking** to assess if **early detection leads to better functional outcomes**.

---

## Final Thoughts

This study underscores the **urgent need for enhanced ASD screening methods** and **multi-modal diagnostic tools**. While **digital screening** shows promise, reliance on **pediatrician judgment and parent concern** remains a **bottleneck**. The integration of **AI, behavioral analytics, and objective biomarkers** (e.g., **eye-tracking**) could revolutionize **early ASD detection** and **mitigate diagnostic delays**.

Would you like me to extract specific figures or expand on any section? 🚀