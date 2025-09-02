---
id: index
aliases: []
tags: []
title: Uganda Project Docs
---

flowchart 
  subgraph Implementation 1ab 
    direction TB
      A[Borehole] --> B[Water Testing] 
end
  subgraph Implementation Phase 1C
      direction TB
        C[Temporary Seal]
        C --> D[Hand Pump]
        D--> F[Concrete Seal]
end
  subgraph Implementation Phase 2a
    subgraph A
     direction TB
      G[Borehole #2]--> H[Electrical Connection/Breaker]
      H-->I[Electric Pump]
end 
end 
B--> C
F-->G 





