# Overview of GitHub Documentation

Welcome! 👋 This documentation will guide you through setting up Local and [**GitHub**](https://github.com) repositories through the Command-Line Interface (CLI).

> :fontawesome-brands-github:{ .github } [**GitHub**](https://github.com) is a cross-platform hosting service, that allows developers to host and review code, manage projects and software releases, and collaborate with other developers.

## Intended Users

This documentation is targeted towards the following users:

- Beginner to intermediate developers who need to keep track of their source code using Git.

## Prerequisite Knowledge

The documentation assumes the following:

- No prior knowledge is required.

## Software Requirements

Before proceeding, ensure you have the following installed:

- [**Visual Studio Code**](https://code.visualstudio.com/download)

> Although the Git commands used will be on VS Code, they can also be done in your CLI outside of VS Code. Such as Terminal in Mac OS or Command Line in Windows.

## Procedures Overview

The main sections of the documentation are summarized below:

- **[Home](docs/index.md)**
- **[Git Basics](docs/Gitbasics.md)**
- **[Pushing Code With Git](docs/Pushingcodewithgit.md)**
- **[Troubleshooting](docs/TroubleShooting.md)**
- **[Glossary](docs/Glossary.md)**

## Notes and Warning Messages

Throughout the documentation, we will use message blocks to alert you to relevant information. 
Each possible message block, from most important to least important:

!!! danger
    Specifies actions that may cause an error or will cause the application to crash.

[comment]: <> (!!! failure)

[comment]: <> (    Specifies actions that may lead to unexpected behaviour.)

[comment]: <> (!!! bug)

[comment]: <> (    Specifies actions that may cause an error.)

!!! warning
    Specifies content that must be read before proceeding.

!!! Info
    Indicates additional information or tips.

!!! success
    Indicates what success looks like.












# Overview of Git User Documentation

Welcome! 👋 This documentation will guide you through setting up Local and [**GitHub**](https://github.com) repositories through the Command-Line Interface (CLI).

The goal of this documentation is to provide you with enough information to use Git and to build your very first remote repository.

These are the topics of this document

- Introduction to Git Installation
- Git Basics
- Pushing Code With Git
- Troubleshooting
- Glossary

## How We Collaborated Together

This user guide assignment occurred while our classes were completely held in-class. Our main form of communication was over Discord and in-person to brainstorm our ideas to get the basic structure for our markdown.

We used Git and GitHub to collaborate on the documentation. We divided the tasks between us by creating our own branches to keep our work separate until we were ready to merge to the master branch.

## How We Created Our Guide

Our guide was created using our knowledge from setting up and using Git in COMP 2340 Collaboration Tools. We referenced the official [Git](https://git-scm.com/doc) and [GitHub](https://docs.github.com/en) to supplement our experiential knowledge.

### Using MkDocs

We chose to use MkDocs as our static site generator as we liked the appearance of the [Material for MkDocs](https://github.com/squidfunk/mkdocs-material) theme, and the components provided by MkDocs.

### Using Markdown

This was the first time writing extensively in markdown for both of us. We learned how to style text using markdown from our COMM 2116 Business Communications 2 and developed our skills over the course of writing this documentation.

### Using VS Code

All the members of the group used VS Code to write our markdown files. We previewed the markdown using VS Code's built-in markdown preview, but we had to serve our guide with MkDocs to see the accurate rendering of our styles.

### Learning Best Practices For Web Writing

In addition to user guides, developers also write documentation for their peers and company stakeholders. Most of this writing exists in a web format. As such, it is important to construct documents that maximize readability on the web.

#### Readability

People read technical writing to retrieve information and not for pleasure (typically). We streamlined our writing to be clear, concise, and complete to provide the necessary information as effectively as possible.

We ensured that every procedure page included a conclusion to summarize what the reader would have accomplished from following the guide.

We used MkDocs' admonitions to highlight any information we wanted to stand out to the reader.

<figure>
  <figcaption>Specifies actions that may cause an error.</figcaption>
  <img
  src="docs/images/warning.png"
  alt="The danger admonition.">
</figure>

[comment]: <> (<figure>)

[comment]: <> (  <figcaption>Specifies actions that may lead to unexpected behaviour.</figcaption>)

[comment]: <> (  <img)

[comment]: <> (  src="docs/pages/images/admonitions/failure.png")

[comment]: <> (  alt="The failure admonition.">)

[comment]: <> (</figure>)

[comment]: <> (<figure>)

[comment]: <> (  <figcaption>Specifies actions that may cause an error.</figcaption>)

[comment]: <> (  <img)

[comment]: <> (  src="docs/pages/images/admonitions/bug.png")

[comment]: <> (  alt="The bug admonition.">)

[comment]: <> (</figure>)
<figure>
  <figcaption>Specifies content that must be read before proceeding.</figcaption>
  <img
  src="docs/images/important.png"
  alt="The warning admonition.">
</figure>
<figure>
  <figcaption>Indicates a tip.</figcaption>
  <img
  src="docs/images/tip.png"
  alt="The info admonition.">
</figure>
<figure>
  <figcaption>Indicates what additional information looks like.</figcaption>
  <img
  src="docs/images/note.png"
  alt="The success admonition.">
</figure>

#### Chunking

Given the nature of our topic, we expected lengthy informative pages, which can be challenging for readers to follow. To address this, we used subheadings and figures to guide our readers.

We opted for a navigation style (from MkDocs) that displays subheadings as nested links. This enables our readers to assess the relevance of the material and navigate to a particular section if desired.

#### Tone

This documentation is written for users who need a clear guide to using Git and setting up a GitHub repository.

- It is intended for beginner to intermediate developers who want to keep track of their source code.

 We have chosen a casual tone, as if we were explaining to a colleague, and have minimized the use of jargon to avoid confusing anyone new to coding. If we include any specialized terminology, we provide a hyperlink to an external resource for further explanation.

## Conclusion

This documentation captures our understanding of Git/Github. Writing about the topic was a bit tedious, as we had to repeat the same Git commands multiple times to ensure that the user sees the file changes. Nevertheless, it presented an opportunity for us to practice writing clear instructions for our intended audience.

This project tested our group's ability to communicate. We maintained an open line of communication throughout and regularly updated each other on our progress. Through solid teamwork, we were able to adhere to a common style guide.

Thank you for your interest in our Git Documentation. We hope it can serve as a useful reference for our readers and for ourselves in future projects.

This document was built on: [Material for MkDocs](https://github.com/squidfunk/mkdocs-material)
