```mermaid
flowchart LR

Documents --> Chunking

Chunking --> EmbeddingModel

EmbeddingModel --> VectorDB

UserQuery --> QueryEmbedding

QueryEmbedding --> SimilaritySearch

SimilaritySearch --> RetrievedChunks

RetrievedChunks --> Prompt

Prompt --> LLM

LLM --> FinalAnswer
```