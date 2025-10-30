---
title: "U-Net for Small Object Segmentation: Detecting Retinal Exudates in Diabetic Retinopathy"
authors:
- admin
- P. Macsik
- J. Goga
- O. Straka
- J. Pavlovicova
date: "2025-01-01T00:00:00Z"
publishDate: "2025-10-30T00:00:00Z"
publication_types: ["paper-conference"]

# Venue
publication: "*2025 International Symposium ELMAR (ELMAR)*, pp. 297–300"
publication_short: "ELMAR 2025"

abstract: "Segmenting retinal exudates is a key step in the automated detection of diabetic retinopathy. This task is challenging due to the small size, low contrast, and sparse distribution of the lesions. This work proposes a deep learning approach based on the U-Net architecture, designed to segment exudates from retinal fundus images. The model is trained and evaluated on two publicly available datasets, E-Optha Ex and DDR, using a standardized preprocessing pipeline involving patch extraction and data augmentation. To address severe class imbalance, we compare training on complete datasets versus filtered datasets containing only images with exudates. Experimental results demonstrate that excluding non-pathological images improves segmentation performance, reaching up to 62% Dice coefficient on validation data. For the larger DDR dataset, training with a dynamic learning rate and the SGD optimizer enabled stable convergence over extended training. Our findings confirm U-Net’s effectiveness for small lesion segmentation and highlight the importance of dataset quality and composition."
summary: "U-Net approach for segmenting small retinal exudates in diabetic retinopathy fundus images."

tags: [Medical Imaging, Retina, Segmentation, Diabetic Retinopathy, Fundus]
featured: false

links:
  - type: paper
    name: IEEE Xplore
    url: https://ieeexplore.ieee.org/abstract/document/11193743

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
