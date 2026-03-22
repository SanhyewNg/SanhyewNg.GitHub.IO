--- 
icon: lucide/package-check
--- 

# Semantic Segmentation (Medical Imaging)

## Overview

Developed a semantic segmentation model for ocular diagnosis (LG staining) images to identify affected regions.


## Responsibilities

* Prepared and cleaned medical image datasets
* Designed and trained UNet-based architecture
* Evaluated segmentation performance using domain-specific metrics


## Approach

* 2D UNet architecture
* Data augmentation for limited datasets
* Pixel-wise classification

### Model Architecture

![Model Architecture](./images/UNet-architecture.png "Model Architecture")


### Training Pipeline

```mermaid
flowchart LR
    A[Raw Medical Images] --> B[Preprocessing]
    B --> C[Data Augmentation]
    C --> D[UNet Training]
    D --> E[Validation]
    E --> F[Model Output]
```

### Inference Pipeline

```mermaid
flowchart LR
    A[Input Image] --> B[Preprocessing]
    B --> C[Model Inference]
    C --> D[Segmentation Mask]
```


### Tech

`TensorFlow` · `Keras` · `UNet`


## Impact

* Enabled automated analysis of ocular conditions
* Reduced manual annotation workload
* Improved diagnostic consistency


### Sample Results

| Raw | Segmented |
|--------|------|
| ![LG-Staining-Eyeball Sclera-raw](./images/LG-Staining-Eyeball-Sclera-raw.png "LG-Staining-Eyeball Sclera-raw") | ![LG-Staining-Eyeball Sclera-segmented](./images/LG-Staining-Eyeball-Sclera-segmented.png "LG-Staining-Eyeball Sclera-segmented") |
| ![LG-Staining-Eyeball Sclera-raw](./images/LG-Staining-Eyelid-Margin-raw.png "LG-Staining-Eyelid-Margin-raw") | ![LG-Staining-Eyeball Sclera-segmented](./images/LG-Staining-Eyelid-Margin-segmented.png "LG-Staining-Eyelid-Margin-segmented") |

