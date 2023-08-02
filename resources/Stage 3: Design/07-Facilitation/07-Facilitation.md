---
title: Instructional design and facilitation
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Instructor kit
    - Folder structure
    - Special files
author: Skills4EOSC T2.3
---

# Instructional design and facilitation

We already looked at some of the facilitation documents that are part of the instructor kit such as the activity details description. In this section we outline all parts of the instructor kit. We then discuss the organisation of all materials in a logical folder structure and introduce a few additional supporting elements needed for reuse and co-creation.  

## Learning Objectives
- Extend the instructor kit
- Structure learning materials
- Gather supporting elements

## Target Audience
- attendees of the FAIR-by-Design ToT live webinar

## Duration
25 mins

## Prerequisites
Completed [06 - Learning Unit Development](../06-Learning%20unit%20development/06-LearningUnitDevelopment.md)

## Learning Tools
- Training BBB room
- Browser

## The Instructor Kit

The main goal of the instructor kit is to support the trainers and instructors in the delivery of the learning materials.
It is also essential for high quality reusability of the learning materials by other trainers and/or instructional designers. 

The complete instructor kit consists of learning materials that are developed and used to support the learning process, but are not directly visible by learners. These include the following items:

- learning unit plan
- activity details
- quiz question banks
- quiz strategies
- facilitation guide
- feedback questions

Most of the items were already introduced and discussed in [06 - Learning Unit Development](../06-Learning%20unit%20development/06-LearningUnitDevelopment.md). Here we will only focus on the last documents: the facilitation guide and the feedback questions.

### Facilitation Guide

As the syllabus represents the learner's view of the learning materials, the facilitation guide is a document that represents the trainers view and aims to enable a smooth and efficient training. Thus the guide aims to help with the general activities regarding the organisation of the training, what needs to be done before, during and after the training, how to setup the training environment, prepare any props and materials, etc. 

A well defined facilitation guide should include the following elements:

- what to do 
	- before
	- during
	- after the training
- where are all of the materials that should be used during the training
    - digital materials location
    - physical resources and equipment needed
        - e.g. projector
        - e.g. activity resources such as card decks
        - etc.
- how to prepare the materials beforehand
    - e.g. something needs to be written on flip charts
- how to prepare the learning environment
    - room layout and any other specifics (e.g. name tags, sign-in sheet, etc.)
    - in case of an online training this includes preparation of the virtual room, providing access, sending out or publishing reading materials, etc.

In the case of a summative or common quiz strategy it can contain this information as well.

For best visibility, the guide should also contain shortcuts to all activities planned. However, any specific details and notes should be available in the learning unit plan.

### Feedback questions

At the end of the learning process you should gather feedback from the learners so that they can provide feedback on what worked well and what should be improved in the training and learning materials. For these purposes a set of feedback questions should be drafted. The feedback can be gathered by enabling the learners to answer the questions using different modalities:

- physically by filling out a feedback sheet
- digitally using a feedback form created on the learning platform or using some other survey system

An example Training Evaluation form is presented in the next subsection. A similar evaluation form can be created using the feedback tool in the Skills4EOSC platform. 

Do not forget to set the following characteristics of the defined feedback used for training evaluation:

- availability from - to
- anonymous
- no multiple submissions
- show analysis page (for transparent review of the results) 

#### Training Evaluation Form
In Skills4EOSC we strive to provide high quality training and continuous improve our training activities. 
To be able to achieve that your feedback is very important to us. 

Please take a moment of your time to fill out the evaluation of the [insert training title]. It will only take a minute.

##### Training rating
Overall, the training provided was
- Excellent
- Very good
- Good
- Fair
- Poor

##### Training aspects rating
Let us know what was your experience regarding different training aspects:

|                                                     | Strongly disagree | Disagree | Neutral | Agree | Strongly agree |
|-----------------------------------------------------|-------------------|----------|---------|-------|----------------|
| I achieved the learning objectives.                 |                   |          |         |       |                |
| The training was clear and easy to follow.          |                   |          |         |       |                |
| The learning materials were clear.                  |                   |          |         |       |                |
| The learning content was relevant.                  |                   |          |         |       |                |
| The time allotted for the training was well chosen. |                   |          |         |       |                |
| The trainers were well prepared.                    |                   |          |         |       |                |
| The training activities were relevant.              |                   |          |         |       |                |

