---
title: "RASMD: RGB and SWIR Multispectral Driving Dataset for Robust Perception in Adverse Conditions"

authors:
- Youngwan Jin
- admin
- Yagiz Nalcakan
- Incheol Park
- Sanghyeop Yeo
- Hyeongjin Ju
- Shiho Kim

# Journal publication (use the journal’s online-available date if you want; below is a safe placeholder).
date: "2025-10-28T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-29T00:00:00Z"

# Publication type (CSL).
publication_types: ["article-journal"]

# Publication name and optional abbreviated name.
publication: "*Information Fusion*"


# Abstract (short, web-friendly).
abstract: >
  We introduce **RASMD**, a large-scale multispectral driving dataset of **100,000** synchronized and pixel-aligned **RGB–SWIR** image pairs captured across diverse locations, lighting, and adverse weather (fog, rain, snow, glare, high contrast). RASMD includes benchmarks for **object detection** and **RGB↔SWIR translation**, showing that combining RGB and SWIR improves perception under challenging conditions.

# Summary (optional, for cards/previews).
summary: 100k paired RGB–SWIR images + benchmarks for object detection and RGB↔SWIR translation; improves robustness in adverse conditions.

tags:
- Dataset
- Autonomous Driving
- Computer Vision
- SWIR
- Multispectral
- Object Detection
featured: false

hugoblox:
  ids:
    arxiv: 2504.07603

links:
  - type: paper
    name: Journal (ScienceDirect)
    url: https://www.sciencedirect.com/science/article/abs/pii/S1566253525009340
  - type: website
    name: Project page
    url: https://yonsei-stl.github.io/RASMD/
  - type: dataset
    name: Hugging Face dataset
    url: https://huggingface.co/datasets/STL-Yonsei/RASMD
  - type: pdf
    name: arXiv PDF
    url: https://arxiv.org/pdf/2504.07603

# Featured image
# Add `featured.jpg/png` to this folder if you want a banner/thumbnail.
image:
  caption: "RASMD: Paired RGB–SWIR samples across varied scenes and weather (see project page)."
  focal_point: ""
  preview_only: false

projects: []

slides: ""
---

Add any **notes** here (e.g., BibTeX, extended results, or a teaser image from the project page).

- **Code/Usage:** see the dataset card for loaders and examples.  
- **Benchmarks:** object detection and RGB↔SWIR translation protocols are included on the project page and paper.
