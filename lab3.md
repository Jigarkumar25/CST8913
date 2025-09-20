flowchart TD
    C[Customer] -->|HTTPS| LB[Azure Load Balancer / App Gateway]

    LB --> RVM[VM: React UI (Nginx/Apache)]
    LB --> FVM[VM: Flask Backend (Gunicorn + Nginx)]
    FVM --> DBVM[VM: PostgreSQL Database]

    subgraph Azure VNet
        RVM
        FVM
        DBVM
    end

    style DBVM fill:#fdd
    style FVM fill:#dfd
    style RVM fill:#ddf
