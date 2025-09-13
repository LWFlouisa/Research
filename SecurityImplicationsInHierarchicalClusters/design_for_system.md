~~~mermaid
flowchart TD
    subgraph "Hierarchical Cluster Network"
        direction TB
        S1["Central Node
        • Offline Processing
        • Statistical Analysis
        • Learning Control"]
        
        subgraph "Cluster Layer 1"
            N1["Node 1
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
            N2["Node 2
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
            N3["Node 3
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
        end
        
        subgraph "Cluster Layer 2"
            N4["Node 4
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
            N5["Node 5
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
            N6["Node 6
            • Data Processing
            • Pattern Recognition
            • Local Learning"]
        end
        
        subgraph "Learning Process"
            L1["Statistical Evaluation
            • Pattern Analysis
            • Knowledge Integration
            • System Learning"]
            L2["Knowledge Base
            • Learned Patterns
            • System Understanding
            • Adaptive Rules"]
        end
        
        S1 -->|"Secure Channel 1"| N1
        S1 -->|"Secure Channel 2"| N2
        S1 -->|"Secure Channel 3"| N3
        S1 -->|"Secure Channel 4"| N4
        S1 -->|"Secure Channel 5"| N5
        S1 -->|"Secure Channel 6"| N6
        
        N1 & N2 & N3 & N4 & N5 & N6 -->|"Statistical Data"| L1
        L1 -->|"Learned Information"| L2
        L2 -->|"Updated Rules"| S1
        
        style S1 fill:#f9f,stroke:#333,color:#000
        style N1,N2,N3,N4,N5,N6 fill:#9ff,stroke:#333,color:#000
        style L1 fill:#ff9,stroke:#333,color:#000
        style L2 fill:#dfd,stroke:#333,color:#000
    end
    
    style Hierarchical fill:#f5f5f5,stroke:#666,color:#000
~~~
