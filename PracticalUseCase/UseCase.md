~~~mermaid
flowchart TD
    subgraph "Information Types"
        direction TB
        I1["Code Name"] --> I2["Unofficial Name"]
        I2 --> I3["Geographic Location"]
        
        style I1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style I2 fill:#98FB98,stroke:#228B22,color:#000000
        style I3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Fact Processing"
        direction TB
        F1["Fact Selection"] --> F2["Confidence Assessment"]
        F2 --> F3["Pattern Integration"]
        F3 --> F4["Adaptive Reasoning"]
        
        style F1 fill:#FFB6C1,stroke:#8B0000,color:#000000
        style F2 fill:#ADD8E6,stroke:#00008B,color:#000000
        style F3 fill:#87CEEB,stroke:#4169E1,color:#000000
        style F4 fill:#DDA0DD,stroke:#4B0082,color:#000000
    end
    
    subgraph "Example: Entity Analysis"
        E1["Fact 1: Code Name"] --> E2["Fact 2: Unofficial Name"]
        E2 --> E3["Fact 3: Geographic Location"]
        
        style E1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style E2 fill:#98FB98,stroke:#228B22,color:#000000
        style E3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    I1 --> E1
    I2 --> E2
    I3 --> E3
    
    F1 --> E1
    F2 --> E2
    F3 --> E3
    
    E1 --> R1["Pattern Recognition"]
    E2 --> R1
    E3 --> R1
    
    subgraph "Result"
        direction TB
        R1 --> R2["Entity Identification"]
        
        style R1 fill:#87CEEB,stroke:#4169E1,color:#000000
        style R2 fill:#FFB6C1,stroke:#8B0000,color:#000000
    end
~~~
