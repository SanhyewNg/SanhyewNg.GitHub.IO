---
icon: lucide/package-check
---

# Non-Uniformity Correction (NUC)

![Before and after NUC](./images/before-after-NUC.png "Before and after NUC")

## Overview

Implemented algorithms to correct pixel-wise response variations in image sensors, improving image uniformity.


## Responsibilities

* Modeled sensor non-uniformity characteristics
* Developed correction algorithms using calibration data
* Integrated correction into image processing pipeline

## Approach

* Gain and offset correction per pixel
* Calibration using reference frames
* Optimization for computational efficiency

### Correction Pipeline

```mermaid
flowchart LR
    A[Raw Image] --> B[Gain Correction]
    B --> C[Offset Correction]
    C --> D[Corrected Image]

    subgraph Calibration Data
        E[Flat Field Image]
        F[Dark Frame]
    end

    E --> B
    F --> C
```

### Tech

`MATLAB` · `Signal Processing` · `Calibration Algorithms`

## Impact

* Significantly reduced fixed-pattern noise
* Improved visual consistency across frames
* Enhanced downstream processing reliability

