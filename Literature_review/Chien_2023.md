---
title: Game-Based Social Interaction Platform for Cognitive Assessment of Autism Using Eye Tracking
authors: 
published: 2023
journal: IEEE Transactions on Neural Systems and Rehabilitation Engineering, Vol. 31, 2023
Paper_type: Research
tags:
  - seriousGame
  - ASD
  - EyeTracking/Gaze
  - SocialInteraction
DOI: https://doi.org/10.1109/TNSRE.2022.3232369
category:
  main: 
  sub: 
device:
  Type: Tobii X2-30 Eye Tracker
  sampling_rate: 30
Participants:
  Total: 
  ASD_boys: 
  ASD_girls: 
  TD_boys: 
  TD_girls: 
cited_papers: 
citing_papers: 
other_connected_paper: 
read_on: 
code_repo: 
dataset:
---


## 📌 Summary


## 🔬 Methods 
### Participants
- **Total recruited:** **48 children**
    
    - **Typically Developing (TD) Children:** **30**
    - **Children with ASD:** **18**
- **Groups by age and cognitive ability:**
    
    - **Toddlers and children (4–7 years)**
        - **ASD:** 12 (after exclusions: 7)
        - **TD:** 18 (after exclusions: 17)
    - **Preadolescents and teenagers (11–13 years)**
        - **ASD:** 6
        - **TD:** 12
- **Exclusions:**
    
    - **5 ASD children** excluded due to **inattention or inability to complete eye-tracking calibration**.
    - **Eye-tracking data was excluded if completeness was below 70% or missing data exceeded 30%**.
- **Cognitive Assessments:**
    
    - **Wechsler Intelligence Scale for Children (WISC)** (for toddlers and children).
    - **Test of Nonverbal Intelligence, Fourth Edition (TONI-4)** (for teenagers).
    - **No significant IQ differences** between ASD and TD groups.

### Tasks for participants

#### Three Game Modules 

### System setup and hardware

#### Eye-Tracking Data Collection

- **Hardware:** **Tobii X2-30 Eye Tracker** (30 Hz sampling rate).
- **Software:** **Tobii Pro Studio** for calibration and analysis.
- **Calibration:** **Five-point calibration** for gaze detection.
- **Regions of Interest (ROIs):**
    - **Eyes, face, mouth, emotions, and social elements** were defined for each module.


### Data Analysis
The study utilized **statistical tests** to analyze **task performance and eye-tracking features** between **autistic (ASD) and typically developing (TD) children**. Below is a detailed breakdown of the analysis performed:

#### 1. Statistical Analysis of Task Performance

**Goal:** Compare **task accuracy and reaction times** between ASD and TD groups.

- **Statistical Tests Used:**
    
    - **Independent Samples t-test** (for normally distributed data)
    - **Mann-Whitney U test** (for non-normally distributed data)
- **Key Findings:**
    
    - **Gaze Following Task:** No significant difference in accuracy.
    - **Emotion Recognition Task:**
        - **ASD children had lower accuracy for happy emotions (p = 0.047).**
    - **Social Interaction Task:**
        - No significant difference in accuracy, but **ASD children had longer reaction times**.

#### 2. Eye-Tracking Data Analysis

**Goal:** Identify differences in gaze patterns between ASD and TD children.

##### Eye-Tracking Features Extracted:

1. **Total Fixation Duration (TFD):** Total time fixating on a target.
2. **Saccade Duration (SD):** Time taken to shift gaze between elements.
3. **Time to First Fixation (TTFF):** Time before first looking at a target.
4. **First Fixation Duration (FFD):** Time spent during the first gaze on an object.
5. **Average Fixation Time (AFT).**
6. **Average Saccade Time (AST).**

---

##### (A) Fixation Duration Analysis

- **Statistical Test Used:**
    
    - **Mann-Whitney U test** (since fixation duration data was not normally distributed).
- **Key Findings:**
    
    - **Fixation on Positive Emotions:**
        - ASD children **spent significantly less time looking at happy faces** than TD children (**p = 0.047**).
    - **Fixation on Social Captions:**
        - ASD children **fixated significantly longer on text-based social captions** than TD children (**p = 0.018**).
    - **Fixation on Multiple Targets:**
        - ASD children **spent less time on multiple social targets** than TD children (**p = 0.042**).

##### (B) Saccade Duration Analysis

- **Statistical Test Used:**
    
    - **Wilcoxon Signed-Rank Test** (since saccade durations were skewed).
- **Key Findings:**
    
    - ASD children **had significantly longer saccade durations when reading social cues** compared to TD children (**p = 0.018**).
    - ASD children **took longer to shift gaze between elements**, indicating **delayed visual attention shifting**.

##### (C) Correlation Analysis

**Goal:** Identify relationships between eye-tracking features and cognitive assessments (IQ, working memory).

- **Statistical Test Used:**
    
    - **Pearson Correlation Coefficient (for normally distributed data)**.
- **Key Findings:**
    
    - **Positive correlation between fixation duration on happy faces and IQ scores in TD children.**
    - **Negative correlation between saccade duration and working memory in ASD children.**

---

### Outlier Handling and Data Validation

- **Normality Testing:**
    - **Shapiro-Wilk Test** was used to check if data was normally distributed.
    - **Results:**
        - Some eye-tracking features were **not normally distributed**, requiring the use of **non-parametric tests** (Mann-Whitney U, Wilcoxon Signed-Rank Test).
- **Variance Homogeneity Testing:**
    - **Levene’s Test** was performed before applying t-tests.
- **Data Exclusions:**
    - **Participants with missing gaze data >30% were excluded.**
    - **Reaction times exceeding 3 standard deviations were removed.**

---

### Final Summary of Statistical Tests Used

|**Test**|**Purpose**|**Application in Study**|
|---|---|---|
|**Independent Samples t-Test**|Compare means between ASD and TD groups|Task accuracy and reaction times|
|**Mann-Whitney U Test**|Compare non-normal distributions|Fixation durations, saccades|
|**Wilcoxon Signed-Rank Test**|Compare paired data|Social interaction fixation data|
|**Pearson Correlation**|Assess relationships|Eye-tracking features vs. cognitive scores|
|**Shapiro-Wilk Test**|Check normality|Task performance and gaze features|
|**Levene’s Test**|Check variance homogeneity|Ensured valid t-test results|



## 📊 Results & Key Findings 


1. **ASD children exhibit atypical eye-tracking behaviors**:
    
    - **Reduced fixation on positive emotions** (p = 0.047).
    - **Longer saccade durations when reading social cues** (p = 0.018).
    - **More fixation on text-based social captions** (p = 0.018).
2. **Statistical tests confirmed significant differences** in gaze behavior between ASD and TD children.
    
3. **Correlation analysis showed eye-tracking features can predict cognitive ability**, supporting eye-tracking as a diagnostic tool.


- ## 🔍 Related Work 



- ## 📝 Notes for Review 
