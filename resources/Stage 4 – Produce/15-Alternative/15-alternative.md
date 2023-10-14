---
title: This MD stuff is nice, but it's not for me
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - File format alternative
author: Skills4EOSC T2.3
---

# MD Alternative

The use of MD file formats for the development of the learning content is a strong recommendation, but not a strict requirement of the FAIR-by-Design methodology. Although the use of MD entails lots of additional automated steps such as publishing to Zenodo and easy integration with the learning platform, you can still produce FAIR learning materials using other open file formats. In this part we will go through one alternative scenario that replaces the use of the Templates repository and MD file formats with Workplace and Microsoft Office Word open file format.

## Learning Objectives

- Adapt to using other file formats
- Assess pros and cons of alternative approach

## Target Audience

- attendees of the FAIR-by-Design ToT live webinar

## Duration

20 mins

## Prerequisites

Completed [12-Content Finalisation](../12-Content%20Finalisation/12-Content_finalisation.md)

## Learning Tools

- Training BBB room
- Browser

## Win some, lose some 

As discussed at the beginning of this stage, the use of markdown is recommended as it allows instructional designers to focus on content, and not worry much about the final layout of the learning materials as the produced GitBook already has a defined style that will be seamlessly replicated. This leads to development of uniform learning materials where the main focus and attention is put on the quality of the content. This approach alleviates many headaches of the produce and publish process such as:

- no need to follow special layout rules and styles to ensure uniform look and feel of the learning materials across learning units
- no need to test and fix any accessibility issues related to the choice of color palette or font style and size
- auto generation of the learners' notebook in the form of a Git Book with integrated multimedia content
- highly dynamic collaborative environment that can easily be extended to external collaborators
- very detailed version control that extended to the very content of each file
- automated workflow for publishing the learning materials to Zenodo and obtaining a DOI
- machine-readable metadata available
- ...

In addition, the level of reusability of the produced material is very high, as the content can be reused in an environment with a completely different layout styles and rules with no, to very little changes. Because when it comes to reuse, it is the content that matters, not the layout.

Switching to using DOCX files instead of MD files is going to **transfer the responsibility for all implemented and automated features to the instructional designers**. This means that the instructional designer will need to take care of:

- implementing uniform styling and layout
- ensuring the styling and layout choices are fully accessible according to WCAG 2.1
- seamless integration of multimedia in the learning content
- manual generation of the final learners content (preferably HTML to accommodate for integrated multimedia)
- transferring to a public collaborative environment before publishing to support external collaborators
- manual publication of the learning materials to Zenodo
- no machine-readable metadata available
- ...

## DOCX alternative setup

How to proceed if you want to work with Microsoft Office open file formats (docx, pptx) while developing the learning content avoiding the use of markdown?

1. Use the Skills4EOSC Workplace as an initial location for the internal development of the learning materials
    - note: workplace documents can not be shared with non project members
2. Recreate the hierarchical folder structure to logically organise your documents
3. Create a docx template which will act as an alternative for each md template file 
    - syllabus
    - facilitator guide
    - feedback form
    - for each learning unit
        - plan
        - content
        - activity description
        - note that quizzes must stay in their GIFT plaintext format for import to the learning platform
4. Copy all fields defined in each md template to the corresponding docx template
5. Style each docx template using the Skills4EOSC logo, color palette and funding information
6. Ensure the created templates are accessible
    - export to HTML
    - use a WCAG 2.1 checking tool
7. Distribute the templates in their right place in your hierarchical folder structure
8. Add the correct LICENSE plaintext file in the root of your folder structure

You are now ready to start developing the learning content using the same basic guidelines and principles as discussed previously.
Don't forget that you will need to export to HTML (or PDF if only static multimedia is used) and then double check for accessibility.
**Don't keep the exported HTML in the same folder tree as the editable content.** 

Once the internal QA is completed, you will need to **ensure that the correct final up-to-date version of the exported HTML is used for its publication on the learning platform** as this is now a fully manual process. 

When the final content is available on the course on the learning platform, it is time to put it into a public repository so that it can be offered for external collaboration:

1. Create a new repository on GitHub
    - or you can delete the MD stuff from the cloned template repository and replace it with the new content
2. Copy paste ALL files and folders from workplace to the repository
3. Commit and push the changes
4. Double check on GitHub that the repository is a cloned image of your initial workplace structure
5. Delete or archive the workplace content (this should not be used any longer as the GitHub repository took over this role)

**From now on, any changes in the learning materials must be done directly on the GitHub repository.**

We don't recommend using a GitHub repository for work with Office only files from the start as this will create a lot of conflicts and requests for conflict resolution and merging, especially when more people are working on the same document. GitHub looks at all Office files as binary objects and can not keep track of the changes done within the object as it does with md files. 

## I'm looking for yet another alternative, what now

You can choose any open file format instead of DOCX. Take care that at the moment Google file formats are not strictly considered as open, so this choice is not recommended as a viable option. 

The procedure would be very similar to the one described above, only a little bit adjusted to the format of your choice.

Sometimes other options, such as the development of SCORM based learning materials for an example, create more files in the place of a single md or docx file. In this case keep all of these files grouped together in a folder for easier building of the hierarchical logical structure. 

## What can not be considered as an alternative learning content

Developing only a slide deck with notes in the slides can not be considered as an alternative for the development of the learners' notebook. The main issue is that the slide notes can not convey the necessary level of information in a multi modal way. Their primary use is support for the trainers that give the presentation, not the learners that acquire the knowledge. 

## Summary

The use of Obsidian and/or markdown as the primary file format for developing learning content is only a strong recommendation and not a requirement of the FAIR-by-Design methodology.

Instructional designers are free to choose any open file format for the development of their learning content. Aiming to support easy reuse of the developed materials it is required that:

- a hierarchical logical structure is followed
- all developed multi-modal learning content is accompanied with the instructor kit
    - facilitation guide
    - feedback form
    - learning unit plans
    - activities description
    - assessment quizzes 

## Suggested Reading

- [Microsoft Make your content accessible to everyone](https://support.microsoft.com/en-us/office/make-your-content-accessible-to-everyone-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
- [Convert documents to HTML format Word 365](https://www.officetooltips.com/word/tips/convert_documents_to_html_format.html)
- [GitHub Create a repo](https://docs.github.com/en/get-started/quickstart/create-a-repo)
