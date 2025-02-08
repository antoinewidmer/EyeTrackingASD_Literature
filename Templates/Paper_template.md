---
title: {{title}}
authors: {{authors}}
published: {{date | format("YYYY")}}
citekey: {{citekey}}
journal: {{publicationTitle}}
Paper_type: {{itemType}}
DOI: https://www.doi.org/{{DOI}}
PdfZoteroLink : {{pdfZoteroLink}}
tags: {{allTags}}
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

## {{title}}

> [!Cite]
> {{bibliography}}


>[!md]
> **Year**:: {{date | format("YYYY")}}   
> **Citekey**:: {{citekey}} {%- if itemType %}  
> **itemType**:: {{itemType}}{%- endif %}{%- if itemType == "journalArticle" %}  
> **Journal**:: *{{publicationTitle}}* {%- endif %}{%- if volume %}  
> **Volume**:: {{volume}} {%- endif %}{%- if issue %}  
> **Issue**:: {{issue}} {%- endif %}{%- if itemType == "bookSection" %}  
> **Book**:: {{publicationTitle}} {%- endif %}{%- if publisher %}  
> **Publisher**:: {{publisher}} {%- endif %}{%- if place %}  
> **Location**:: {{place}} {%- endif %}{%- if pages %}   
> **Pages**:: {{pages}} {%- endif %}{%- if DOI %}  
> **DOI**:: {{DOI}} {%- endif %}{%- if ISBN %}  
> **ISBN**:: {{ISBN}} {%- endif %}    

> [!LINK] 
> {{pdfZoteroLink}}

> [!Abstract]
> {%- if abstractNote %}
> {{abstractNote}}
> {%- endif -%}.
> 

## 📌 Summary


## 🔬 Methods 

### Study Design

### Participants

### Tasks for participants

### System setup and hardware

### Data Analysis

## 📊 Results & Key Findings 


## 🔍 Related Work 



## 📝 Observations

### Strengths of the Study

### Major Concerns and Challenges