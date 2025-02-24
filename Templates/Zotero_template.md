---
title: {{ title }} 
authors: {{ authors }}
published: {{ date | format("YYYY") }} 
citekey: {{ citekey }}
journal: {{ publicationTitle }}
Paper_type: {{ itemType }}
DOI: https://www.doi.org/{{DOI}}
PdfZoteroLink: {{ desktopURI }} 
tags: 
cited_papers: 
citing_papers: 
other_connected_paper: 
read_on: {{ dateAdded | format("YYYY-MM-DD HH:mm") }}
code_repo: 
dataset: 
dg-publish: true
researchgroup: 
relatedApp:
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
> **dateAdded**:: {{dateAdded | format("YYYY-MM-DD HH:mm")}}

> [!LINK] 
> {{pdfZoteroLink}}

> [!Abstract]
> {%- if abstractNote %}
> {{abstractNote}}
> {%- endif -%}.
> 


## Notes

```dataview 
TABLE file.name 
FROM "NotesConnectToPapers" 
WHERE contains(file.name, this.citekey)
```



## Figures

{{formattedAnnotations}}