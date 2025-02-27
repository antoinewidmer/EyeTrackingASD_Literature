---
citekey: kim2024
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

- The study explores the use of a **virtual reality (VR) system (WorkplaceVR) to enhance self-efficacy in individuals with autism** for workplace social interactions.
- WorkplaceVR simulates work-related social scenarios and provides users with **data-driven reflections on their behavioral and physiological responses**.
- A study was conducted with 14 young adults with autism to **evaluate the feasibility and effectiveness of WorkplaceVR**.
- The study found that WorkplaceVR **increased perceived self-efficacy** and **fostered self-awareness** regarding anxiety triggers in social situations.
- The VR system helped participants **recollect real-world experiences** and **develop anxiety management strategies**.

## 🔬 Methods

### Study Design

- A within-subject deployment study was conducted to examine the feasibility of WorkplaceVR.
- A mixed-methods approach was used, including pre- and post-system use assessments of participants’ self-efficacy perceptions and qualitative interviews.

### Participants

|Characteristic|Details|
|:--|:--|
|**Number of Participants**|14|
|**Gender**|12 men, 2 women|
|**Age Range**|16 to 34 years|
|**Condition**|Diagnosed with autism|
|**Other Criteria**|Could verbally articulate thoughts/feelings, no difficulties wearing HMD, understood study procedure|

### Tasks for participants

|Task|Purpose|Format|Data Collected|
|:--|:--|:--|:--|
|**VR Social Scenarios**|Practice social skills in a simulated café environment|Basic and advanced levels, interacting with customer avatars|Behavioral data (eye contact, voice volume), Physiological data (HR, EDA, temperature), Performance videos|
|**Data-Driven Reflection**|Review behavioral and physiological data to understand their performance and emotional responses|Visualization interface with graphs and video playback|Participants' reflections on their anxiety moments, voice volume, eye contact, and overall VR experience, Answers to reflective questions|

### System setup and hardware

|Device|Specificity|
|:--|:--|
|**VR Headset**|HTC VIVE Pro Eye VR headset|
|**Physiological Sensor**|Empatica E4 wristband|
|**PC Specifications**|Windows 10, Intel Core i7, GeForce RTX 2070 graphics card, 16 GB RAM|
|**VR Development Engine**|Unity3D|
|**SteamVR plug-in**|Valve Inc|

### Data Analysis

|Feature|Task|Description|
|:--|:--|:--|
|**Anxiety Moments**|VR Social Scenarios, Data-Driven Reflection|Time stamps of radical changes in sensor signals (HR, EDA, temperature, interbeat intervals, blood volume pulse)|
|**Voice Volume**|VR Social Scenarios, Data-Driven Reflection|Voice volume level during the VR experience|
|**Eye Contact**|VR Social Scenarios, Data-Driven Reflection|Whether the user gazes at the faces of the customer and manager avatars|
|**Perceived Self-Efficacy**|Pre- and Post-VR Experiment|Measured using the Perceived Self-Efficacy for VR Social Skill Training Scale (PSES-VR), an 8-item questionnaire with a 5-point Likert scale|
|**Sense of Presence**|Post-VR Experiment|Measured using the iGroup Presence Questionnaire (IPQ), a 14-item questionnaire with a 7-point Likert scale|
|**Qualitative Feedback**|Post-VR Experiment, Semi-structured Interviews|Participants' descriptions of their experiences, emotions, and insights gained during the VR scenarios and data reflection process, Thematic analysis was performed on the interview transcripts to identify key themes.|

Here is a summary table of how anxiety was measured in the study, based on the sources:

