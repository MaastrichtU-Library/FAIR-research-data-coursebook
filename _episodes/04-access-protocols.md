---
title: "Data Access Protocols"
teaching: 10
exercises: 15
questions:
- "1 What are data access protocols?"
- "2 Is Open Access a data access protocol?"
- "3 Can I expose my data as a service using FAIR API protocols?"
objectives:
- "The participant will learn what data access protocols are"
- "The participant will explore the aspects of an access protocol for humans and machines."
keypoints:
- "Data Access Protocols are a set of formatting and processing rules for data communication. For example, imagine you enter a security room. You must follow certain steps or possess keys to access the room."
- "When you expose your data using FAIR protocols, you must register your service in a registry for FAIR APIs such as [SMART API](https://www.smart-api.info/)"
---

> ## FAIR principles used in Data Access Protocols:  
> **Accessible**   
> > FM-A1.1 (Access Protocol) → [doi.org/10.25504/FAIRsharing.yDJci5](https://doi.org/10.25504/FAIRsharing.yDJci5)  
> > FM-A1.2 (Access Authorization) → [doi.org/10.25504/FAIRsharing.EwnE1n](https://doi.org/10.25504/FAIRsharing.EwnE1n)  
>
> **Interoperable**  
> > FM-I3 (Use Qualified References) → [doi.org/10.25504/FAIRsharing.B2sbNh](https://doi.org/10.25504/FAIRsharing.B2sbNh)  
>
{: .checklist}

### 1. What are Data Access Protocols?

Data Access Protocols are a set of formatting and processing rules for data communication. In practice, Data Access Protocols are the **explicit instructions** for humans and machines to access a data source.   

Imagine you enter a security room. You need to follow the specific steps or possess specific keys for accessing the room. The same is with data. Moreover, if the door of the room is *open* we can say it is **Open Access**

<img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/05-2.png" alt="access">


Following the premise that "Data Access Protocols" are a common set of rules on a standard language, they exist in various ranges. For example, some messages are directed to humans, and some protocols are meant for machines.  



|Access Protocol|Example|Note|
|---|---|---|
|Communication between machines|![](https://study-ccna.com/wp-content/images/http_process_explained.jpg)|A PC requesting information using HTTP protocol|
|Communication between humans|<img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/05-1.png" alt="etui" weight=200 height=300>|Data owner requesting users to contact deriectly for data access|

Image: **Mapping EU Company Mobility & Abuse-Detection**   → [LINK TO EXAMPLE](https://eu-corporate-mobility.org/)

In a strict sense, data access protocols relate to network protocol definitions. However, regarding Research Data, the human factor plays a part. Therefore we can explicitly mention the rules and instructions for accessing data depending on the use case. Sometimes the data can't be publicly available, and there is no particular repository for it. Therefore you request the user to contact you to get access. We could say it is a **human-friendly** access protocol.

For example:   

In **Data Request Form UMC Utrecht**  → [LINK TO EXAMPLE](https://preview.umcutrecht.nl/en/data-request-form-umc-utrecht)    
The University Medical Center at Utrecht (UMC Utrecht) has an open *data request form* for users to access clinical data for research purposes. The form asks general things related to the researcher's identification and affiliation, research context and methodologies. Furthermore, they explicitly mention that the *Data Access Committee* will review and consider applications and respond within 4 weeks.


> ## Protocols are like standard rules communicated in a standard language for humans and machines.
> We humans use the English language for communication in science predominantly.
> 
> > Machines need a "medium" to talk to each other such as an **API [(Application Programming Interface)](https://en.wikipedia.org/wiki/Web_API)**, and they use a "communication language" such as **HTTP [Hypertext Transfer Protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)**  to share information between one another.   
> >
> > Relevant API protocols are:  
> >
> > - [SOAP](https://en.wikipedia.org/wiki/SOAP) API  
> > - [SPARQL](https://en.wikipedia.org/wiki/SPARQL) API  
> > - [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) API   
{: .prereq}


### 2. Is Open Access a data access protocol?

Open Access is a policy framework in the strict sense but yes! We could say it's a data access protocol.
Within the Open Science recommendations, it is endorsed to standardise open access datasets when it is possible to make them publicly available and does not violet legal or ethical considerations. More information at [Open Access](https://www.openaccess.nl/en/wat-is-open-access/open-data)

<img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/05-3.png" href="https://www.openaccess.nl/en/wat-is-open-access/open-data" alt="access">

Depositing datasets in public data repositories can grant them open access protocol automatically. In addition, data repositories typically work as a data archiving instrument, which we cover in [Episode 6 (Data Archiving)](https://maastrichtu-library.github.io/circular-research-data-bootcamp/05-data-archiving/index.html).  

Moreover, Open Acess data sources can be made available using FAIR protocols such as SPARQL API endpoints.  

An example is:  

**The European Union Public Data**   → [LINK TO EXAMPLE](https://data.europa.eu/data/sparql)  
Which makes available all public datasets. the following endpoint (permanent link) [https://data.europa.eu/sparql](https://data.europa.eu/sparql)  

<img src="https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/images/05-4.png" href="https://data.europa.eu/data/sparql" alt="access">


> ## Exercise - Level Easy 🌶
>
> 1. Go to [ZENODO Covid 19 Community](https://zenodo.org/communities/covid-19/).  
> 2. Can you tell what is the default "Data Access Protocol" for the Digital Objects displayed?  
> {: .source}
>
> > ## Solution
> >
> > It is *Open Access*. It is indicated in the green tag on top of the titles.
> >
> > {: .output}
> {: .solution}
{: .challenge}

> ## Open Access is a human and machine-friendly Data Access Protocol
>  Humans see a "Download" button  
>  Machines see an HTTPS request  
{: .callout}

## 3. Can I expose my data as a service using FAIR API protocols?

Yes, it is possible; however, it is not an easy road and requires technical skills.  
We must remember that exposing data as a service would mean we need a server to host it, which we don't always have. Moreover, one of the main motivations to expose our data using FAIR protocols is to make it accessible for other data sources to integrate. But for that, you would need some basics of Knowledge Graphs. More information about you can find in the [FAIR Elixir Cookbok](https://faircookbook.elixir-europe.org/content/recipes/introduction/FAIR-and-knowledge-graphs.html) 

|Tool | Source | GUI | Note|
| ---| ---|
|TriplyDB | [LINK](https://triplydb.com/)| ✅| Free account, you can expose your data on their servers for a limited time |
|GraphDB | [LINK](https://www.ontotext.com/products/graphdb/)| ✅| Nice interface; you need to rely on a server    |
|FAIR Data Point | [LINK](https://github.com/fair-data/fairdatapoint)| ❌ | Highly technical, requires programing language knowledge |
|RDFlib Endpoint | [LINK](https://pypi.org/project/rdflib-endpoint/)| ❌|Requires familiarity with terminal, but is the quickest way to get started|

> Important!
> When you expose your data using FAIR API protocols, you must register your service in a registry for FAIR APIs such as [SMART API](https://www.smart-api.info/)
{: .prereq}

> ## Exercise - Level Hard 🌶🌶🌶
>
> - Expose your RDF data to a service endpoint using a FAIR API protocol  
> > 1. Use the RDF data you generated in Episode 2 (data descriptions) else you can download it here
> > 2. In your terminal, install the following library using the default Python installation `pip install rdflib-endpoint@git+https://github.com/vemonet/rdflib-endpoint@main`  
> > 3. Next, execute the following command to locally expose your data `rdflib-endpoint serve data-file.nt`
> {: .source}
>
> > ## Solution
> >
> > This exercise is optional
> >
> > {: .output}
> {: .solution}
{: .challenge}


> ## Discussion  
> What do you do on granting access credentials upon request? application? Form?   
>
{: .discussion}

> ## Discussion  
> Scenario:  
You are a researcher of Sustainable Investment from the Economics department. After your research, you ended up possessing sensitive financial information of company figures that can not be disclosed. You will store the data in a secure envirnment but you would like to make it available for research purposes.  
> 
> Discuss with your team what type of access protocols shall be considered in this case. 
{: .discussion}