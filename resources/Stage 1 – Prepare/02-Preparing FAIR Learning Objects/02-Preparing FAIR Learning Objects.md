---
title: Preparing
author: Skills4EOSC T2.3
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Metadata
    - PIDs
    - Repositories
    - IPR
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

- [01-FAIR Skills & Principles](../01-FAIR%20skills%20&%20principles/01-FAIR%20skills%20&%20principles.md)

## Learning Tools

- Training BBB room
- Browser
- Menti access or BBB quiz interaction

## Metadata and Metadata Schema

Metadata is one of the key ingredients to making learning resources findable, accessible, and reusable. In essence, metadata consists of structured information that describes, explains and locates a resource.

The main purpose of the (meta)data about the learning resource is to enable cataloguing and discovery by providing a standard means to report on:

- WHO created the resource
- WHAT is the content of the resource
- WHEN was the resource created
- WHERE is the location of the resource
- WHY the data was resource

![example metadata for an image](./attachments/image_metadata.png){: style="height:350px;"}

Example metadata for an image


Using this information a learner or instructor should be able to:

- Search and retrieve the information about a learning resource 
- Determine if the learning resource meets certain learning requirements
- Discover how to acquire and use the learning resource

### RDA Minimal Metadata for Learning Resources

The [RDA Education And Training On Handling Of Research Data Interest Group](https://www.rd-alliance.org/groups/education-and-training-handling-research-data.html) has defined a [minimal metadata set for learning resources](https://zenodo.org/record/6769695#.YrrP9-xBybQ) that has become a de facto standard for describing FAIR learning materials.

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

## Intellectual Property Rights (IPR)

Intellectual property refers to the creation of intellectual activity. Intellectual Property Rights (IPR) protects the interests of the creators and owners by providing them with rights over their creation. 

For the purposes of creation of learning materials, the copyright and related rights main branches of IPR are used. They are defined to protect literary and artistic creations, performances, phonograms by defining the authors’, owners’, performers’, producers’ and broadcasters’ rights. In some cases additional IPR branches might be involved.

### Copyright

Original work can be protected by copyright law that grants the owner **exclusive right** to control certain rights such as reproduction. The copyright is owned jointly by all authors, or it may be owned by the employing institution.

Any work that you create by default makes you or your institution/employer the copyright holder of it.

**Use of copyright protected work requires permission from the owner**. Permission may not be required in the case of works licensed in the public domain and uses covered by Copyright Exceptions.

Only the copyright holder is allowed to distribute whatever is created. If you want to transfer this right to other people as well, you can do that via a license.

In absence of exceptions or limitations, one can reuse an existing work if it is licensed to the user or it is licensed to the public using a public license such as the [Creative Commons (CC) licenses](https://creativecommons.org/licenses/) or [Free-Libre / Open Source Software (FLOSS) licenses](https://dwheeler.com/essays/floss-license-slide.html).

### Licensing

>The content in this section is adapted from:
>
>- [CC FAQ website](https://creativecommons.org/faq/#can-i-combine-material-under-different-creative-commons-licenses-in-my-work) licensed under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode)
>- [Creative Commons license Wikipage](https://en.wikipedia.org/wiki/Creative_Commons_license) (2023, June 21) in Wikipedia licensed under the [Creative Commons Attribution-ShareAlike License 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

A license allows you to define rights and obligations regarding the use of your work.

One of the best sources of information for licensing reusable learning materials is [Creative Commons](https://creativecommons.org/). 

There are many available [CC License options](https://creativecommons.org/about/cclicenses/) which are based on the four baseline rights.

![list of CC baseline rights](./attachments/rights.png)

![List of possible CC licenses](./attachments/licenses.png)

It is **recommended** that the least restrictive **[CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)**, requiring only that credit is given to the creator when reusing, is used when creating new learning materials. 

The ND right falls into the opposite extreme and is not recommended for FAIR learning materials licensing as it severely limits their reusability in adaptations.

Public domain licensing (CC0) is also not recommended as different rules apply in different countries.

The [CC License Chooser tool](https://creativecommons.org/choose/) helps authors share their work in a standardised way providing copyright licenses that enable sharing and reuse of the creative work under the chosen conditions. 

**To apply a license** all you have to do is indicate which CC license you are applying to your work. You should then check the terms of the chosen license and comply with the requirements therein. For an example, it is strongly recommended to include a link to the relevant CC license deed (e.g., https://creativecommons.org/licenses/by/4.0). 

Example is provided below:

>![CC BY button](./attachments/by-1.png){: style="height:50px;"}

>Except where otherwise noted, content on this site is licensed under a [Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

#### Activity

Now is a good time to test out the [License Chooser tool](https://creativecommons.org/choose/) and compare licenses.

In the Creative Commons Wiki page: [Marking your work with a CC license](https://wiki.creativecommons.org/wiki/Marking_your_work_with_a_CC_license) there are numerous examples on how license can be applied to different document types.

Throughout this training you will be able to practice combining and applying licenses.


### Attribution and Citing

The right to attribution is a moral right of the authors that protects the personal relationship between the author and the created work even if the creator does not own the copyright.

In other words, acknowledgement of the reused materials through attribution is **always needed** (even if it is not a requirement of the license, such as the public domain licenses). One condition that is **required for all CC licenses** is attribution. 

The **ideal attribution** follows the TASL approach:

- **T**itle - what is the name of the work
- **A**uthor - who allows you to use the work (name and link)
- **S**ource - where can the work be found (link added to title)
- **L**icense - how can the work be used (name and link to the license)

If your work is a modification or adaptation of another work, indicate this and provide attribution to the creator of the original work. You should also include a link to the work you modified and indicate what license applies to that work.

For work created by others that you are incorporating into your own work you want to make it easy for others to know who created what parts of the work using the TASL approach. For an example see the attribution in the previous section of this document.

#### Attribution examples

Creative Commons offer a wiki page with the [Recommended practices for attribution](https://wiki.creativecommons.org/wiki/Recommended_practices_for_attribution).

Some examples on attribution provided on the Creative Commons wiki page are:

- Image attribution
> "[Creative Commons 10th Birthday Celebration San Francisco](http://www.flickr.com/photos/sixteenmilesofstring/8256206923/in/set-72157632200936657)" by [Timothy Vollmer](http://www.flickr.com/photos/sixteenmilesofstring/) is licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

- Adapted image attribution
>  "[Creative Commons 10th Birthday Celebration San Francisco](http://www.flickr.com/photos/sixteenmilesofstring/8256206923/in/set-72157632200936657)" by [Timothy Vollmer](http://www.flickr.com/photos/sixteenmilesofstring/) is licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) / Cropped from original

- Text attribution
> This chapter is from “[You Don't Know JS Yet (2nd Edition)](https://github.com/getify/You-Dont-Know-JS)” by [Kyle Simpson](https://github.com/getify). The book is licensed under the [CC BY-NC-ND 4.0 license](https://creativecommons.org/licenses/by-nc-nd/4.0/). © 2019-2022 Kyle Simpson.

Other sites with other type of licensing may request a different form of attribution. Such is the case with Pixabay that offers royalty-free images where the suggested attribution style is:

> Image by AUTHOR(link) from Pixabay(link)

At the current moment, the Pixabay license allows use of content:

- for free
- without attribution (although recommended)
- for modification and adaptation into new work

#### Citing

Citing can be used for including and **referencing restricted works with limited copyright**. 

However, in the case of using direct quotations with citing, it is essential that the amount of information referenced is very limited (e.g. 200-300 words from a book-length work). In addition, it is recommended to quote works that were already made available to the public in a lawful way and, when possible, to provide the original source and the author's name.

Depending on the country, the reproduction and communication of a protected work may be carried out for the sole purpose of illustration for teaching or scientific research, as long as the source, including the author's name, is indicated, unless this turns out to be impossible and to the extent justified by the non-commercial purpose to be achieved. This falls under the so-called "fair use" of copyright law.

#### Attribution exercise

Write attribution for the following learning resources that you have decided to incorporate in your learning materials:

- [image from https://creativecommons.org/2021/12/02/unesco-recommendation-on-open-science-ratified/](https://creativecommons.org/2021/12/02/unesco-recommendation-on-open-science-ratified/)
- [TRIPLE TRAINING on Open Research Europe slides from https://project.gotriple.eu/triple-open-science-training-series/](https://project.gotriple.eu/triple-open-science-training-series/)
- [slide 3 from Why open science? presentation by Sarah Jones](https://slideplayer.com/slide/12073970/)
- [Lesson 1: The What from https://github.com/opensciency/sprint-content/blob/main/ethos-of-open/lesson1-intro-to-open-science.md](https://github.com/opensciency/sprint-content/blob/main/ethos-of-open/lesson1-intro-to-open-science.md)

Are you able to find all TASL elements for each example?

In the [following example document](./attachments/attribution_example.html) there are several points where attribution and citation is provided. Are they correctly stated?

What are the pitfalls of not using attribution?
Take a look at these two examples:

- [image from https://www.openscience-twente.com/open-science/#open-scientific-knowledge](https://www.openscience-twente.com/open-science/#open-scientific-knowledge)
- [image from https://unesdoc.unesco.org/ark:/48223/pf0000383323](https://unesdoc.unesco.org/ark:/48223/pf0000383323)


## Suggested Reading

- [Hoebelheinrich, Nancy J, Biernacka, Katarzyna, Brazas, Michelle, Castro, Leyla Jael, Fiore, Nicola, Hellström, Margareta, Lazzeri, Emma, Leenarts, Ellen, Martinez Lavanchy, Paula Maria, Newbold, Elizabeth, Nurnberger, Amy, Plomp, Esther, Vaira, Lucia, van Gelder, Celia W G, & Whyte, Angus. (2022). Recommendations for a minimal metadata set to aid harmonised discovery of learning resources (1.0).](https://doi.org/10.15497/RDA00073)
- [Jesse Long, Lisa Curtin, Persistent Identifiers, NTL Guide to DOIs & ORCID iDs for DOT Researchers, National Transportation Library (2022)](https://transportation.libguides.com/persistent_identifiers)
- [Creative Commons Certificate for Educators, Academic Librarians and GLAM](https://certificates.creativecommons.org/cccertedu/)
