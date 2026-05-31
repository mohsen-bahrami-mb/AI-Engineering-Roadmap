```mermaid
flowchart LR

User[User Prompt]

User --> Tokenization

Tokenization --> ContextWindow

ContextWindow --> LLM

LLM --> Sampling

Sampling --> Output

Output --> UserResponse[Final Response]
```