##### Acquired knowledge rating
How would you rate your level of knowledge on the topic before and after the training.

|                                     | None | Newbie | Basic | Advanced | Expert |
|-------------------------------------|------|--------|-------|----------|--------|
| My skills level before the training |      |        |       |          |        |
| My skills level after the training  |      |        |       |          |        |

##### Insights
In your opinion 

- the most useful part of the training is [free text]
- the least useful part of the training is [free text]
- the training could have been improved by [free text]

### Activity

Take a look at the [feedback form](https://learning.skills4eosc.eu/mod/feedback/view.php?id=36) available for this training. We will ask you fill it out later on.

## Logical organisation

All of the introduced documents that create the full set of learning materials should be organised in a logical tree structure in a clear, meaningful way to support

- potential reusers that will quickly find their way around
- automated publishing of the main learning content for learners (more on this later)

The logical structure that must be followed is as follows:

- Root folder
	- resources
		- attachments
			- contains all media files integrated in the syllabus and facilitator guide
		- Feedback
			- feedback questions file
		- (optional level) 01 Section
			- (optional level) 01 Module	
				- 01 Learning Unit
					- Activities
						- 01 activity details file
						- ...
						- N activity details file
					- Assessment
						- quiz question bank for this learning unit file
						- (optional) strategy for this quiz
					- attachments
						- contains all media files integrated in this learning unit files
					- learning content file(s)
					- slide deck file
					- learning unit plan file
				- ...
				- N Learning Unit  
		- syllabus file
		- facilitator guide file
	- README file
	- LICENSE file
	- CITATION file
	- CODE_OF_CONDUCT file

### Activity

Take a look at the logical organisation of the learning materials for this training [FAIR-by-Design ToT](https://github.com/FAIR-by-Design-Methodology/FAIR-by-Design_ToT).


## Machine-readable metadata

To complete the full set of learning materials and abide by the FAIR principles that require that the metadata be both human and machine readable, the fields from the RDA minimal metadata schema need to be filled out in a machine-readable format.

As this information has been stored in the syllabus, it is recommended that the machine-readable format is also stored in the header of the syllabus file so that both versions are found in one place making it easier to keep in sync. How to enter this information in the syllabus file will be presented in the learning units that follow.

## Supporting elements

There are a few supporting elements that makeup the learning materials set. In addition to the ones that are required for the technical implementation of the publishing workflow (to be discussed later), the following files are necessary to be defined by the instructional designers:

- license
	- this is a text oriented version of the CC license of your choice. You can find a list of all text license 4.0 files at https://creativecommons.org/2014/01/07/plaintext-versions-of-creative-commons-4-0-licenses/. You just need to choose the one based on your license decision you made in [04 Conceptualisation](../04-Conceptualisation/04-Conceptualisation.md).
- citation
	- the structure of this file is a machine readable description of how your learning materials should be cited based on the [Citation File Format - CFF](https://citation-file-format.github.io/). You will learn how to fill out this file in the Publish stage
- code of conduct
	- the purpose of this document is to define the rules of play when working in a collaborative environment. It is typically defined using a template that supports ope collaboration. The details on how to use the template are provided in the Publish stage.
- readme
	- think of the content of this file as the landing page for other trainers and instructional designers that seek to reuse your materials. So provide them with a meaningful description and information on how to do this. 

## Summary

Using the defined logical organisation of all learning materials files you are now ready to start producing your own learning content. 

It is imperative that you follow the rules of the logical organisation if you are planning to automate your publishing process based on the workflow provided in this training. 

## Suggested Reading
- [Francesca Di Donato, Lottie Provost, Tiziana Lombardo, Michela Vignoli, Stefanie Pohle, Erzsébet Tóth-Czifra, Yin Chen, & Emilie Blotière. (2022). TRIPLE Training Toolkit (3.0). Zenodo. https://doi.org/10.5281/zenodo.7309919](https://doi.org/10.5281/zenodo.7309919)
- [Best Feedback Forms For Training Sessions: 6 Templates](https://quenza.com/blog/feedback-form-training/)
- [Code of Conduct](https://en.wikipedia.org/wiki/Code_of_conduct)
- [Make a README](https://www.makeareadme.com/)
- [CFF] (https://citation-file-format.github.io/about/)