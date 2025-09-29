Documentazione prova corso DDD

```mermaid
flowchart TD
  A[Start] --> B{Decision}
  B -->|Yes| C[Do thing]
  B -->|No| D[Do other thing]
  C --> E[Finish]
  D --> E


---
config:
  layout: fixed
  look: neo
---
flowchart TD
    n1["Marmaidchart"] --> n2["What is this?"]
    n3["This is sample label"]
    n6["What is for?"]
    n1@{ icon: "mc:default", pos: "b"}
    n2@{ shape: rounded}
    n3@{ img: "https://static.mermaidchart.dev/whiteboard/default-image-shape.svg", h: 200, w: 200, pos: "b"}
    n6@{ shape: rounded}

