Documentazione prova corso DDD

```mermaid
flowchart TD
  A[Start] --> B{Decision}
  B -->|Yes| C[Do thing]
  B -->|No| D[Do other thing]
  C --> E[Finish]
  D --> E
