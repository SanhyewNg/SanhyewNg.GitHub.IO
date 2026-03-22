--- 
icon: lucide/package-check
---  

# Live Interview Copilot

## Overview

Developed a real-time assistant to support users during interviews with contextual responses.


## Responsibilities

* Real-time transcription (Whisper)
* Context-aware response generation
* Memory summarization


## Approach

* Streaming transcription
* Context tracking
* Response generation

### Architecture

```mermaid
flowchart LR
    A[Live Audio] --> B[Whisper]
    B --> C[Context Memory]
    C --> D[LLM]
    D --> E[Suggested Answer]
```


## Tech

`OpenAI` · `Whisper` · `Desktop App`


## Impact

* Enabled real-time AI assistance
* Improved response quality under pressure
* Demonstrated low-latency LLM system design
