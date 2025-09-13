~~~mermaid
flowchart LR
    subgraph "Three-Layer Communication Pattern"
        A[Alice] --> L1["Layer 1
        Statistics Request"]
        L1 --> E1[Eve Handler 1]
        E1 --> L2["Layer 2
        Data Processing"]
        L2 --> E2[Eve Handler 2]
        E2 --> L3["Layer 3
        Final Transmission"]
        L3 --> B[Bob]
    end
    
    subgraph "Security Boundaries"
        S1["Security Layer 1
        • Authentication
        • Encryption
        • Validation"]
        S2["Security Layer 2
        • Data Sanitization
        • Access Control
        • Logging"]
        S3["Security Layer 3
        • Integrity Checks
        • Rate Limiting
        • Monitoring"]
    end
    
    L1 --- S1
    L2 --- S2
    L3 --- S3
    
    style A fill:#f9f,stroke:#333,color:#000
    style B fill:#9ff,stroke:#333,color:#000
    style E1 fill:#ff9,stroke:#333,color:#000
    style E2 fill:#ff9,stroke:#333,color:#000
    style L1 fill:#ddd,stroke:#333,color:#000
    style L2 fill:#ddd,stroke:#333,color:#000
    style L3 fill:#ddd,stroke:#333,color:#000
    style S1 fill:#dfd,stroke:#333,color:#000
    style S2 fill:#dfd,stroke:#333,color:#000
    style S3 fill:#dfd,stroke:#333,color:#000
~~~
