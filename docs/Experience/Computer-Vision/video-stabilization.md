--- 
icon: lucide/package-check
--- 

# Video Stabilization & Motion Estimation

## Overview

Developed video stabilization techniques to reduce camera shake using motion estimation and smoothing.


## Responsibilities

* Estimated frame-to-frame motion
* Applied trajectory smoothing
* Warped frames to stabilize output


## Approach

* Optical flow / feature tracking
* Motion trajectory estimation
* Temporal smoothing

### Pipeline

```mermaid
flowchart LR
    A[Input Frames] --> B[Feature Tracking]
    B --> C[Motion Estimation]
    C --> D[Trajectory Smoothing]
    D --> E[Frame Warping]
    E --> F[Stabilized Video]
```


### Tech

`OpenCV` · `NumPy` · `Optical Flow`


## Impact

* Reduced visual jitter in videos
* Improved user experience and visual quality
* Demonstrated strong understanding of motion modeling


![Video Stabilization](./images/video-stabilization.jpg "Video Stabilization")
