---
title: "Data Terms of Use"
teaching: 10
exercises: 15
questions:
- "What are data terms of use?"
- "What must they contain?"
- "What format should they be?"
objectives:
- "The participant will understand what data terms of use are with examples"
- "The participant will be able to create a basic data terms of use text"
keypoints:
- "A License is the bare minimum requirement for 'Data Terms of Use."
- "The 'Data Terms of Use' text is the legal basis of the refered data source"
- "The data creator must create always a Terms of Use text along."
---

> ## FAIR principles used in Data Terms of Use:  
> **Accessible**   
> > FM-A2 (Metadata Longevity) → [doi.org/10.25504/FAIRsharing.A2W4nz](https://doi.org/10.25504/FAIRsharing.A2W4nz)  
>
> **Reusable**  
> > FM-R1.1  (Accessible Usage License) → [doi.org/10.25504/FAIRsharing.fsB7NK](https://doi.org/10.25504/FAIRsharing.fsB7NK)  
>
{: .checklist}

### What are Data Terms of Use?

Data Terms of Use is a text that referers to the terms, conditions, actions, legal considerations or licenced content when particlar digital object(s) is used (e.g. reusing datasets).  

An example is **The World Bank - Terms of Use for Datasets**   → [LINK TO EXAMPLE](https://www.worldbank.org/en/about/legal/terms-of-use-for-datasets)  


<img title="terms" src="https://www.worldbank.org/content/dam/wbr/logo/logo-wb-header-en.svg">

We can identify general elements that are present in the **Data Terms of Use** for example a general description of the document mentioning the data in is refered to, but also under what type f license the user is allowed to. 

### What must contain?

As a general rule a good **Data Terms of Use** document must contan at least the following:

  - Description
  - License
  - Work attribution
  - Disclaimer

Nevertheless, depending on the use case the "Data Terms of Use" text can be extended to different speific sections when involves more complex information, intrgration of databases or personal data is invlved. After all the "Data Terms of Use" text is the legal basis of the refered Digital Object (e.g. dataset). i.e. on the light of public law, you can make someone liable for not compling to specific clauses. 

Nevertheless, when working in scientific projects we normally are participating within a greater scope in a scitific project or study. It is always recommended to check with the Principal Invistigaorr or Porject Managers wheter if **Data Terms of Use** are to be defined since, possibly there is already a **Data Policy** framework.

An example is **Policy for use and oversight of samples and data arising from the Biomedical Resource of the 1958 Birth Cohort (National Child Development Study)**   → [LINK TO EXAMPLE](https://fairsharing.org/FAIRsharing.z09fg9)  
Link to the original [Data Policy](https://cpb-eu-w2.wpmucdn.com/blogs.bristol.ac.uk/dist/7/314/files/2015/07/POLICY-DOCUMENT-FINAL-Vsn-4.0-DEC-2014.pdf)

> ## "Data Terms of Use" text is the legal basis of the refered data source
>
> **on the light of public law, you can make someone liable for not compling to specific clauses.**
{: .callout}

Some more specific sections are:

### What format should they be?

The **Data Terms of Use** is a plain document, this document has the lenght and depth that the data owner sees fit, there is no right or wrings when drafting it. Normally is recommended to store this document in a `README` file, using an accessible format for example `.txt`, `.md` or `.html` so that any user can read it withouth needing any additional software.

Any text editor software would do the trick, such as [Notepad++](https://notepad-plus-plus.org/) or [Sublime](https://www.sublimetext.com/) but also you can write it using Microsoft Word or Google Docs and save it as `.txt` 

> ## Exercise - Level Medium 🌶🌶
>
> 1. Visit the landing page of following terms of use [github.com/CityOfPhiladelphia/terms-of-use/blob/master/LICENSE.md](https://github.com/CityOfPhiladelphia/terms-of-use/blob/master/LICENSE.md) 
>
> 2. Can you tell what type of data is about?
> 
> 3. Can you tell on what format the terms of use are written?
> {: .source}
>
> > ## Solution
> >
> > - Refers to the public code on which rge city of Philadelfia government is based on (https://www.phila.gov/)
> > - The format is Markdown (`.md`)
> > {: .output}
> {: .solution}
{: .challenge}

> ## Data Terms of Use it's "just" a plain document
>
> **The "Data Terms of Use" can be drafted using any application (e.g. MS Word), howeveri it's important to store it on an accessible format (e.g. `.txt`)**
{: .callout}

### Where to put the Data Terms of Use?

The **Data Terms of Use** needs to be in the same root folder than the data source. In case regards to a database - like the World Bank example - it should be in the prject's website. Moreover, if there no official project website you should in clude it on `.md` format in a Github repository like the fllowing example: → [LINK TO EXAMPLE](https://github.com/MaastrichtU-IDS/clean-technologies-nlp/blob/master/data/README.md)  


### Are there standard Licenses?

Yes  
- [Creative Commons (CC)](https://creativecommons.org/about/cclicenses/)  
- [Open Data Commons (ODC)](https://opendatacommons.org/licenses/index.html)  
 
 CC provides a number of licenses that can be used with a wide variety of creations that might otherwise fall under copyright restrictions, including music, art, books and photographs. Although not tailored for data, CC licenses can be used as data licenses because they are easy to understand. Its website includes a summary page [HERE](https://creativecommons.org/about/cclicenses/) outlining all the available licenses, explained with simple visual symbols.

|Permission Mark|What can I do with the data?|
|---|---|
|BY|Creator must be credited|
|SA|Derivatives or redistributions must have identical license|
|NC|Only non-commercial uses are allowed|
|ND|No derivatives are allowed|

ODC provides three licenses that can be applied specifically to data. The webpages of each of these licenses include human-readable summaries, with the ramifications of the legalese explained in a concise format.

Example https://www.numbeo.com/common/terms_of_use.jsp

----


> ## Exercise - Level Easy 🌶
>
> Is it possible to edit the Terms of Use in DataverseNL?
>
> **HINT:** Go to [dataverse.nl/](https://dataverse.nl/) to the FAQ section.
> {: .source}
>
> > ## Solution
> >
> > Yes, it is possible, however you can't choose it at the begining. Only after creating a dataset you go to the ‘Terms’ tab on your dataset page and click ‘Edit Terms requirements’. Select the radio button ‘No, do not apply CC0 public domain dedication’, and fill in the text fields with your own terms and conditions.
> >
> > {: .output}
> {: .solution}
{: .challenge}


Choose a licemse
https://creativecommons.org/share-your-work/

Write a disclaimer

Discussion
What to do with KIDS DATA

## More:

- Layout in Markdown (`.md): https://gist.github.com/pedrohserrano/c439f790b54df4bf738964446bd52500
- Dataverse DUA https://dataverse.org/best-practices/sample-dua

- Output:
	- In case it's a document (README) then get the link
	- In case it's a tailored policy project then register to a registry https://fairsharing.org/


> ## Discussion  
> Kids data   
>
{: .discussion}