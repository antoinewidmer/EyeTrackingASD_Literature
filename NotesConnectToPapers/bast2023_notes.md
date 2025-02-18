---
citekey: bast2023
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

- The study investigates how sensory salience processing (SSP) influences gaze patterns on faces in individuals with ASD.
- Pupillary responses, as an index of locus coeruleus-norepinephrine (LC-NE) activity, were measured during the viewing of naturalistic video scenes.
- ASD participants showed attenuated gaze patterns toward human faces, influenced by SSP and moderated by LC-NE activity.
- Higher pupillary responses were observed for non-human scenes and lower responses for human scenes in ASD participants.
- SSP differences and pupillary response variations may underlie social attention differences in ASD.

## 🔬 Methods

### Study Design

- Case-control study using eye-tracking to investigate SSP and social attention differences in ASD.
- Naturalistic videos with human and non-human content were shown while tracking eye movements and pupillary responses.

### Participants

|Group|N|Gender (M/F)|Age Range|Mean Age (SD)|IQ Range|Mean IQ (SD)|Diagnosis|
|---|---|---|---|---|---|---|---|
|ASD|166|125/41|6-30|15.96 (5.59)|61-138|102.1 (17.91)|DSM-5 ASD diagnosis|
|Neurotypical|166|117/49|6-30|16.65 (6.03)|63-138|104.81(16.56)|No developmental conditions|

### Tasks for Participants

Participants watched naturalistic video clips with human and non-human scenes.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Human Scenes|Measure social attention|Videos with social content|Gaze patterns, pupil response|
|Non-Human Scenes|Measure sensory salience response|Videos without social content|Gaze patterns, pupil response|

### System Setup and Hardware

|Device|Purpose|Specifications|
|---|---|---|
|Tobii TX300|Eye tracking|300 Hz sampling rate|
|MATLAB TaskEngine|Video presentation|Stimuli synchronization|
|OpenCV Python Library|Salience map generation|Feature extraction for SSP|

### Data Analysis

|Feature|Task|Description|
|---|---|---|
|Pupillary Response|All tasks|Measures LC-NE activity via pupil dilation|
|Gaze Fixation Duration|Human scenes|Time spent fixating on faces|
|Salience Tracking|All tasks|Gaze patterns related to salience map features|
|Temporal Dynamics|All tasks|Changes in gaze patterns over video progression|

## 📊 Results & Key Findings

### Key Findings

- ASD participants displayed fewer fixations on human faces compared to neurotypical peers.
- Pupillary responses were higher during non-human scenes and lower during human scenes in ASD.
- SSP influenced gaze patterns across participants, with salience features drawing attention away from social content.
- Age and IQ differences were significant predictors of variations in gaze patterns.

### Implications

- SSP may serve as a neurobiological mechanism contributing to social attention differences in ASD.
- Pupillary responses could potentially serve as biomarkers for ASD diagnosis and intervention targeting social attention.
- Eye-tracking methods combined with salience maps offer an effective, non-invasive tool for understanding attention patterns in ASD.

## 🔍 Related Work

- Extends research on altered gaze behavior in ASD, supporting prior findings of diminished social attention.
- Aligns with studies suggesting heightened salience responses to non-social stimuli in ASD.
- Contributes new insights into the role of LC-NE activity in modulating sensory attention differences.

## 📝 Observations

### Strengths of the Study

- Large, well-matched participant sample.
- Application of dynamic, naturalistic video stimuli for ecological validity.
- Integration of multiple data streams (eye-tracking, salience maps, pupillometry) to provide a nuanced analysis.

### Major Concerns and Challenges

- Cross-sectional design prevents understanding of developmental trajectories.
- High variability in pupillary responses may limit reproducibility.
- Limited ability to control for the potential influence of task novelty.
- Focus on one sensory modality (visual) may overlook multisensory integration effects.
- Lack of consideration for potential gender-related differences in gaze behaviors.

The study highlights the importance of sensory salience processing in social attention differences observed in ASD and suggests pupillary responses as a potential biomarker for these differences.