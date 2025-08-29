---
id: index
aliases: []
tags: []
title: Uganda Project Docs
---
```mermaid
flowchart TD
subgraph Implementation 1ab 
    Direction TD
    A[Borehole] --> B{Water Testing} 
end
  subgraph Implementation Phase 1C
Direction TD
    B -->C[Temporary Seal]
    C --> D[Hand Pump]
    D --> F[Concrete Seal]
end
subgraph Implementation Phase 2a
Direction TD
    F --> G[Borehole #2]
end 
Implementation 1ab--> Implementation 1c --> Implementation Phase 2a
```




