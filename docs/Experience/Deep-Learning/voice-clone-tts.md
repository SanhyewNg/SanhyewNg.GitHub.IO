--- 
icon: lucide/package-check
--- 

# Voice Clone TTS

## Overview

Implemented a real-time voice cloning system based on SV2TTS architecture.


## Responsibilities

* Integrated open-source voice cloning model
* Processed speaker embeddings
* Generated natural-sounding speech


## Approach

* Speaker encoder
* Synthesizer (Tacotron-like)
* Vocoder

### Pipeline

![Voice Clone TTS training](./images/voice-clone-TTS.png "Voice Clone TTS training")  

![Voice Clone TTS](./images/voice-clone-TTS_1.png "Voice Clone TTS")


```mermaid
flowchart LR
    A[Speaker Audio] --> B[Speaker Encoder]
    B --> C[Embedding]
    C --> D[Synthesizer]
    D --> E[Vocoder]
    E --> F[Generated Speech]
```


## Tech

`PyTorch` · `TTS` · `SV2TTS`


## Impact

* Enabled realistic voice cloning
* Demonstrated multi-stage deep learning pipeline
* Expanded into generative audio systems

