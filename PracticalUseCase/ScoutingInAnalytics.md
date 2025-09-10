~~~mermaid
flowchart TD
    subgraph "Initial Reconnaissance"
        direction TB
        I1["Analytics Spike"] --> I2["Pattern Detection"]
        I2 --> I3["System Mapping"]
        
        style I1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style I2 fill:#98FB98,stroke:#228B22,color:#000000
        style I3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Three Known Facts"
        direction TB
        F1["Fact 1: Traffic Pattern"] --> F2["Fact 2: Access Method"]
        F2 --> F3["Fact 3: Behavioral Indicators"]
        
        style F1 fill:#FFB6C1,stroke:#8B0000,color:#000000
        style F2 fill:#ADD8E6,stroke:#00008B,color:#000000
        style F3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Pattern Analysis"
        direction TB
        P1["Fact Selection"] --> P2["Confidence Assessment"]
        P2 --> P3["Pattern Integration"]
        P3 --> P4["Adaptive Reasoning"]
        
        style P1 fill:#DDA0DD,stroke:#4B0082,color:#000000
        style P2 fill:#F08080,stroke:#CD5C5C,color:#000000
        style P3 fill:#98FB98,stroke:#228B22,color:#000000
        style P4 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    I1 --> F1
    I2 --> F2
    I3 --> F3
    
    F1 --> P1
    F2 --> P2
    F3 --> P3
    
    P1 --> R1["Pattern Recognition"]
    P2 --> R1
    P3 --> R1
    
    subgraph "Result"
        direction TB
        R1 --> R2["Threat Assessment"]
        
        style R1 fill:#87CEEB,stroke:#4169E1,color:#000000
        style R2 fill:#FFB6C1,stroke:#8B0000,color:#000000
    end
~~~
