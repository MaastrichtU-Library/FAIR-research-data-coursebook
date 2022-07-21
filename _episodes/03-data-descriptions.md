---
title: "Data Descriptions"
teaching: 10
exercises: 15
questions:
- "What are data descriptions?"
- "What is the relation between data description and codebook"
objectives:
- "First"
- "Second"
keypoints:
- "First key point."
---

### What are Data Descriptions?

Data descriptions are a detailed explanation and documentation of each data attribute or variable in a dataset. Depending on the use case and field of research these data desriptions are also known as:  
- Codebooks (e.g. in Statistics or Social Sciences)
- Data Dictionaries (e.g. in Computer and Data Science)
- Labels or Data Tags (e.g. in Crowdsorucing or Humanities)
- Data Glossary (e.g. in Business Administration & Finance)
- Metadata (wrong use of this term in this context)

For example:  

|Variable Name | Description|
|---|---|
|Weight | Weight of the patient in kilograms|
|Height | Height of the patient in centimeters|
|Age | Age of the patient in years|
|Blood Glucose Level |Blood glucose level of the patient in mg/dl|

> ## "Data Descriptions" has synonims depending on the field
>
> **No matter what terminology you use, "Data Descriptions" always referes to detailed explanation and documentation of each data attribute or variable in a dataset.**
{: .callout}

### How to reuse Data Descriptions?

Documentation taes time, however we shall always aim for reusing existing data descriptions that are generally accepted in the community. i.e. the variable `Weight` is a concept that has been widely used in research therefore we don't need to redifine it every time.

For example, in [BioPortal](https://bioportal.bioontology.org/) we can find already existing descriptions of `Weight`, these descriptions belongs to a community accepted online diccionary (Ontology). Moreover it provides a globally unique identifier to the description.  

IMAGE 1  
IMAGE 2  

> ## Describe your data by reusing ontology terms  
>
> **By resuing Ontology terms or community accepted vocabularies we aim to create a culture of recycling by default.**  
> **Advantages**
> > - We don't have to redefine the terms every time
> > - We get a permanent link to the resource
> > - Since it uses a global identifier becomes easier for others to integrate with different data sources
> **Disadvantages**
> > - Sometimes you might not find an Ontology or vocabularies that fits your variable.
{: .callout}

### Are there standard Ontologies for Data Descriptions?

- EU voc https://op.europa.eu/en/web/eu-vocabularies 
- General https://schema.org/
- Wiki https://www.wikidata.org/wiki/Wikidata:Main_Page
- Data https://www.w3.org/TR/vocab-dcat-2/
- Metadata https://www.dublincore.org/
- Dbpedia https://www.dbpedia.org/ so here https://dbpedia.org/page/United_States#
- Bioportal

----

> ## Exercise - Level Easy 🌶
>
> 1. Visit [BioPortal](https://bioportal.bioontology.org/). BioPortal is the most knwon repository for biomedical ontologies
> 2. Search for an Ontology term for `blood glucose level` In the "Search for a class" search box.
> 3. Select one result related to clinical measurement that is sound to you. 
> 4. What is the definition and ID?
> 
> {: .source}
>
> > ## Solution
> >
> > Definition: Measurement of the amount of glucose, the monosaccharide sugar, C6H12O6, occurring widely in plant and animal tissues which is one of the three dietary monosaccharides that are absorbed directly into the bloodstream during digestion, is the end product of carbohydrate metabolism, and is the chief source of energy for living organisms, in a specified volume of blood, the fluid that circulates through the heart, arteries, capillaries and veins carrying nutrients and oxygen to the body tissues and metabolites away from them.
> > ID: [http://purl.obolibrary.org/obo/CMO_0000046](http://purl.obolibrary.org/obo/CMO_0000046)
> > {: .output}
> {: .solution}
{: .challenge}

### What format should it be?

The **Data Descriptions** are normally written on a tabular format, this document has the lenght and depth that the data owner sees fit. The general rule of thumb is to describe the dataset that is related to a publication. Any accsible format like `.csv`, `.xls` or similar is acceptable.  
In case is a databse a data model must be included in machine readible format (e.g `.sql`) and a human friendly diagram (e.g. ER model on `.pdf`)

There are examples where data descriptions are made available in a fuman-relatable maner such as the *dataset nutrition labels* style [(Holland et al., 2018)](https://arxiv.org/abs/1805.03677).

An example is **A Statutory Article Retrieval Dataset**   → [LINK TO EXAMPLE](https://github.com/maastrichtlawtech/bsard/blob/master/docs/img/nutrition.png) 


### (ADVANCE) What format should it be?

- Optional:  CONVERTION TO LINKED DATA FORMAT
	- Using the LDWizard https://github.com/MaastrichtU-IDS/ldwizard-humanities or https://humanities.wizard.semanticscience.org/  orhttps://ldwizard.netwerkdigitaalerfgoed.nl/#1
	- Annotate the columns and publish to Triply DB https://triplydb.com/hdezserrano/-/settings/tokens
	- OR DOWNLOAD AND SAVE IN DATA FOLDER (IN CASE YOU DONT HAVE TRIPLYDB ACCOUNT) 
	- Optional: UPLOAD to LOD https://lod-cloud.net/#


	- In case it's an RDF file (meaning that you created your Ontolgy) then register it in an Ontlogy registry https://fairsharing.org/search?fairsharingRegistry=Standard or http://bioportal.bioontology.org/