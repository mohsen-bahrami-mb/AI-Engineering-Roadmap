```mermaid
graph LR

User --> Supervisor

Supervisor --> ResearchAgent

Supervisor --> CodingAgent

Supervisor --> DataAgent

ResearchAgent --> Supervisor
CodingAgent --> Supervisor
DataAgent --> Supervisor

Supervisor --> FinalAnswer
```