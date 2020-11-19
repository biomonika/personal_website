---
abstract: Sex chromosomes present a genomic region which to some extent, differs between the genders of a single species. Reliable high-throughput methods for detection of sex chromosomes specific markers are needed, especially in species where genome information is limited. Next generation sequencing (NGS) opens the door for identification of unique sequences or searching for nucleotide polymorphisms between datasets. A combination of classical genetic segregation analysis along with RNA-Seq data can present an ideal tool to map and identify sex chromosome-specific expressed markers. To address this challenge, we established genetic cross of dioecious plant Rumex acetosa and generated RNA-Seq data from both parental generation and male and female offspring. We present a pipeline for detection of sex linked genes based on nucleotide polymorphism analysis. In our approach, tracking of nucleotide polymorphisms is carried out using a cross of preferably distant populations. For this reason, only 4 datasets are needed; reads from high-throughput sequencing platforms for parent generation (mother and father) and F1 generation (male and female progeny). Our pipeline uses custom scripts together with external assembly, mapping and variant calling software. Given the resource-intensive nature of the computation, servers with high capacity are a requirement. Therefore, in order to keep this pipeline easily accessible and reproducible, we implemented it in Galaxy – an open, web-based platform for data-intensive biomedical research. Our tools are present in the Galaxy Tool Shed, from which they can be installed to any local Galaxy instance. As an output of the pipeline, user gets a FASTA file with candidate transcriptionally active sex-linked genes, sorted by their relevance. At the same time, a BAM file with identified genes and alignment of reads is also provided. Thus, polymorphisms following segregation pattern can be easily visualized, which significantly enhances primer design and subsequent steps of wet-lab verification. Our pipeline presents a simple and freely accessible software tool for identification of sex chromosome linked genes in species without an existing reference genome. Based on combination of genetic crosses and RNA-Seq data, we have designed a high-throughput, cost-effective approach for a broad community of scientists focused on sex chromosome structure and evolution.
#author_notes:
#- Equal contribution
#- Equal contribution
authors:
- admin
- Z Kubat
- R Hobza
- B Vyskot
- E Kejnovsky.
#- Rahulsimham Vegesna
date: "2015-03-11T00:00:00Z"
doi: ""
featured: false
image:
  caption: 'Image credit: DANI ZEMBA AND MONIKA CECHOVA, PENN STATE'
  focal_point: ""
  preview_only: false
projects: []
publication: '*BMC Bioinformatics*'
publication_short: ""
publication_types:
- "2"
publishDate: "2017-01-01T00:00:00Z"
#slides: example
summary: Our pipeline presents a simple and freely accessible software tool for identification of sex chromosome linked genes in species without an existing reference genome. Based on combination of genetic crosses and RNA-Seq data, we have designed a high-throughput, cost-effective approach for a broad community of scientists focused on sex chromosome structure and evolution.
tags:
- Source Themes
title: Fully automated pipeline for detection of sex linked genes using RNA-Seq data
url_code: ""
url_dataset: ""
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4367819/pdf/12859_2015_Article_509.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

#{{% alert note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import #publication metadata into their reference management software.
#{{% /alert %}}

#{{% alert note %}}
#Click the *Slides* button above to demo Academic's Markdown slides feature.
#{{% /alert %}}

#Supplementary notes can be added here, including [code and #math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
