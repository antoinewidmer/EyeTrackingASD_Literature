---
title: Early detection of autism using digital behavioral phenotyping
authors: Sam Perochon, J. Matias Di Martino, Kimberly L. H. Carpenter, Scott Compton, Naomi Davis, Brian Eichner, Steven Espinosa, Lauren Franz, Pradeep Raj Krishnappa Babu, Guillermo Sapiro, Geraldine Dawson
published: 2023
citekey: perochon2023a
journal: Nature Medicine
Paper_type: journalArticle
DOI: https://www.doi.org/10.1038/s41591-023-02574-3
PdfZoteroLink : zotero://select/library/items/2TRL46FN
tags: Machine learning, Disability
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
cited_papers:
citing_papers: 
other_connected_paper: 
read_on: 
code_repo: 
dataset:
---

## Early detection of autism using digital behavioral phenotyping

> [!Cite]
> Perochon, S., Di Martino, J. M., Carpenter, K. L. H., Compton, S., Davis, N., Eichner, B., Espinosa, S., Franz, L., Krishnappa Babu, P. R., Sapiro, G., & Dawson, G. (2023). Early detection of autism using digital behavioral phenotyping. _Nature Medicine_, _29_(10), 2489–2497. [https://doi.org/10.1038/s41591-023-02574-3](https://doi.org/10.1038/s41591-023-02574-3)


>[!md]
> **Year**:: 2023   
> **Citekey**:: perochon2023a  
> **itemType**:: journalArticle  
> **Journal**:: *Nature Medicine*  
> **Volume**:: 29  
> **Issue**:: 10   
> **Pages**:: 2489-2497  
> **DOI**:: 10.1038/s41591-023-02574-3    

> [!LINK] 
> [2023_Perochon et al._Early detection of autism using digital behavioral phenotyping.pdf](zotero://select/library/items/2TRL46FN)

> [!Abstract]
>
> Early detection of autism, a neurodevelopmental condition associated with challenges in social communication, ensures timely access to intervention. Autism screening questionnaires have been shown to have lower accuracy when used in real-world settings, such as primary care, as compared to research studies, particularly for children of color and girls. Here we report findings from a multiclinic, prospective study assessing the accuracy of an autism screening digital application (app) administered during a pediatric well-child visit to 475 (17–36 months old) children (269 boys and 206 girls), of which 49 were diagnosed with autism and 98 were diagnosed with developmental delay without autism. The app displayed stimuli that elicited behavioral signs of autism, quantified using computer vision and machine learning. An algorithm combining multiple digital phenotypes showed high diagnostic accuracy with the area under the receiver operating characteristic curve = 0.90, sensitivity = 87.8%, specificity = 80.8%, negative predictive value = 97.8% and positive predictive value = 40.6%. The algorithm had similar sensitivity performance across subgroups as defined by sex, race and ethnicity. These results demonstrate the potential for digital phenotyping to provide an objective, scalable approach to autism screening in real-world settings. Moreover, combining results from digital phenotyping and caregiver questionnaires may increase autism screening accuracy and help reduce disparities in access to diagnosis and intervention.
>.
> 

## 📌 Summary

This study evaluates the effectiveness of **SenseToKnow**, a **digital behavioral phenotyping app**, for early autism detection in toddlers aged **17–36 months**. Conducted in **pediatric primary care settings**, the study assessed 475 children using **machine learning (ML) and computer vision analysis (CVA)** to quantify behavioral responses to social and non-social stimuli. The app demonstrated **high diagnostic accuracy**, with **AUC = 0.90, sensitivity = 87.8%, specificity = 80.8%**, and **negative predictive value (NPV) = 97.8%**. Importantly, **performance remained stable across sex, race, and ethnicity**, supporting **objective, scalable, and equitable autism screening**.

---

## 🔬 Methods

### **Study Design**

- **Type**: **Multiclinic, prospective study**.
- **Setting**: **Four Duke University pediatric clinics** during routine **well-child visits**.
- **Goal**: Assess **SenseToKnow's diagnostic accuracy** vs. traditional screening tools (M-CHAT-R/F).
- **Algorithm**: **XGBoost ML model** trained on 23 digital phenotypes extracted from **gaze tracking, facial expressions, head movements, and motor behaviors**.

---

### **Participants**

- **Total sample**: **475 toddlers (17–36 months old)**.
- **Subgroups**:
    - **Autism**: 49 children.
    - **Developmental Delay (DD-LD)**: 98 children.
    - **Typically Developing (TD)**: 328 children.
- **Demographics**:
    - **Sex**: 269 boys (56.6%), 206 girls (43.4%).
    - **Ethnicity**: 10.5% Hispanic/Latino, 89.5% Non-Hispanic/Latino.
    - **Race**: 70.4% White, 15.3% Black, 8.2% Multiracial, others <6%.
- **Inclusion Criteria**:
    - Age **16–38 months**.
    - No **sensory or motor impairments**.
    - Parent speaks **English or Spanish**.
- **Exclusion Criteria**:
    - Illness or distress preventing participation.

---

### **Tasks for Participants**

1. **App-based Digital Phenotyping**:
    - Toddlers watched **social and non-social videos** on a tablet.
    - Facial and behavioral responses were **automatically recorded**.
    - The app **called the child’s name** three times.
    - Toddlers played a **bubble-popping game** to assess motor skills.
2. **Traditional Autism Screening**:
    - Parents completed the **M-CHAT-R/F**.
    - Children flagged for autism underwent **ADOS-2 & DSM-5-based evaluation**.

---

### **System Setup and Hardware**

|**Component**|**Description**|
|---|---|
|**Tablet Device**|iPad (60 cm distance from child)|
|**Camera**|Embedded **frontal camera (1280x720, 30fps)**|
|**Stimuli**|Short **social vs. non-social videos**|
|**Gaze Tracking**|**Computer vision** detects eye movements|
|**Head Movements**|Captured via **facial landmarks analysis**|
|**Motor Skills**|Measured through **touch-based game interaction**|

---

### **Data Analysis**

- **Primary Outcome**: Accuracy of the **ML-based autism classifier** vs. **traditional screening tools**.
- **Algorithm Used**: **XGBoost model** trained on **23 digital behavioral phenotypes**.
- **Cross-Validation**: **Fivefold nested cross-validation** with **1000 trees per model**.
- **Performance Metrics**: **AUC, Sensitivity, Specificity, PPV, NPV**.
- **Model Interpretability**: **SHAP analysis** to determine key predictors.

#### Digital Behavioral Data (Collected via SenseToKnow App)

The app recorded **23 behavioral phenotypes** using **computer vision (CVA) and machine learning (ML)**.

##### 👀 Social & Gaze Behavior

|**Feature**|**Description**|
|---|---|
|**Facing Forward Time**|Percentage of time child faced the screen during videos (proxy for attention).|
|**Gaze Percent Social**|Proportion of time spent looking at social stimuli (vs. non-social).|
|**Gaze Silhouette Score**|Measures clustering of gaze patterns (focused vs. dispersed viewing).|
|**Attention to Speech**|Synchronization between gaze and alternating speakers in a conversation.|

##### 🙂 Facial Expression & Movement

|**Feature**|**Description**|
|---|---|
|**Eyebrows Complexity**|Variability of eyebrow movements during social and non-social videos.|
|**Mouth Complexity**|Variability in mouth movements (indicative of affective engagement).|

##### 🤖 Head Movement Patterns

|**Feature**|**Description**|
|---|---|
|**Head Movement Rate**|Frequency of head movements during social and non-social stimuli.|
|**Head Movement Complexity**|Variability and predictability of head movements.|
|**Head Movement Acceleration**|Speed of head movement changes over time.|

##### 📣 Response to Name

|**Feature**|**Description**|
|---|---|
|**Response to Name Proportion**|Number of times child turned their head when name was called (out of 3 attempts).|
|**Response to Name Delay**|Average delay (seconds) between name call and head turn.|

##### 👁️ Blink Rate

|**Feature**|**Description**|
|---|---|
|**Blink Rate (Social & Non-Social Videos)**|Frequency of blinking (indicator of attentional engagement).|

##### 🖐️ Touch-Based Motor Skills

|**Feature**|**Description**|
|---|---|
|**Touch Popping Rate**|Ratio of bubbles popped during interactive game.|
|**Touch Error (s.d.)**|Variation in touch precision (distance from bubble center).|
|**Touch Average Length**|Average finger trajectory length on the screen.|
|**Touch Average Applied Force**|Estimated force applied during touch interactions.|

---

#### Clinical & Demographic Data (Collected via Parent Reports & Clinician Evaluations)

|**Category**|**Details**|
|---|---|
|**Demographics**|Age, sex, race, ethnicity, parental education level.|
|**M-CHAT-R/F Score**|Parent-completed autism screening questionnaire.|
|**ADOS-2 Score**|Expert clinical autism assessment (DSM-5 criteria).|
|**Mullen Scales**|Cognitive and language development scores.|
|**Electronic Health Records (EHR)**|Longitudinal follow-up of autism or developmental delay diagnoses.|

---

## 📊 Results & Key Findings

### **1. Diagnostic Performance of SenseToKnow**

|**Metric**|**Autism vs. Neurotypical**|**Autism vs. All Others (DD-LD + NT)**|
|---|---|---|
|**AUC**|**0.90**|**0.86**|
|**Sensitivity**|**87.8%**|**81.6%**|
|**Specificity**|**80.8%**|**80.5%**|
|**Negative Predictive Value (NPV)**|**97.8%**|**97.4%**|
|**Positive Predictive Value (PPV)**|**40.6%**|**32.5%**|

- **Higher accuracy** than traditional **M-CHAT-R/F screening (PPV = 14.6%)**.
- **Combining SenseToKnow + M-CHAT-R/F increased accuracy (AUC = 0.97, PPV = 63.4%)**.

---

### **2. Performance Across Subgroups**

|**Subgroup**|**AUC (%)**|**Sensitivity**|**Specificity**|
|---|---|---|---|
|**Boys**|**89.6**|86.8%|77.8%|
|**Girls**|**89.1**|90.9%|83.5%|
|**White**|**86.9**|82.6%|82.7%|
|**Black**|**81.2**|90.9%|53.6%|
|**Hispanic/Latino**|**95.3**|92.3%|90.9%|

- **Consistent accuracy across sex, race, and ethnicity**.
- **Lower specificity in Black children (53.6%)** suggests the need for further validation.

---

### **3. Key Predictive Features**

|**Top Features**|**Mean SHAP Value Contribution (%)**|
|---|---|
|**Facing forward during social movies**|**11.2%**|
|**Gaze to social stimuli**|**11.1%**|
|**Response to name delay**|**7.1%**|
|**Facial expressions complexity**|**6.0%**|
|**Head movement patterns**|**4.9%**|

- **Social attention and response to name were the strongest autism predictors**.
- **Motor and facial expression features also contributed significantly**.

---

## 🔍 Related Work

- **Traditional autism screening tools** (e.g., **M-CHAT-R/F**) have **low sensitivity in real-world settings**.
- **Eye-tracking studies** have shown high specificity (**98%**) but low sensitivity (**17%**).
- **Digital phenotyping approaches** (e.g., AI-based gaze tracking) have **improved classification accuracy**.
- **Machine learning models** have been increasingly used to **automate and enhance behavioral assessments**.

---

## 📝 Observations

### **Strengths of the Study**

✅ **High diagnostic accuracy (AUC = 0.90, Sensitivity = 87.8%)**.  
✅ **Objective, automated, and scalable**—reduces **clinician burden**.  
✅ **Equitable screening**—performs well across **sex, race, and ethnicity**.  
✅ **Multi-feature analysis (gaze, head movements, motor skills)**—captures autism heterogeneity.  
✅ **Improved performance when combined with M-CHAT-R/F**.

---

### **Major Concerns and Challenges**

⚠️ **Lower specificity in Black children (53.6%)**—needs further validation in **diverse populations**.  
⚠️ **Parental bias**—voluntary participation may have **over-representation of children with suspected autism**.  
⚠️ **Limited generalization**—app was tested in **clinical settings**; real-world home use remains **untested**.  
⚠️ **Exclusion of children with sensory/motor impairments**—reduces applicability in **all neurodiverse groups**.