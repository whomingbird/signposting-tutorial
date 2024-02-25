# signposting-tutorial

## Overview
* __Name:__ Tutorial on adding Signposting to GitHub pages
* __Description:__ This tutorial shows how to add Signposting to GitHub pages. It uses a simple GitHub page hosted in the `docs/` folder to create a sample project page, i.e., as learners could do with their own GitHub projects. As an example, it uses the dataset corresponding to the released project [TREC-doc-2-doc-relevance](https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance), a web-based interface to add document-to-document relevance assessments to pairs of documents retrieved from [TREC 2005 Genomics Track](https://trec.nist.gov/data/genomics/05/genomics.qrels.large.txt). 
* __Keywords:__ Signposting, GitHub pages

<img src="./icons/question.svg" width="16" height="16"/> __Questions__
* How can I add Signposting to GitHub pages?
* How can I include external metadata in my signposting?
* How

<img src="./icons/bullseye.svg" width="16" height="16"/> __Learning outcomes__
* Describe how Signposting can be embedded in GitHub pages
* Understanding of Signposting limitation of static content-delivery networks
* Use schema and Bioschemas validators

<img src="./icons/circle-check.svg" width="16" height="16"/> __Requirements__
* Brief understanding of Signposting
* Familiarity on how to use GitHub 
* Basic knowledge on how to use GitHub pages. More information at [GitHub Pages](https://pages.github.com/)
* Familiarity with HTML
* Knowledge of develop tools on a browser

<img src="./icons/hourglass-half.svg" width="16" height="16"/> __Time estimation__ 30 minutes

<img src="./icons/graduation-cap.svg" width="16" height="16"/> __Level__ Beginner / Introductory

<img src="./icons/calendar.svg" width="16" height="16"/> __Published__ 2024-02-07

<img src="./icons/pen-to-square.svg" width="16" height="16"/> __Latest modification__ 2024-02-07

<img src="./icons/scale-balance.svg" width="16" height="16"/> __License__ [CC-By 4.0](https://spdx.org/licenses/CC-BY-4.0)

<img src="./icons/code-compare.svg" width="16" height="16"/> __Version__ 1.0.0

<img src="./icons/fingerprint.svg" width="16" height="16"/> __Identifier__ [DOI:10.5281/zenodo.10629453](https://doi.org/10.5281/zenodo.10629453)

<img src="./icons/crosshairs.svg" width="16" height="16"/> __Citation__ Castro, LJ. (2024, February 7). Adding Bioschemas Dataset and ComputationalTool markup to GitHub pages. Zenodo. https://doi.org/10.5281/zenodo.10629453

## Learning experience

### Agenda
In this tutorial we will cover:
- [signposting-tutorial](#signposting-tutorial)
  - [Overview](#overview)
  - [Learning experience](#learning-experience)
    - [Agenda](#agenda)
    - [Prerequisites](#prerequisites)
    - [Creating this GitHub Page](#creating-this-github-page)
    - [Overview of the data](#overview-of-the-data)
    - [Adding Signposting markup](#adding-signposting-markup)
    - [Try it out](#try-it-out)
  - [What is next?](#what-is-next)
  - [Acknowledgements](#acknowledgements)

### Prerequisites

To follow this tutorial, you should already have experience with using GitHub, and be signed in to your GitHub account. See [Learn the basics of GitHub](https://docs.github.com/en/get-started/start-your-journey) as a refresher.

### Creating this GitHub Page

Let's start by forking [this repository](https://github.com/stain/signposting-tutorial) for your own purposes. Once forked, go to **Settings**

![Settings](./images/settings.png)

You will need to enable _Pages_ on your forked repository, and select **Deploy from a branch** using  **Branch:** `main`  and **Folder**: `docs/`. Then **Save** the changes. 

As this repo does have a gh-pages branch, it will use it. If such branch would not exist, GitHub would ask you to use the main branch to start the gh-pages one

![GitHub Pages](./images/pages.png)

In a matter of minutes, your site will be live. The pages corresponding to the examples used in this tutorial are available at [https://stain.github.io/signposting-tutorial/](https://stain.github.io/signposting-tutorial/)

![Published pages](./images/pages-published.png)

Do not forget to check out a local copy of your fork so you can make changes -- alternatively you may use the GitHub editor.

### Overview of the data



### Adding Signposting markup



### Try it out



## What is next?


## Acknowledgements
This tutorial is based on [bioschemas-ghpages-markup-tutorial](https://github.com/zbmed-semtec/bioschemas-ghpages-markup-tutorial), [bioschemas-github-markup-example](https://github.com/zbmed-semtec/bioschemas-github-markup-example) and [Adding schema.org to a GitHub Pages site](https://bioschemas.org/tutorials/howto/howto_add_github).

LJC has received fundings from the [German Research Foundation (DFG)](https://www.dfg.de/en) via the grant for NFDI4DataScience No. [460234259](https://gepris.dfg.de/gepris/projekt/460234259)

We use free SVG icons from [Font Awesone](https://fontawesome.com/)
