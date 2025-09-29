flowchart TD
  A[Start] --> B{Decision}
  B -->|yes| C[Do thing]
  B -->|no| D[Do other thing]
  C --> E[Finish]
  D --> E
