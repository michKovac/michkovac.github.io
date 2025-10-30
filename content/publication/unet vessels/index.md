---
title: "Retinal Vessel Segmentation by U-Net using Modification of the Phase Component of the DFT Image Spectrum"
authors:
- O. Straka
- F. Zubek
- admin
- J. Pavlovicova
- V. Kurilova
date: "2025-01-01T00:00:00Z"
publishDate: "2025-10-30T00:00:00Z"
publication_types: ["paper-conference"]

# Venue
publication: "*2025 International Symposium ELMAR (ELMAR)*, pp. 311–314"
publication_short: "ELMAR 2025"

abstract: "Retinal vessel segmentation plays a key role in diagnosing ocular and systemic diseases. While convolutional neural networks such as U-Net have proven effective, segmenting fine vessels remains challenging. In this study, we propose a novel augmentation method, where we interchanged the blue channel in the color image with a new enhanced vessels mask. The mask was created using the Phase Stretch Transform (PST) algorithm that modifies the phase frequency characteristic of the DFT spectrum of the image. The PST parameters were optimized via a genetic algorithm to maximize vessel visibility while suppressing noise. We evaluated our approach on the HRF database using a ResNet34-based U-Net architecture. The results demonstrate consistent improvements across all metrics, achieving an AUC of 98.60, an F1-score of 83.62, and an MCC of 80.17, surpassing several other methods. The results suggest that our approach effectively emphasizes vessel structures, particularly in low-contrast areas, without increasing model complexity."
summary: "U-Net vessel segmentation leveraging modifications to the DFT phase component."

tags: [Medical Imaging, Retina, Segmentation, DFT, U-Net, Fundus]
featured: false

links:
  - type: paper
    name: IEEE Xplore
    url: https://ieeexplore.ieee.org/abstract/document/11194040/

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
