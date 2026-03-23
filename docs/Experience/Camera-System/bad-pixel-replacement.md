---
icon: lucide/package-check
--- 

# Bad Pixel Replacement (BPR)

![Before and after BPR](./images/before-after-BPR.png "Before and after BPR")

## Overview

Designed methods to detect and replace defective pixels in image sensors.

## Responsibilities

* Identified dead, hot, and stuck pixels
* Developed interpolation-based correction methods
* Integrated real-time correction strategies

## Approach

* Threshold-based detection
* Neighborhood interpolation
* Adaptive replacement strategies

### Bad Pixel Handling Flow

```mermaid
flowchart TD
    A[Raw Image] --> B[Detect Bad Pixels]
    B --> C{Pixel Type}

    C -->|Dead Pixel| D[Neighbor Interpolation]
    C -->|Hot Pixel| E[Threshold Correction]
    C -->|Stuck Pixel| F[Adaptive Replacement]

    D --> G[Corrected Image]
    E --> G
    F --> G
```

### Tech

`MATLAB` · `Image Processing`

## Impact

* Eliminated visual artifacts caused by defective pixels
* Improved perceived image quality
* Increased robustness of camera output


