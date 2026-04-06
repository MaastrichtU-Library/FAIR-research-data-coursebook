---
title: "Publish and preserve"
teaching: 10
exercises: 15
---

:::::::::::::::::::::::::::::::::::::: questions

- What is data archiving?
- What are data repositories?
- What is a DOI, and why is it important?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand the role of trusted repositories in long-term preservation.
- Learn why repositories improve discovery and citation.
- Understand how DOI supports persistence and citation.

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: callout

### FAIR principles used in data archiving

Findable:

- FM-F1A Identifier Uniqueness: <https://doi.org/10.25504/FAIRsharing.r49beq>
- FM-F3 Resource Identifier in Metadata:
  <https://doi.org/10.25504/FAIRsharing.o8TYnW>

Accessible:

- FM-A2 Metadata Longevity: <https://doi.org/10.25504/FAIRsharing.A2W4nz>

::::::::::::::::::::::::::::::::::::::::::::::::

## What is data archiving?

Data archiving is the long-term preservation of research data and related
digital objects.

Funders and journals increasingly expect enough of the data and methods to be
preserved so that results can be inspected, understood, and, where possible,
replicated.

## What are data repositories?

Data repositories are storage locations for digital objects such as datasets,
code, supplementary files, and metadata.

Repositories make research outputs easier to find and can also provide:

- preservation
- backup
- citation infrastructure
- versioning
- controlled access options

Examples:

| Repository | About |
| --- | --- |
| DataverseNL | Community repository supporting Dutch universities and research centers |
| 4TU Data | Repository originally developed by Dutch technical universities |
| PANGAEA | Domain repository for Earth and environmental sciences |
| Figshare | General-purpose repository for many digital object types |

::::::::::::::::::::::::::::::::::::: callout

### General repository recommendations

- Zenodo: <https://zenodo.org/>
- SURF Repository: <https://repository.surfsara.nl/>
- DataverseNL: <https://dataverse.nl/>

Aim for a community repository when it exists. If not, a trusted general
repository is usually better than leaving data only on a local drive or project
website.

::::::::::::::::::::::::::::::::::::::::::::::::

Typical strengths of general-purpose repositories include:

- persistent identifiers
- rapid publication
- versioning
- backup and preservation
- usage statistics
- open or restricted access modes

![Repository comparison matrix](https://datamanagement.hms.harvard.edu/sites/g/files/mcu941/files/assets/Images/2020-12-10-Repo-Matrix.png){alt='Comparison chart of repository options'}

Additional registries that help identify suitable repositories:

- re3data: <https://www.re3data.org/>
- PLOS recommended repositories:
  <https://journals.plos.org/plosone/s/recommended-repositories>
- NIH repositories guidance:
  <https://sharing.nih.gov/data-management-and-sharing-policy/sharing-scientific-data/repositories-for-sharing-scientific-data>
- OpenDOAR: <https://v2.sherpa.ac.uk/opendoar/>

For context on the original Dataverse model, see Harvard Dataverse:

- <https://dataverse.harvard.edu/dataverse/harvard>
- Introductory video: <https://www.youtube.com/watch?v=MPQ0Tpgaxt0>

::::::::::::::::::::::::::::::::::::: challenge

## Exercise

Visit <https://dataverse.org/> and inspect the current installation map and the
DataverseNL portal.

Answer:

- How many Dataverse installations are listed now?
- How many are in the Netherlands?
- Roughly how many datasets are visible in DataverseNL at the time of your
  visit?

:::::::::::::::::::::::: solution

These counts change over time, so record the values you observe at the moment
you complete the exercise rather than relying on historical numbers from older
lesson versions.

:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::

## What is a DOI, and why is it important?

DOI is a persistent identifier commonly used for articles, datasets, reports,
and other scholarly outputs.

Two major DOI registration services in research are:

- Crossref: <https://www.crossref.org/>
- DataCite: <https://datacite.org/>

A DOI has three conceptual parts:

- the resolver service
- the registrant prefix
- the locally assigned suffix

![Diagram explaining DOI structure](https://authorcarpentry.github.io/CODATA-RDA-Trieste-2016/Figure1.jpg){alt='Illustration of DOI components'}

DOIs make resources easier to cite and track, and they continue resolving even
when storage details change.

::::::::::::::::::::::::::::::::::::: challenge

## Exercise

Upload a test dataset to the DataverseNL demo or another training repository:

1. Download the mock dataset: [MOCK DATA](data/MOCK_DATA_BOOTCAMP.xlsx)
2. Deposit it in a suitable demo or sandbox repository
3. Record the DOI or persistent identifier you receive

:::::::::::::::::::::::: solution

There is no single correct answer. The point is to experience how a repository
assigns persistent identifiers and what metadata are required before publication.

:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: discussion

### Scenario

You conducted personal interviews for an ethnographic migration study. The raw
transcripts cannot be openly shared, even under restricted access.

How should archiving be handled in this case? What metadata, derived outputs, or
access statements should still be preserved and published?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints

- Repositories improve preservation, discovery, and citation.
- Prefer a trusted community repository when one fits your discipline.
- General repositories such as Zenodo still provide a strong baseline for FAIR
  publication.
- DOI is a key persistent identifier for datasets and publications.

::::::::::::::::::::::::::::::::::::::::::::::::
