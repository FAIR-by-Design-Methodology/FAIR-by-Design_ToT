---
title: Internal QA check
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - QA
    - Review
author: Skills4EOSC T2.3
---

# Internal Quality Assurance

After the learning content has been fully developed and finalised, it is time to perform an initial internal Quality Assurance (QA). This will help ensure that all required documents are present, and that the structure, layout and content are valid. Both are needed before starting the publication process, as after publication the visibility of the repo will increase massively.  

## Learning Objectives
- create machine-readable metadata in syllabus
- generate overall license
- develop facilitation guide

## Target Audience
- attendees of the FAIR-by-Design ToT live webinar

## Duration
20 mins

## Prerequisites
Completed [Stage 3: Design](../../Stage%203:%20Design/)
Completed [11-Accessibility](../11-Accessibility/11-Checking_accessibility.md)

## Learning Tools
- Training BBB room
- Obsidian


## Who should perform the internal QA?

The internal QA can be performed by the same people that have done the development. If the work has been done collaboratively, it is preferred that the checks are done in such a way that the person that checks the learning unit is not the same person that developed the learning unit. This approach will improve the chance of catching some small bugs and errors. The overall check of structure and presence of all required elements should be done by the main collaborator. The checks of authorship, citation and similar should be done by all collaborators. 

## Required elements

The internal QA should start with an initial sweep that will check if the hierarchical structure of the learning content is correct and all learning units have been fully developed.

The easiest way to perform this step is to check the Table of Content (TOC) of the learner's notebook (Git Book) and see if the structure matches the design.

Next, an overall check should be done to identify if all required elements (files) are present. For these purposes the following checklist can be used:

- Root folder
    - [ ] Syllabus
    - [ ] Facilitation Guide
    - [ ] LICENSE
    - [ ] Feedback form
- resources folder
    - [ ] Section folders
    - [ ] Module folders
    - [ ] Learning Unit folders
- for each Learning Unit folder
    - [ ] Activities
    - [ ] Assessment
    - [ ] Learning Plan
    - [ ] Learning Content
    - [ ] Slide Deck (if instructor-led)

Note: We assume that you have not changed any of the rest of the files in the Templates repo that was cloned in the beginning. 

Once the structure is confirmed, the QA lead then continues with checking content and layout. 

- [ ] All required fields are present in Syllabus body
- [ ] Syllabus content is correct and clearly described
- [ ] Syllabus layout is correct in learners' notebook (HTML view)
- [ ] Syllabus accessibility check reports no issues
- [ ] All required fields are present in Syllabus metadata (MD file)
- [ ] Facilitation Guide describes the training setup (before, during and after)
- [ ] Correct LICENSE file is used

The QA lead then assigns different people to check different learning units.

### Learning Unit QA 

For each learning unit a thorough check of the learning content needs to be performed:

- [ ] Learning plan content adheres to template
- [ ] Learning plan is aligned with the information provided in the Syllabus
- [ ] Learning plan links to activities
- [ ] Learning content adheres to template
- [ ] Learning content layout is correct in learners' notebook (HTML view)
- [ ] Learning content is clearly written, easy to follow and understand
- [ ] Learning content is well aligned with the learning objectives defined in the plan
- [ ] Learning content accessibility check reports no issues
- [ ] All planned activities have description
- [ ] Planned activities are relevant for the unit content
- [ ] Activities description adhere to template
- [ ] Assessment quiz questions are relevant for the unit content
- [ ] Assessment quiz adheres to GIFT format
- [ ] Slide deck is aligned with the learning content
- [ ] Slide deck accessibility check reports no issues

Don't forget that this QA check, although most probably performed as self-assessment must still be done with a critical eye. The QA check should focus on all aspects of the produced learning materials, including the qualitative evaluation of the content.

For these purposes, the [Saide tool for reviewing course material](https://www.oerafrica.org/sites/default/files/course_design/8.%20Reviewing%20course%20materials%20tool%20.doc) can be used. The tool defines success criteria across a comprehensive set of elements including:

- Orientation
    - Introduction, aims and learning outcomes
    - Selection and coherence of content
- Helping learners learn
    - Presentation of content
    - View of knowledge and use of learners’ experience
    - Activities and feedback
    - Language
- Accessibility and Layout
    - Learning skills
    - Access devices (making it easy for the learners to find their way through the materials)
    - Visual aids (pictures, diagrams and cartoons)

### All hands check

All authors and collaborators should check the Syllabus to verify that their personal information is correct. 

Depending on the approach taken for authorship of different learning units, the metadata information in each file in the learning unit should also be double checked to confirm correct authorship information.

### Iterative changes

If any changes are needed then the newly produced versions should be double checked by the person that performed the initial QA assessment. 

## Summary

The main goal of the internal QA check is to ensure that all relevant learning materials are present and fully developed before going into the publishing step.

The QA should focus on both quantitative and qualitative aspects of the content: is it present, are the templates adhered to, as well as, is the content clear, comprehensive, well defined or maybe something is missing or needs to be changed and extended.

Once you are satisfied that all learning materials are to your liking you can proceed to publication. 

## Suggested Reading
- [How can we ensure good quality learning? (Quality assurance), OER Africa](https://www.oerafrica.org/35-how-can-we-ensure-good-quality-learning-quality-assurance)
