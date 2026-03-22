--- 
icon: lucide/package-check
--- 

# AI Voice Assistant

## Overview

Built a real-time voice assistant with conversational memory and tool-based reasoning.


## Responsibilities

* Integrated STT (speech-to-text) and TTS (text-to-speech)
* Implemented conversational memory
* Enabled tool-based responses


## Architecture

```mermaid
flowchart LR
    A[Voice Input] --> B[STT]
    B --> C[Agent]
    C --> D[Tool Call]
    D --> C
    C --> E[TTS Output]
```


## Tech

`Whisper` · `OpenAI` · `TTS`


## Impact

* Enabled natural voice interaction
* Demonstrated real-time agent system capability
