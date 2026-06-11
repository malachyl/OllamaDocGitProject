---
title:	OllamaDocGitProject README  
author:	malachyl  
date:	2026-06-10
updated:	2026-06-10 
tags: 	[Reference, basic]
---


# OllamaDocGitProject README
<!-- If you update the document title, ensure you update the title in the metadata above to match -->
This is a documentation project in git to describe how to install, configure, and use Ollama to run Large Language Models (LLMs) on a local desktop or server.

## Guidance for topics
The project borrows the concept of topic types from Darwin Information Typing Architecture (DITA) model, so each markdown file has a type of Task, Concept, or Reference. As an author, you must code the markdown file type in the file metadata under tags. You also must apply type discipline in the file's content: for example, do not include numbered lists of instructions in a concept or reference type file.
Task type topics broadly follow the DITA layout by including a description of the purpose of the task, prerequisites, task steps, and (optionally) next steps.

In addition, the project implements a target audience capability level of basic, intermediate, or advanced: these attributes will drive the presentation on the knowledgebase website. Similar to the topic type, encode the audience level in the metadata under tags. In addition, ensure you use an appropriate level of readability for the intended audience, such as checking that the Flesch-Kincaid readability score is low in topics for a basic audience.

## Style guide
<!-- ToDo - reference style guide here -->
Pending a reference to the style guide....

Following the principles of modular content:
* Include metadata in every file:

        ---
        title:	OllamaDocGitProject README  
        author:	malachyl  
        date:	2026-06-10
        updated:	2026-06-10 
        tags: 	[Reference, basic]
        ---

* Have a single Heading Level 1 in each file. This acts as the topic title, so ensure it matches the title in the metadata (both when you create it and when you update it).
* As much as possible, keep to Heading Level 2 in the content. If you feel you need to use heading level 3, consider whether you could put the content in a new topic and reference it.
* Write to the simplified technical english standard.
* Address readers directly (second person, imperative), and use active voice at all times.


## File metadata
This project uses YAML Frontmatter for adding metadata, with three hyphens as delimiters. The front matter must start on the first line of the markdown file, with no preceding blank lines. For example:

        ---
        Title:	installing Ollama  
        Author:	malachyl
        Date:	June 10, 2026  
        tags: 	[Task, basic]
        ---
