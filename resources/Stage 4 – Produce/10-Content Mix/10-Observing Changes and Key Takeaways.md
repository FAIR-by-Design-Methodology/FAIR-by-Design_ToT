---
title: "Observing Changes and Key Takeaways"
author: "Skills4EOSC T2.3"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Software Tools
    - File Formats
    - Markdown
    - Git
    - Git Book
---

# Observing Changes and Key Takeaways

Having produced our very own learning unit, now is the time to verify that its visual appearance conforms to our expectation by viewing it directly in the Git book.

## Exercise: Observing Changes

The steps that we need to execute in order to have the content published on the already set up Git book are: 

- push the content to GitHub
- wait for the workflow publishing process to finish
- visit the public URL and browse the content

We will go through each of these steps in more details below.

1. Open GitHub Desktop. Enter a commit title and an optional commit message and commit the changes by clicking on the blue `Commit to main` button.
2. Once committed, make sure to upload the changes to GitHub by clicking on the blue `Push` button.
3. After uploading the files, the publishing workflow will automatically be started. Depending on various factors, its execution time can vary, but in most cases it should finish within 1-2 minutes. You can track its execution progress by visiting the landing page of your repository and waiting for the green checkmark to appear next to the latest commit ID.
4. Once the workflow has finished, visit the public URL of your Git book, as configured in the previous section. Browse around the new learning unit, verifying that everything is formatted as expected.
5. In case something is out of place, or you have spotted an error, go back to Obsidian, make the necessary changes, commit and push them again. The workflow will also be automatically executed in this case as well, creating an updated version of your Git book in a matter of minutes.

**Important Notice**: It is by design that lesson plans, activities, and assessments are not visible on the rendered Git book, as these documents, in their raw format, are solely targeted at trainers and not trainees which are expected to visit the web page of the Git book.

## Suggested Reading

- [Excluding Files in MkDocs](https://github.com/apenwarr/mkdocs-exclude)