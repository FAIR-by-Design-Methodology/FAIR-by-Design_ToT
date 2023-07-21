---
title: "Preparing & Ideating"
author: "Skills4EOSC T2.3"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Instructional design process
---

# Preparing FAIR Learning Objects

The purpose of this learning unit is to introduce all relevant FAIR concepts that are necessary when developing learning objects such as metadata, PIDs, repo, licenses, attribution, etc. Once these concepts are adopted, the instructional designer is then ready to start with the backwards instructional process. The first step is ideation wherein the main aspects of the learning materials such as learning objects need to be defined.

## Learning Objectives

- Recognize metadata
- Identify Permanent Identifiers (PIDs)
- Compare licenses
- Write attribution
- Categorizing learning repositories
- Interpret the instructional design process
- Preparing learning objectives

## Target Audience
- attendees of the FAIR-by-Design ToT live webinar

## Duration
30 mins

## Prerequisites
- [01-FAIR Skills & Principles](../../01-FAIR%20skills%20&%20principles/Content/01-FAIR%20skills%20&%20principles.md)

## Learning Tools
- Training BBB room
- Browser
- Menti access or BBB quiz interaction

## Metadata and Metadata Schema

Metadata is one of the key ingredients to making learning resources findable, accessible, and reusable. In essence, metadata consists of structured information that describes, explains and locates a resource.

The main purpose of the (meta)data about the learning resource is to enable cataloguing and discovery by providing a standard means to report on:
- WHO created the resource
- WHAT is the content of the resource
- WHEN was the data resource
- WHERE is the location of the resource
- WHY the data was resource

Using this information a learner or instructor should be able to:
- Search and retrieve the information about a learning resource 
- Determine if the learning resource meets certain learning requirements
- Discover how to acquire and use the learning resource

### RDA Minimal Metadata for Learning Resources

The [RDA Education And Training On Handling Of Research Data Interest Group](https://www.rd-alliance.org/groups/education-and-training-handling-research-data.html) has defined a [minimal metadata seta for learning resources](https://zenodo.org/record/6769695#.YrrP9-xBybQ) that has become a de facto standard for describing FAIR learning materials.

The following table describes the minimal metadata set elements and their definitions:

| **Element Name** | **Definition** |
|---|---|
| Title | The human readable name of the resource. |
| Abstract / Description | A brief synopsis about or description of the learning resource |
| Author(s) | Name of entity(ies) authoring the resource |
| Primary Language | Language in which the resource was originally published or made available |
| Keyword(s) | Keywords or tags used to describe the resource |
| License | A license document that applies to this content, typically indicated by URL |
| Version Date | Version date for the most recently published or broadcast resource |
| URL to Resource | URL that resolves to the learning resource or to a "landing page" for the resource that contains important contextual information  including the direct resolvable link to the resource, if applicable. |
| Resource URL Type | Designation of the identifier scheme  used for the resource URL, e.g., DOI, ARK, Handle |
| Target Group (Audience) | Principal users(s) for which the resource was designed |
| Learning Resource Type | The predominant type or kind that characterizes the learning resource |
| Learning Outcome | Descriptions of what knowledge, skills or abilities a learner should acquire on completion of the resource |
| Access Cost | Choice stating whether or not there is a fee for use of the resource (yes, no, maybe) |
| Expertise (Skill) Level | Target skill level in the topic being taught; example values include beginner, intermediate, advanced |

This table is taken from [RDA Minimal Metadata for Learning Resources](https://doi.org/10.15497/RDA00073) by Hoebelheinrich, Nancy J; Biernacka, Katarzyna; Brazas, Michelle; Castro, Leyla Jael; Fiore, Nicola; Hellström, Margareta; Lazzeri, Emma; Leenarts, Ellen; Martinez Lavanchy, Paula Maria; Newbold, Elizabeth; Nurnberger, Amy; Plomp, Esther; Vaira, Lucia; van Gelder, Celia W G; Whyte, Angus licensed under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode).

These elements need to be standardized so that they are useful when used in practice. This is done by defining a metadata schema that describes the structure of the metadata elements. The metadata schema defines the standards for describing the metadata elements.

The metadata schema for learning resources that also defines the type of each element, the allowed values, and constraints is available on the RDA website: [RDA Minimal Metadata for Learning Resources Professional and Informal Education Examples](https://www.rd-alliance.org/system/files/Copy%20of%20Examples%20for%20Professional%20and%20Informal%20Education.pdf)

### Controlled Vocabularies

Some of the fields in the proposed RDA metadata schema are based on fixed or suggested controlled vocabularies (CV). The use of controlled vocabularies is to help humans and machines categorize the information while helping to reduce duplication and errors. 

In essence, controlled vocabularies should be used for any metadata elements with predefined value(s), where in the vocabulary is presented as a list of prescribed items. 

Such examples are 
- Access Cost with possible values of Y, N and Maybe
- Primary Language that can be a two letter code from the [ISO 639-1:2002 codeset](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)

Note that in many cases controlled vocabularies are suggested, but at this stage they are not strictly defined.

Later on during this training, you will learn how and where to define the metadata for your learning resources.

## Learning materials repositories

The learning materials need to be stored in a learning repository so that they are made available to others. 
As the two perspective on learning materials (learners and instructors) have different needs regarding the type and content of the learning materials, to ensure FAIRness for both perspective the learning materials should be stored in two separate repositories:
- training repository that hosts editable learning materials for instructors
- learning repository that stores final learning materials to be consumed by learners.

In Skills4EOSC the suggested choices for the repositories are as follows:
- learning materials for instructors should be stored on Zenodo (from GitHub)
- learning materials for learners should be stored on the Skills4EOSC learning platform 


## Persistent Identifiers

A persistent identifier (PID) is a type of metadata. Its purpose is to uniquely tag a digital object and ensure that this tag is not going to change over time (remains persistent).

Using a PID one should be able to land on an accessible page with the listed digital object and its metadata. The actual access to the digital object from this page may be restricted. 

PIDs are machine readable and help distinguish between 
- different materials
- different versions of the same material.

Multiple kinds of PIDs exist such as DOI (digital object identifier), Handle (HNDL), ARK (Archival Resources Key).

For the purposes of creating FAIR learning materials we will be using a Zenodo provided DOI to generate a PID for the trainers learning material kit and the internal IDs system of the Skills4EOSC learning platform for identifying learning resources for learners. 


## IPR

### Licensing

### Attribution

## Backward instructional design process

purpose 

target audience

scope 

prerequisites

### Learning Objectives

#### Bloom's Taxonomy





## Summary

At the end provide a short summary of the main points of the learning unit (these are the key takeaways that help reflect on the learning outcomes)

## Suggested Reading
- [Hoebelheinrich, Nancy J, Biernacka, Katarzyna, Brazas, Michelle, Castro, Leyla Jael, Fiore, Nicola, Hellström, Margareta, Lazzeri, Emma, Leenarts, Ellen, Martinez Lavanchy, Paula Maria, Newbold, Elizabeth, Nurnberger, Amy, Plomp, Esther, Vaira, Lucia, van Gelder, Celia W G, & Whyte, Angus. (2022). Recommendations for a minimal metadata set to aid harmonised discovery of learning resources (1.0).](https://doi.org/10.15497/RDA00073)
- [Jesse Long, Lisa Curtin, Persistent Identifiers, NTL Guide to DOIs & ORCID iDs for DOT Researchers, National Transportation Library (2022)](https://transportation.libguides.com/persistent_identifiers)
- 
