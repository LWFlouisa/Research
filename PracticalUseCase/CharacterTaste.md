~~~mermaid
flowchart TD
    subgraph "Social Media Post"
        direction TB
        S1["Character Preference"] --> S2["Game Knowledge"]
        S2 --> S3["Personal Interest"]
        
        style S1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style S2 fill:#98FB98,stroke:#228B22,color:#000000
        style S3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Pattern Analysis"
        direction TB
        P1["Fact 1: Character Choice"] --> P2["Fact 2: Game Context"]
        P2 --> P3["Fact 3: Behavioral Pattern"]
        
        style P1 fill:#FFB6C1,stroke:#8B0000,color:#000000
        style P2 fill:#ADD8E6,stroke:#00008B,color:#000000
        style P3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Three Known Facts Integration"
        direction TB
        F1["Fact Selection"] --> F2["Confidence Assessment"]
        F2 --> F3["Pattern Integration"]
        F3 --> F4["Adaptive Reasoning"]
        
        style F1 fill:#DDA0DD,stroke:#4B0082,color:#000000
        style F2 fill:#F08080,stroke:#CD5C5C,color:#000000
        style F3 fill:#98FB98,stroke:#228B22,color:#000000
        style F4 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    S1 --> P1
    S2 --> P2
    S3 --> P3
    
    P1 --> F1
    P2 --> F2
    P3 --> F3
    
    F1 --> R1["Pattern Recognition"]
    F2 --> R1
    F3 --> R1
    
    subgraph "Result"
        direction TB
        R1 --> R2["Behavioral Analysis"]
        
        style R1 fill:#87CEEB,stroke:#4169E1,color:#000000
        style R2 fill:#FFB6C1,stroke:#8B0000,color:#000000
    end
