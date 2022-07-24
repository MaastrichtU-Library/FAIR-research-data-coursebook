---
title: "Data Archiving"
teaching: 10
exercises: 15
questions:
- "1 What is Data Archiving?"
- "2 What are Data Repositories?"
- "3 What is a DOI, and why is it important?"
objectives:
- "The participant will understand the importance of archiving datasets on trusted data repositories."
- "The participant will learn the significance of the Digital Object Identifier (DOI)."
keypoints:
- "**Data repositories** can make a research data more discoverable by machines (e.g. Google search engine)."
- "Always aim for a repository that fits your community (e.g. DataverseNL). Else, deposit your dataset on generic repositories (e.g. Zenodo)."
- "If the data is about human subjects or includes demographics, you can always choose to make it private or deposit an aggregated subset."
---


> ## FAIR principles used in Data Archiving  
> **Findable**   
> > FM-F1A (Identifier Uniqueness) → [doi.org/10.25504/FAIRsharing.r49beq](https://doi.org/10.25504/FAIRsharing.r49beq)  
> > FM-F3 (Resource Identifier in Metadata) → [doi.org/10.25504/FAIRsharing.o8TYnW](https://doi.org/10.25504/FAIRsharing.o8TYnW)  
>
> **Accessible**  
> > FM-A2 (Metadata Longevity) → [doi.org/10.25504/FAIRsharing.A2W4nz](https://doi.org/10.25504/FAIRsharing.A2W4nz)  
>
{: .checklist}


### 1. What is Data Archiving?

"Data Archiving" is the long-term storage of research data, including all research disciplines. The various academic journals have different policies regarding how much of their data and methods researchers are required to store in a public archive. Similarly, the major grant-giving institutions have varying attitudes toward public archival of data. In general, publications must have attached sufficient information to allow fellow researchers to replicate and test the research.

> ##  "Data Archiving" is the long-term storage of research data
>
{: .callout}

### 2. What are Data Repositories?

Datasets are archived in **Data repositories**. They are storage locations for digital objects. **Data repositories** can help make a researcher's data more discoverable by search engines (e.g. Google) and ultimately lead to potential reuse. Therefore, using storage can lead to increased citations of your work. Data repositories can also serve as backups during rare events where data are lost to the researcher and must be retrieved.

 > ## **Data repositories** can help make a researcher's data more discoverable by search engines (e.g. Google) 
>
{: .callout}

Examples of data repositories  

| Data Repository | About |
|---|---|
|[DataverseNL](https://dataverse.nl/dataverse) <img src="https://dataverse.nl/assets/logos/DataverseNL-logo.png" alt="dataverse" style="width:30x;height:15x;"> | DataverseNL is a community-specific repository it focuses on Dutch universities and research centers|
|[4TU Data](https://data.4tu.nl/) <img src="https://data.4tu.nl/fileadmin/Tmpl/Images/4TU-logo.png" alt="4tu" style="width:30x;height:15x;"> | 4TU Data is a community repository which was originally created by three technical universities in the Netherlands|
|[PANGEA](https://pangaea.de/) <img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/04-1.png" alt="pangea" style="width:30x;height:15x;"> | PANGEA is a community-specific repository that focuses on Earth & Environmental Science| 
|[FigShare](https://figshare.com/) <img src="https://websitev3-p-eu.figstatic.com/assets-v3/2fa5d16c00fb00c8f5413b230e05e1c55e745c36/static/media/defaultLogo.30adffde.png" alt="figshare" style="width:30x;height:15x;"> | FigShare is an open generic data repository for general purposes, it can store data and other digital objects| 

Just like FigShare, many data repositories are for general use. They provide a low entry barrier to making data **Findable** addressing FM-F1A (Identifier Uniqueness) and FM-F3 (Resource Identifier in Metadata). 

> ## Default recommendations for data repositories
> [ZENODO](https://zenodo.org/) administrated by [CERN](https://home.cern/)  
> [SURF Repository](https://repository.surfsara.nl/) administrated by [SURF](https://www.surf.nl/)  
> [DataverseNL](https://dataverse.nl/)  administrated by [DANS](https://dans.knaw.nl/en/)
{: .callout}

Quick characteristics of general purpose repositories:  

- Safe — your research is stored safely for the future in a Data Centre for as long as CERN and/or DANS exist.
- Citeable — every upload is assigned a Digital Object Identifier (DOI) to make them citable and trackable.
- No waiting time — Uploads are made available online as soon as you hit publish, and your DOI is registered within seconds.
- Open or closed — Share, e.g. anonymised clinical trial data with only medical professionals via our restricted access mode.
- Versioning — Easily update your dataset with our versioning feature.
- GitHub integration — Easily preserve your GitHub repository in Zenodo.
- Usage statistics — All uploads display standards-compliant usage statistics.


<img src="https://datamanagement.hms.harvard.edu/sites/g/files/mcu941/files/assets/Images/2020-12-10-Repo-Matrix.png" alt="hardvard">
*Image: Harvard Medical School, RDM - Data Repositories. Accessed Jul-2022 - *datamanagement.hms.harvard.edu/share/data-repositories*


#### [Original Hardvard Dataverse](https://dataverse.harvard.edu/dataverse/harvard)


<iframe width="560" height="315" src="https://www.youtube.com/embed/MPQ0Tpgaxt0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> ## There are also public registries where you can find trusted repositories for Data Archiving 
> **Registry of Research Data Repositories (re3data)**  → [re3data.org//](https://www.re3data.org/)  
> **PLOS ONE Recommended Repositories**  → [journals.plos.org/plosone/s/recommended-repositories](https://journals.plos.org/plosone/s/recommended-repositories)  
> **NIH Recommended Repositories:**  → [sharing.nih.gov/repositories-for-sharing-scientific-data](https://sharing.nih.gov/data-management-and-sharing-policy/sharing-scientific-data/repositories-for-sharing-scientific-data)  
> **Nature - Scientific Data Guidelines:**  → [nature-com.mu.idm.oclc.org/sdata/policies/repositories](https://www-nature-com.mu.idm.oclc.org/sdata/policies/repositories)  
> **OpenDOAR - Directory of Open Access Repositories**  →  [v2.sherpa.ac.uk/opendoar/](https://v2.sherpa.ac.uk/opendoar/)
{: .prereq}


> ## Exercise - Level Medium 🌶🌶
>
> 1. Go to **[dataverse.org](https://dataverse.org/)** and scroll down until you see a map. Respond to the following:  
> 2. How many installations of Dataverse are?  
> 3. How many Dataverse installations are in the Netherlands?  
> 4. DataverseNL is the data repository hosted by DANS. It supports all higher education institutions in the Netherlands. How many datasets exist now in DataverseNL?   
> {: .source}
>
> > ## Solution
> >
> > 2. There are 83 installations worldwide. This means that 83  Organizations have a copy of the original Harvard Dataverse layout and have hosted it on their own servers to support researchers.  
> > 3. There are 3 installations in the Netherlands: DataverseNL, IISH Dataverse,  and NIOZ Dataverse. 
> > 4. There are 6,075. 
> > {: .output}
> {: .solution}
{: .challenge}


### 3. What is a DOI, and why is it important?

The DOI is a common identifier used for academic, professional, and governmental information such as articles, datasets, reports, and other supplemental information. The [International DOI Foundation (IDF)](https://www.doi.org/) is the agency that oversees DOIs. [CrossRef](https://www.crossref.org/) and [Datacite](https://datacite.org/) are two prominent not-for-profit registries that provide services to create or mint DOIs. Both have membership models where their clients are able to mint DOIs distinguished by their prefix. For example, DataCite features a [statistics page](https://stats.datacite.org/) where you can see registrations by members.

A DOI has three main parts:

- Proxy or DOI resolver service
- Prefix which is unique to the registrant or member
- Suffix, a unique identifier assigned locally by the registrant to an object

<img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/04-2.jpeg" alt="hardvard" style="width:100x;height:80x;">

In the example above, the prefix is used by the Australian National Data Service (ANDS) now called the Australia Research Data Commons (ARDC) and the suffix is a unique identifier for an object at Griffith University. DataCite provides DOI [display guidance](https://support.datacite.org/docs/datacite-doi-display-guidelines
) so that they are easy to recognize and use, for both humans and machines.

> ## Exercise - Level Hard 🌶🌶🌶
>
> 1. Watch the following tutorial to create a dataset in the DEMO DataverseNL
>
> 2. Download this mock dataset to do it.
> 
> 3. What is the DOI of your dataset?
> {: .source}
>
> > ## Solution
> >
> > Did you watch it already? 🤓
> > {: .output}
> {: .solution}
{: .challenge}


> ## Discussion  
> Given that uploading sensitive research data such as interviews. Dicuss in group on how to archive this type of projects in a data reporostory
>
{: .discussion}