---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Alignment of single-cell RNA-seq samples without over-correction using kernel
  density matching
subtitle: ''
summary: ''
authors:
- Mengjie Chen
- Qi Zhan
- admin
- Lili Wang
- Zhaohui Zheng
- Jinlin Miao
- Ping Zhu
- Yang I Li
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-16T09:59:29-05:00
featured: false
draft: false
doi: '10.1101/2020.01.05.895136'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-16T14:59:27.574858Z'
publication_types:
- 2
abstract: 'Single-cell RNA sequencing (scRNA-seq) technology is poised to replace bulk cell RNA sequencing for most biological and medical applications as it allows users to measure gene expression levels in a cell-type-specific manner. However, data produced by scRNA-seq often exhibit batch effects that can be specific to a cell-type, to a sample, or to an experiment, which prevent integration or comparisons across multiple experiments. Here, we present Dmatch, a method that leverages an external expression atlas of human primary cells and kernel density matching to align multiple scRNA-seq experiments for downstream biological analysis. Dmatch facilitates alignment of scRNA-seq datasets with cell-types that may overlap only partially, and thus allows integration of multiple distinct scRNA-seq experiments to extract biological insights. In simulation, Dmatch compares favorably to other alignment methods, both in terms of reducing sample-specific clustering, and in terms of avoiding over-correction. When applied to scRNA-seq data collected from clinical samples in a healthy individual and five autoimmune disease patients, Dmatch enabled cell-type-specific differential gene expression comparisons across biopsy sites and disease conditions, and uncovered a shared population of pro-inflammatory monocytes across biopsy sites in RA patients. We further show that Dmatch increases the number of eQTLs mapped from population scRNA-seq data. Dmatch is fast, scalable, and improves the utility of scRNA-seq for several important applications. Dmatch is freely available online (https://qzhan321.github.io/dmatch/).'
publication: '*bioRxiv*'
---

<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>
<div class='altmetric-embed' data-badge-type='medium-donut' data-badge-details='right' data-doi='10.1101/2020.01.05.895136'></div>
