---
title: "Speak the same language"
teaching: 10
exercises: 15
---

:::::::::::::::::::::::::::::::::::::: questions

- What are data descriptions?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Confirm that this episode path builds with minimal valid content.
- Recognize that data descriptions help people interpret dataset variables.

::::::::::::::::::::::::::::::::::::::::::::::::

Data descriptions explain what dataset fields mean so that others can interpret
and reuse the data correctly.

Depending on the community, similar documents may also be called:

- codebooks
- data dictionaries
- variable descriptions

Clear descriptions reduce ambiguity and make later reuse easier.

## Why shared language matters

Different teams may use different names for the same concept. A clear data
description helps readers understand whether two fields really refer to the
same thing.

Where possible, reuse established community terms rather than inventing a new
definition for every project.

## Reusing existing terms

When a concept is already described by a community vocabulary or ontology, it
is often better to reuse that definition than to write a completely local one.

This helps:

- reduce ambiguity
- improve interoperability
- make comparisons across datasets easier

## Practical minimum

A useful data description usually includes:

- the variable or field name
- a short definition
- units or scale where relevant
- links to reused community terms when available

## From local notes to interoperable descriptions

Many projects begin with informal notes in spreadsheets, lab books, or README
files. Those notes are useful, but they become more valuable when they are
written consistently and can be understood outside the original team.

A good next step is to review descriptions field by field and make sure that:

- abbreviations are explained
- measurement units are explicit
- coded values are defined
- reused concepts are named consistently

## Why this matters for FAIR data

Without good descriptions, a dataset may be visible but still difficult to
interpret correctly. Clear definitions make later sharing, integration, and
reuse more realistic.

## Examples of useful descriptive detail

The more concrete a description is, the easier it becomes to interpret the
data correctly.

For example, a helpful description may clarify:

- whether a date refers to collection, publication, or update time
- whether a value is measured or derived
- whether a category uses local project labels or a wider standard

These details help others avoid misreading the dataset.

## Reuse across projects

Well-described variables are easier to compare across studies, repositories,
and software workflows. Even when datasets are not identical, shared language
makes it easier to spot overlap and understand differences.

That is especially useful when:

- combining data from multiple sources
- reusing legacy datasets after a long time gap
- handing data to collaborators outside the original team

::::::::::::::::::::::::::::::::::::: keypoints

- This episode is being restored conservatively to preserve build stability.
- Data descriptions help people understand what dataset variables mean.
- Reusing shared terms makes data easier to compare and combine.
- A practical description should define fields clearly and note reused terms.
- Better field descriptions improve later sharing and reuse.
- Concrete definitions reduce the risk of misinterpreting data fields.
- Shared descriptions make cross-project reuse easier.

::::::::::::::::::::::::::::::::::::::::::::::::
