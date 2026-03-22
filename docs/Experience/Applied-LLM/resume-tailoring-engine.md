--- 
icon: lucide/package-check
---  

# Resume Tailoring Engine

## Overview

Generated job-specific resumes from raw input and job descriptions using structured prompting.


## Responsibilities

* Parsed PDF/DOC resumes
* Designed structured output prompts
* Integrated Gemini API


## Approach

* Prompt engineering for structured JSON output
* Context alignment with job descriptions
* Resume rewriting pipeline

### Pipeline

```mermaid
flowchart LR
    A[Resume Input] --> B[Parsing]
    B --> C[Job Description]
    C --> D[LLM Prompt]
    D --> E[Structured Output]
    E --> F[Final Resume]
```


## Tech

`Gemini API` · `Streamlit`


## Impact

* Automated resume optimization
* Improved job matching relevance
* Reduced manual editing effort
