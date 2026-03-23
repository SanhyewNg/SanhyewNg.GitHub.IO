---
icon: lucide/package-check
--- 

# Digital Noise Reduction (DNR)

![Before and after DNR](./images/before-after-DNR.jpg "Before and after DNR")

## Overview

Implemented noise reduction algorithms to improve image quality, especially under low-light conditions.

## Responsibilities

* Modeled noise characteristics of sensors
* Designed spatial and temporal denoising filters
* Optimized for performance and quality

## Approach

* Spatial filtering (e.g., smoothing, bilateral filtering)
* Temporal noise reduction across frames
* Noise-aware adaptive filtering

### Noise Reduction Flow

```mermaid
flowchart LR
    A[Input Image] --> B[Noise Estimation]
    B --> C{Filter Type}

    C -->|Spatial| D[Spatial Filtering]
    C -->|Temporal| E[Temporal Filtering]

    D --> F[Output Image]
    E --> F
```

### Tech

`MATLAB` · `Signal Processing` · `Image Filtering`

## Impact

* Reduced visible noise in challenging conditions
* Improved low-light performance
* Enhanced downstream computer vision reliability

