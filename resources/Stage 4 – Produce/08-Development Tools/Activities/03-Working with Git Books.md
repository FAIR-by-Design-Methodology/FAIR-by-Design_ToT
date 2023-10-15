---
title: Working with Git Books
author: Skills4EOSC T2.3
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Git
    - Git Books
    - MkDocs
---

# Working with Git Books

This activity promotes the use of Git books, leveraging HTML documents as the final output format for showcasing the Markdown files created during the production phase. It explores the use of automated workflows which have the capability of automatically converting the Markdown documents to HTML and uploading them to a free service where they are hosted as part of a publicly accessible web page.

## Activity duration

15 minutes

## Number of People that it can be Performed With

Any

## Goal of Activity

The goal of this activity is for participants to get acquainted with the concepts of a Git book through a hands-on experience working with the MkDocs framework. 

Special attention is also paid to automated workflows which allow for effortless live previewing of the rendered Markdown files comprising the produced learning objects.

## Materials

- Local clone of the previously forked `templates` repository.
- Necessary software tools already installed on the participants' workstations:
    - [GitHub Desktop](https://desktop.github.com/)
    - [Obsidian](https://obsidian.md/)

## Instructions

### Scenario Setup

After setting up the local environment, you are interested in ways to preview the produced content in its final output format. Following the FAIR principles, you have decided to publish the content as a Git book.

### Tasks Assigned to Participants

1. Make the necessary configuration changes on GitHub to enable the already defined workflows (which were disabled after forking). Allow read/write access to repository files for workflows both at the organization and repository levels.
    - Navigate to [GitHub](https://github.com).
    - Visit the landing page of your forked repository.
    - Enable the currently disabled workflows by choosing the `Actions` tab.
    - Visit the landing page of the previously created GitHub organization.
    - Using the Settings page, enable read/write access for GitHub workflows to child repositories.
    - Visit the landing page of your `templates` fork repository and verify that read/write access has indeed been enabled using the Settings menu.
2. Make local changes to some Markdown file.
    - Open Obsidian.
    - Select an arbitrary Markdown file from the left pane (e.g., `syllabus`).
    - Make some changes to the file.
    - Open GitHub Desktop and commit the changes, writing a title for the commit message and an optional commit description.
    - Push the changes to the upstream repository.
    - Navigate to the landing page of your forked repository on GitHub and verify that the workflow has been successfully executed by looking for a green checkmark next to the unique identifier for the last commit.
3. Enable free hosting for the Git book on GitHub.
    - On GitHub go to the settings for your forked repository.
    - In the pages section, select `gh-pages` as the source location for the files to be hosted as part of the web page.
    - Save the changes, wait for around 60 seconds, and then refresh the page.
    - Open the newly shown URL at the top of the page in a new browser window, verifying that the Markdown files have been automatically rendered to HTML representation and are publicly accessible.

### Trainer Guidance

The participants should already have both GitHub Desktop and Obsidian installed on their local machines before the start of the activity. As they are performing the activity, the trainer should provide additional instructions and help as needed, as well as promoting thinking-out-loud where anyone can share their findings with the rest of the group.

## Tips and Tricks

- Make sure that the settings that configuration settings that need to be changed are prominently displayed on a slide throughout the activity.

## Related Sources

- /

## Comments

- How did it go, were any issues encountered