---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

<style>
h1 {text-align: center;}
</style>

<br>
<h1>Six Steps to FAIR Implementation (with examples) ♻️ </h1>
<hr>

**Keywords**: `Research Data Management`, `Research Data Reuse`, `FAIR`, `FAIR Digital Objects`.


<img src="/fig/FAIRcoursebook-image0.png" alt="FAIR Research Data Logo" width=800>

> 📢 **This coursebook was last updated in January 2025.**

## About 📗

Usually, training materials on FAIR principles are tedious and contain extensive theory. In this Library Carpentries-based coursebook, we aim to teach the implementation of FAIR principles differently. It has low entry-level materials and examples that the average researcher can understand and immediately apply.

Some relevant topics the coursebook aims to address are the following:

- Get to know the importance of a “Research Digital Object”.
- Explore the available open-source tools for interoperability to make research digital objects sustainable.
- You will learn what “Data Terms of Use” and “Data Access Protocols” are and how to create them.
- You will review the differences and similarities of “Data Descriptions” in different science fields to discuss what we can do (as a scientific community) to standardize these practices.
- You will learn what “Rich Metadata” technically means on the Semantic Web and its relation to sustainable research output for future researchers.    

> 💡 **Following a bolder approach, we want to teach the implementation of FAIR principles differently. There is less focus on the theory and more emphasis on examples. Guided by 6 steps in Research Data Management**
{: .callout}


<div style="font-size: 24px;">
    <h2>Six steps to FAIR</h2>
    <ol style="display: inline-block; text-align: left;">
        <li>📜 Set up your own terms ➡️ <a href="{{ site.baseurl }}/02-terms-of-use/index.html">Data Terms of Use</a></li>
        <li>🌍 Speak the same language ➡️ <a href="{{ site.baseurl }}/03-data-descriptions/index.html">Data Descriptions</a></li>
        <li>🔒 Securely share ➡️ <a href="{{ site.baseurl }}/04-access-protocols/index.html">Data Access Protocols</a></li>
        <li>📦 Publish and preserve ➡️ <a href="{{ site.baseurl }}/05-data-archiving/index.html">Data Archiving</a></li>
        <li>🤖 Make machines work for you ➡️ <a href="{{ site.baseurl }}/06-rich-metadata/index.html">Rich Metadata</a></li>
        <li>♻️ Responsibly reuse ➡️ <a href="{{ site.baseurl }}/07-data-reusing/index.html">Data Reusing</a></li>
    </ol>
</div>


----

> ## Acknowledgements 🙏
> 
> These efforts are realized with the support from the [SURF funding for strengthening the RDM landscape on Digital Competence Center](https://www.dtls.nl/2022/01/24/surf-honors-10-proposals-in-call-for-proposals-digital-competence-centers-to-work-on-strengthening-the-rdm-landscape/) and the backing of [Maastricht University Library](https://library.maastrichtuniversity.nl/research/rdm/).
>   
> This coursebook draws inspiration from the [FAIR Teaching Handbook](https://fairsfair.gitbook.io/fair-teaching-handbook/0lessonplans/1lessonplan), incorporating various elements and illustrations from [The Turing Way](https://the-turing-way.netlify.app/welcome.html). Our approach aims to simplify the learning process for researchers by focusing on practical examples over theory. For those interested in delving deeper into FAIR principles, resources like the [FAIR Cookbook](https://the-turing-way.netlify.app/welcome.html) where you can further explore.
{: .prereq}

----

> ## Cite this Coursebook
> > [Hernández Serrano, Pedro](https://www.maastrichtuniversity.nl/nl/p.hernandezserrano); [Vivas Romero, Maria](https://www.maastrichtuniversity.nl/m.vivasromero); Library Carpentries (2022, August 8): FAIR Research Data Coursebook. Zenodo. [doi.org/10.5281/zenodo.6974103](https://doi.org/10.5281/zenodo.6974103)
{: .prereq}


{% include links.md %}

<!-- {% include syllabus.html %} -->

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-1JS8K9J9GE"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-1JS8K9J9GE');
</script>

<script type="application/ld+json">
{
    "@context": "https://schema.org",
    "@type": "Course",
    "name": "FAIR Research Data Coursebook",
    "description": "Welcome to the FAIR Research Data Coursebook. This resource is an Open Educational Resource designed in accordance with FAIR and Open Science guidelines. Traditional training materials on FAIR principles often come across as dense and heavily theoretical. Our approach, inspired by Library Carpentries, aims for a different learning experience. This coursebook offers accessible, entry-level content and practical examples to enable researchers to easily grasp and apply FAIR principles in their work.",
    "version": "v1.3",
    "url": "https://doi.org/10.5281/zenodo.6974103",
    "license": "https://creativecommons.org/licenses/by/4.0/legalcode",
    "dateCreated": {
        "@type": "Date",
        "@value": "2022-08-01"
    },
    "inLanguage": {
        "@type": "Language",
        "name": "EN",
        "alternateName": "EN"
    },
    "keywords": [
        "Research Data Management",
        "Research Data Reuse",
        "FAIR",
        "FAIR Digital Objects",
        "FAIR Data"
    ],
    "creator": {
        "@type": "Person",
        "name": "concat @givenName @familyName",
        "givenName": "Pedro",
        "familyName": "Hernandez Serrano",
        "image": "https://avatars.githubusercontent.com/u/12054964?v=4",
        "jobTitle": "Data Steward",
        "email": "p.hernandezserrano@maastrichtuniversity.nl",
        "affiliation": {
            "@type": "Organization",
            "name": "Maastricht University",
            "url": {
                "@type": "URL",
                "@value": "https://maastrichtuniversity.nl"
            }
        }
    },
    "contributor": [
        {
            "@type": "Person",
            "givenName": "Maria",
            "familyName": "Vivas Romero",
            "jobTitle": "Data Steward",
            "email": "m.vivasromero@maastrichtuniversity.nl",
            "affiliation": {
                "@type": "Organization",
                "name": "Maastricht University",
                "url": {
                    "@type": "URL",
                    "@value": "https://maastrichtuniversity.nl"
                }
            }
        }
    ],
    "publisher": {
        "@type": "Person",
        "name": "Pedro Hernandez Serrano",
        "givenName": "Pedro",
        "familyName": "Hernandez Serrano",
        "jobTitle": "Data Steward",
        "email": "p.hernandezserrano@maastrichtuniversity.nl"
    },
    "citation": {
        "@type": "CreativeWork",
        "name": "FAIR Research Data Coursebook",
        "creator": [
            {
                "@type": "Person",
                "name": "Pedro Hernandez Serrano"
            },
            {
                "@type": "Person",
                "name": "Maria Vivas Romero"
            }
        ]
    },
    "learningResourceType": "Coursebook",
    "dateModified": {
        "@type": "Date",
        "@value": "2024-02-24"
    }
}
</script>