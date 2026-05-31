```mermaid
flowchart TD

User --> InputValidation

InputValidation --> PromptInjectionCheck

PromptInjectionCheck --> Moderation

Moderation --> LLM

LLM --> OutputValidation

OutputValidation --> FinalResponse
```