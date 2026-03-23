---
icon: lucide/package-check
---

# Camera & Sensor Test Bench

![Camera & Sensor Test Bench](./images/camera-sensor-test-bench.png)

## Overview

Developed a testing framework for evaluating camera sensors and image processing algorithms under controlled conditions.

## Responsibilities

* Designed test workflows for **sensor characterization**
* Implemented tools for **capturing and analyzing raw image data**
* Automated evaluation of image quality metrics


## System Architecture

```mermaid
flowchart TD
    A[Test Input Config] --> B[Sensor Capture]
    B --> C[Raw Image Data]
    C --> D[Processing Algorithms]
    D --> E[Metrics Evaluation]
    E --> F[Visualization Dashboard]

    subgraph Metrics
        M1[SNR]
        M2[Uniformity]
        M3[Sharpness]
    end

    E --> M1
    E --> M2
    E --> M3
```


### Key Features

* Controlled input scenarios (lighting, exposure, noise)
* Batch processing of test images
* Visualization tools for analysis


### Tech

`MATLAB` · `Image Analysis` · `Data Visualization`


## Impact

* Enabled systematic benchmarking of camera performance
* Accelerated development and validation of ISP algorithms
* Improved reproducibility of testing workflows

