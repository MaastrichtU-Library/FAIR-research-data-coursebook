---
title: "Data Access Protocols"
teaching: 10
exercises: 15
questions:
- "What are data access protocols?"
- "Is Open Access a data access protocol?"
objectives:
- "First"
- "Second"
keypoints:
- "First key point."
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

### What are Data Access Protocols?

"Data Access Protocols" are a set of formatting and processing rules for data communication.  

Imaging you enter in a security room, you need to follow the protocols for accessing.

"Data Access Protocols"  exist on a wide variety of ranges.  
- Some are more "machine friendly" 
- Some other are more "human friendly"

An example of **machine friendly** is **The European Union Public Data**   → [LINK TO EXAMPLE](https://data.europa.eu/data/sparql)  
Which makes available all public datasets. The "Data Access Protocol" in this case is a machine-redable endpoint (permanent link) [https://data.europa.eu/sparql](https://data.europa.eu/sparql)

> ## Protocols are like a common language for computers.
> Just as the United Nations relies on its 6 official languages to communicate amongst representatives from all over the globe.
> 
> Computers have common languages to communicate such as:
> Internet Protocol (IP)
> Transmission Control Protocol (TCP) 
> Hypertext Transfer Protocol (HTTP/HTTPS) 
{: .callout}

On a strict sense, data access protocols have relation to netrowk protocols definitions. However, when it comes to Research Data we can be flexible the rules and protocols for access depending on the use case.

An example of **human friendly** is when the data can't be publicly available and there is no special repository for it. Therefore you request the user to contact you for getting access.

IMAGE ETUI MARCUS

 Example: **Mapping EU Company Mobility & Abuse-Detection**   → [LINK TO EXAMPLE](https://eu-corporate-mobility.org/)  

## Is Open Access a Data Access Protocol?

Yes.  
Withing the Open Science framework it is endoresed to standarize open access datasets when is pissbloe to make it publicly available and does not violet legal or ethical considerations.

[Open Access NL](https://www.openaccess.nl/en/wat-is-open-access/open-data)

OPEN ACESS IMAGE

Depositing datasets in data public repositories can grant them Open Access protocol automatically. Data repositories normally work as a data achiving instrument, on which we cover in episode 6 (LINK TO EPISODE)


> ## Exercise - Level Easy 🌶
>
> Is it possible to edit the Terms of Use in DataverseNL?
>
>  Go to [ZENODO Covid 19 Community](https://zenodo.org/communities/covid-19/).
> Can you tell what is the default "Data Access Protocol" for the Digital Objects displayed
> {: .source}
>
> > ## Solution
> >
> > Open Access. It is indicated in the green tag on top of the titles.
> >
> > {: .output}
> {: .solution}
{: .challenge}

> ## Open Access is a human and machine friendly Data Access Protocol
>  Humans see a "Download" buttom  
>  Machines see an HTTPS request
{: .callout}

## How can I expose my data as an API endpoint?


	- The software, data and paper is open access. Put the links to the Zenodo downloadable access or github (https://zenodo.org/record/4657236 link: https://zenodo.org/record/4657236/files/MaastrichtU-IDS/clean-technologies-nlp-1.0.zip?download=1)
	- ENDPOINT https://triplydb.com/hdezserrano/CleanTechTag-CORDIS-DATA/graphs/default
	- OR SPARQL ENDPOINT 
	    pip install rdflib-endpoint@git+https://github.com/vemonet/rdflib-endpoint@main
	    rdflib-endpoint serve your-file.nt
	- Optional: create documentation of API

- Output:
	- In case is a document (README) then get the link
	- In case is a service (API) then register to a registry https://www.smart-api.info/