---
title: "Existing Markdown Materials Reuse"
author: "Skills4EOSC T2.3"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Software Tools
    - File Formats
    - Markdown
    - Content Reuse
---

# Existing Markdown Materials Reuse

As discussed in [Stage 2: Discover](../../Stage%202%20–%20Discover/03-Existing%20learning%20materials/03-Existing%20learning%20materials.md), discovering existing learning materials instead of writing from scratch is an important aspect of the FAIR-by-Design methodology. From the production perspective, reusing existing materials is similar to modifying the Markdown templates in the same way as if the material was written just now. This includes ensuring that the correct information is present in the Markdown header and that the relevant sections have been filled out, as discussed in the [Markdown syntax section](../09-Content%20Development/09-Markdown%20Syntax.md).

Before reusing existing content, careful attention needs to be paid to its original license, and whether it is compatible with the assigned license of the newly developed materials. Potential license incompatibilities can prevent the reuse of the discovered content in a new context. Furthermore, even if the licenses are compatible, attribution for the original content needs to be provided (recommended even if the original license is CC-0), crediting its original authors.

Since the discovered content can be in any file format, additional effort might be required to convert it to a Markdown representation. Additionally, it is worth mentioning that even if the content is available in Markdown, there are multiple Markdown flavors available today, some of which introduce specific formatting options (such as tab display, annotations, modal windows). These formatting options might not be compatible with the wider Markdown eco-system, including MkDocs, so it is best to use only basic Markdown formatting, ensuring compatibility with the widest set of tools.

## Learning Objectives

- Extend the learning content
- Define slides in open format

## Target Audience

- attendees of the FAIR-by-Design ToT live webinar

## Duration

60 mins

## Prerequisites

- Completed [Stage 3: Design](../../Stage%203%20–%20Design/04-Conceptualisation/04-Conceptualisation.md)
- Completed [09 - Content Development](../09-Content%20Development/09-Markdown%20Syntax.md)

## Learning Tools

- Training BBB room
- optional: Obsidian & Quarto

## Exercise: Reusing Existing Content

The goal of this exercise is to put to practical use the concepts learned from the previous stages regarding discovery, material reuse, licensing, attribution, and Markdown formatting. Having already discovered relevant material for reuse in Stage 2, while also performing a license compatibility check and defining attribution in Stage 3, we are now ready to incorporate the content according to the FAIR-by-Design Methodology.

Throughout the exercise we assume that you are writing a new course on Open Data and plan to reuse [Lesson 5: Planning for Open Data](https://github.com/opensciency/OpenData/blob/main/lessons/lesson5.md). The following steps will need to be performed:

- create a lesson plan
- create an activity
- create an assessment
- modify the existing content so that it is compliant to the provided Markdown templates

The questions bellow can act as a guide through the above steps.

1. Take a moment to scroll through the [document](https://github.com/opensciency/OpenData/blob/main/lessons/lesson5.md), skimming its content.
2. Is the assumption which was made regarding the content sound, and is it indeed possible to reuse this content in your learning unit? Where can you see its license?
3. Open the GitHub Desktop client and make sure that the local copy of the repository is up-to-date.
4. Open Obsidian. Our goal will be to make a copy of the `Learning Unit` directory, rename it to an appropriate name, download the original file, and systematically edit the necessary Markdown templates.

    - To copy the `Learning Unit` directory, expand the navigation tree on the left hand side in Obsidian, and right click on `Learning Unit`. Choose `Show in system explorer`.

        ![Obsidian - Show in Explorer](attachments/11-show-in-explorer.png)

    - Copy and paste the `Learning Unit` directory using your file manager, renaming it in the process. A good name is `Open Data`, but you are of course free to choose.

5. Download the found content into the newly created directory.

    - There are multiple ways in which a file can be downloaded from GitHub. In this case perhaps the simplest one is to choose the `Raw` option.

        ![GitHub - Raw Option for Downloading Files](attachments/12-raw-option-github.png)
    
    - In the window that opens simply right click and choose the option `Save as` or `Save Page As` (the available option depends on the browser being used).

        ![GitHub - Downloading the File to a Local Directory](attachments/13-save-as.png)

    - Save the file to the newly created directory in Step 4. Make sure to change its name and use an `.md` extension.

6. Go back to Obsidian and make sure that the file is visible and can be freely edited. 
7. Having completed the majority of the technical aspects, we are now ready to follow the Backwards Design Model. Since we already defined a lesson plan in the previous exercise, you can move it to the new directory. Verify that the content in it reflects the current scenario.
8. The next step is to define the assessment questions, according to the template provided in the `Assessment` directory.
9. Having defined the Assessments, describe the Activities that will be undertaken using the `assessment_template` in the `Assessment` directory.
10. We are now ready to start working on adapting the downloaded lesson file. 

    - Add the necessary metadata in the Markdown heading: `title`, `author`, `tags`.
    - Reorder the existing content, so that the `Learning Objectives`, `Target Audience`, `Duration`, `Prerequisites`, and `Learning Tools` sections are filled out. 
    - Go over the remaining content and make sure that all headings are defined appropriately. Note that MkDocs supports only one level 1 heading in a given document, so `#` can be used only once in the Markdown file.
    - Ensure that any linked images are visible. If they are not, download them to the `attachments` directory, and relink them in the document.
    - Ensure that images have an alt text.
    - Provide attribution to the original document.

## Next Steps

We have edited all of the required files for our new learning unit. The next step would be to verify the changes by uploading the files to GitHub and letting the automated workflow render them to HTML using MkDocs. We will cover this activity in the next section.

## Suggested Reading

- [Markdown Flavors](https://www.markdownguide.org/getting-started/#flavors-of-markdown)
- [Extended Markdown Syntax](https://www.markdownguide.org/extended-syntax/)
- [Extended Markdown Syntax for MkDocs – Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)