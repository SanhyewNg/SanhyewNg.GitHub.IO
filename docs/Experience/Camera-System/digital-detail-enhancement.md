---
icon: lucide/package-check
--- 

# Digital Detail Enhancement (DDE)

![Before and after DDE](./images/before-after-DDE.png "Before and after DDE")

## Overview

Developed algorithms to enhance fine details and edges in images while minimizing noise amplification.

## Responsibilities

* Designed edge enhancement filters
* Balanced sharpness vs noise trade-offs
* Tuned parameters for different imaging conditions

## Approach

* High-frequency boosting
* Edge-aware filtering
* Adaptive enhancement strength

### Enhancement Pipeline

```mermaid
flowchart LR
    A[Input Image] --> B[Edge Detection]
    B --> C[High-Frequency Extraction]
    C --> D[Adaptive Gain Control]
    D --> E[Enhanced Image]

    subgraph Control
        F[Noise Level Estimation]
    end

    F --> D
```

### Tech

`MATLAB` · `Filtering` · `Image Enhancement`

## Impact

* Improved perceived sharpness of images
* Enhanced fine textures and edges
* Maintained natural image appearance

