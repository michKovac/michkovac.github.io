---
title: "Unconditional GAN-Based Generation of Stage-Specific Fundus Images for Augmenting Diabetic Retinopathy Screening"
authors:
- admin
- P. Macsik
- V. Kurilova
- O. Straka
- Z. Fellner
- J. Pavlovicova

date: "2026-03-18T00:00:00Z"
publishDate: "2026-05-30T00:00:00Z"
publication_types: ["article-journal"]

# Venue
publication: "*IEEE Access*, vol. 14, pp. 47800–47815"
publication_short: "IEEE Access"

abstract: "Class imbalance in diabetic retinopathy (DR) datasets, particularly the underrepresentation of advanced stages such as proliferative DR, limits classifier performance and necessitates specialized augmentation strategies. This study presents a data augmentation approach using StyleGAN2-ADA to generate stage-specific synthetic fundus images. Unlike conditional approaches requiring labels or segmentation masks, our method trains separate unconditional models for each DR severity stage, producing anatomically realistic images while preserving pathological characteristics. We propose a comprehensive evaluation framework comprising three components: quantitative assessment using distribution-based metrics (FID, KID, IS) and nearest-neighbor-based metrics (NN-SSIM, NN-PSNR); task-based evaluation through DR classification experiments with ConvNeXt Tiny, MobileNet V3 Small, and Xception architectures; and expert validation by three ophthalmologists assessing clinical plausibility. Classification experiments demonstrated improvements in overall accuracy, with ConvNeXt Tiny achieving 73.48% accuracy (+1.82% over baseline) when combining synthetic and classical augmentation. Inter-rater reliability analysis between the two most discriminating evaluators (κ = 0.723) confirmed the clinical realism of generated images. Our unconditional StyleGAN2-ADA approach provides a scalable, mask-free augmentation solution addressing class imbalance in fundus imaging datasets, potentially enhancing DR screening systems in resource-constrained clinical settings."
summary: "Unconditional StyleGAN2-ADA generates stage-specific synthetic fundus images to address class imbalance in diabetic retinopathy datasets, improving DR classification accuracy."

tags: [Medical Imaging, Retina, Fundus, Diabetic Retinopathy, GAN, StyleGAN2-ADA, Data Augmentation, Deep Learning, Synthetic Images]
featured: true

links:
  - type: paper
    name: IEEE Xplore
    url: https://ieeexplore.ieee.org/document/11441342

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
