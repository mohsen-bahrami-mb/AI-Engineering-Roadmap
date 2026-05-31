```mermaid
graph TD

User --> Agent

Agent --> Reasoning

Reasoning --> Decision

Decision --> Tool1[Search Tool]
Decision --> Tool2[Database Tool]
Decision --> Tool3[API Tool]

Tool1 --> Observation
Tool2 --> Observation
Tool3 --> Observation

Observation --> Agent

Agent --> FinalAnswer
```