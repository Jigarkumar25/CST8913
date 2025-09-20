```mermaid
flowchart TD
    C[Customer] -->|HTTPS| LB[Azure Load Balancer]

    LB --> RVM[React UI VM]
    LB --> FVM[Flask Backend VM]
    FVM --> DBVM[PostgreSQL VM]

    subgraph VNet[Azure VNet]
        RVM
        FVM
        DBVM
    end
``` 