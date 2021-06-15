---
title: "Mapping Inaccessible Areas Using Deep Learning based Semantic Segmentation of VHR Satellite Images with OpenStreetMap Data"
authors:
- admin
- Taehong Kwak
- Jaeung Jung
- Yongil Kim

date: "2021-05-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2021 International Symposium of Remote Sensing (ISRS)*
publication_short: 2021 International Symposium of Remote Sensing (ISRS) (Online) <span style="color:red;font-style:italic;font-weight:bold;">(Best Paper)</span>

abstract: Remote sensing is crucial for mapping and developing geospatial information of inaccessible areas. In particular, supervised classification or semantic segmentation of very high resolution (VHR) satellite images are used to extract key features such as buildings, roads, vegetation, and water bodies, but these methods are limited by the need for ground truth data, which is physically unobtainable for remotely located areas. To address this limitation, OpenStreetMap (OSM) data can provide ground truth labels that can be modified for use in VHR satellite images. In this study, Geoeye-1 VHR satellite imagery and refined OSM labels were acquired in urban regions situated in Pyeongyang, North Korea and are integrated into a feature pyramid network-based segmentation model with a pre-trained EfficientNet-B1 backbone. Building and road extraction yielded an F1-score of 0.8806 and 0.9580, respectively. Building and road segmentation results are combined with vegetation and waterbody features from spectral index thresholding to map four fundamental spatial data that are crucial for the development and updating of geospatial information in inaccessible urban areas.

tags:
- Urban Remote Sensing, Machine Learning, Satellite Image Processing
featured: false

links:
- name: Link
  # url:

image:
  caption: "Semantic segmentation of buildings and roads using Efficient-UNet"
  focal_point: ""
  preview_only: false
---
