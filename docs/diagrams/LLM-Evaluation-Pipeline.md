```mermaid
flowchart LR

Dataset --> TestCases

TestCases --> LLM

LLM --> Outputs

Outputs --> Metrics

Metrics --> Accuracy

Metrics --> Faithfulness

Metrics --> Relevance

Metrics --> Cost

Metrics --> Latency
```