| Measurement Type                            | Method                                                                                                                                                                                                                                                      | Data Collected                                                                                                                                                                                                                      |
| :------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Physiological Data**                      | Empatica E4 wristband (E4 band) and head-mounted display (HMD) to collect data during VR intervention. Microsoft Azure machine learning algorithm defined anxiety moments using timestamps when sensors detected changes in users' physiological reactions. | Heart rate, electrodermal activity, temperature, interbeat intervals, and blood volume pulse.                                                                                                                                       |
| **Data Visualization Interface**            | Presented data for user interpretation along with performance videos.                                                                                                                                                                                       | Anxiety-related physiological measures, changes in voice volume, and detection of eye contact. Voice volume was graphed with timestamps. Eye contact was measured using regions of interest (ROIs) on customer and manager avatars. |
| **Perceived Self-Efficacy Scale (PSES-VR)** | 8-item questionnaire using a 5-point Likert scale. Modified from existing scales and based on Bandura's theory. Administered before and after VR experience.                                                                                                | Assessed beliefs regarding self-efficacy in practicing social skills at the workplace. Higher scores indicated better self-efficacy.                                                                                                |
| **iGroup Presence Questionnaire (IPQ)**     | 14-item questionnaire using a 7-point Likert scale.                                                                                                                                                                                                         | Investigated users' perceived sense of presence in the VR system. Measured general sense of being there, spatial presence, involvement, and experienced realism. Higher scores indicated a better sense of presence.                |

## 📊 Results & Key Findings

### Key Findings:

- **Significant increase in perceived self-efficacy** after using WorkplaceVR (P=.02).
- **Participants experienced more anxiety moments in advanced scenarios** compared to basic scenarios (P<.001).
- Data reflection fostered **increased self-awareness** among participants regarding anxiety triggers and behaviors.
- Participants were able to **recollect real-world experiences** and **articulate anxiety management strategies**.
- The VR system motivated participants to engage in **self-advocacy**.
- The data-driven reflection process helped participants **build positive self-beliefs**.
- Participants reported a **high level of presence** in WorkplaceVR due to realistic visuals and immersive scenarios.

### Implications:

- VR simulations enriched with physiological and behavioral sensing can be a **valuable tool for augmenting self-efficacy** in workplace social interactions for individuals with autism.
- Data reflection facilitated by physiological sensors can help participants with autism become **more self-aware of their emotions and behaviors**, **advocate for their characteristics**, and **develop positive self-beliefs**.
- The VR system can provide opportunities for individuals with autism to have a **mastery experience**, promote **self-awareness of their emotional states**, and support **self-advocacy** through data reflection.

## 🔍 Related Work

The study references prior research on:

- Anxiety and social challenges faced by individuals with autism in the workplace.
- The potential of VR interventions for promoting self-efficacy and social skills in people with autism.
- The importance of self-efficacy in approaching challenging workplace experiences.
- The use of inclusive design principles in developing VR programs for people with autism.

## 📝 Observations

### Strengths of the Study

- **Comprehensive VR system:** WorkplaceVR integrates realistic work scenarios, evidence-based social skills interventions, and multiple levels of difficulty.
- **Data-driven reflection:** The system provides users with visualizations of their behavioral and physiological data, promoting self-awareness and self-understanding.
- **Mixed-methods approach:** The study combines quantitative data (self-efficacy scores, presence questionnaires, sensor data) with qualitative data (interviews) to provide a comprehensive understanding of the VR system's impact.
- **User-centered design:** The VR program was developed using an inclusive and iterative design process, incorporating feedback from individuals with autism, managers, psychiatrists, and professional counselors.

### Major Concerns and Challenges

- **Limited generalizability:** The study only included participants with autism who are able to communicate and interact with others, which may limit the generalizability of the findings.
- **Algorithm for anxiety detection**: The algorithm used to estimate anxiety moments may not be entirely accurate.
- **Lack of validated measures:** The PSES-VR and IPQ measures had not been previously validated in the Korean population.
- **Translation to real-life situations:** The study could not confirm whether participants’ experiences in the study would translate to their real-life situations through post-study observations.
- **Need for diverse data:** Participants suggested that having more diverse data (e.g., facial expressions, body movements, and gestures) could help them better reflect on and understand their behaviors.
- **Data Accuracy**: Participants were informed that the data may not be accurate because of technical issues, so there can be errors or missing data in the interface.