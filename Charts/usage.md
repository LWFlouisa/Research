~~~mermaid
flowchart TD
    subgraph "Fact Processing"
        direction TB
        F1["Three Verified Facts
        • Limited but certain
        • Domain-specific"]
        F2["Pattern Recognition
        • Relationship mapping
        • Connection analysis"]
    end
    
    subgraph "Pattern Discovery"
        direction TB
        P1["APT-Prisoner Connection
        • Historical patterns
        • Behavioral links"]
        P2["Healthcare-Cult Connection
        • Gaming addiction
        • Social patterns"]
    end
    
    subgraph "Knowledge Integration"
        direction TB
        K1["Pattern Storage
        • Relationship mapping
        • Confidence scores"]
        K2["Knowledge Base
        • Domain connections
        • Pattern networks"]
    end
    
    F1 --> F2
    F2 --> P1 & P2
    P1 & P2 --> K1
    K1 --> K2
    
    style Facts fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Patterns fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Knowledge fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Fact Processing"
        direction TB
        F1["Unrelated Facts
        • Independent data points
        • No known connection"]
        F2["Shuffling Mechanism
        • Random combination
        • Pattern generation"]
    end
    
    subgraph "Probability Assessment"
        direction TB
        P1["Manual Evaluation
        • Human judgment
        • Context analysis"]
        P2["Confidence Scoring
        • Probability assignment
        • Relationship strength"]
    end
    
    subgraph "Knowledge Integration"
        direction TB
        K1["Pattern Storage
        • Relationship mapping
        • Confidence levels"]
        K2["Knowledge Base
        • Domain connections
        • Pattern networks"]
    end
    
    F1 --> F2
    F2 --> P1
    P1 --> P2
    P2 --> K1
    K1 --> K2
    
    style Facts fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Probability fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Knowledge fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~
