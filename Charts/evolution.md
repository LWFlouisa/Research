~~~mermaid
flowchart TD
    subgraph "Initial Design"
        direction TB
        I1["Game Simulation
        • Lunar cycles
        • Survival mechanics"]
        I2["Matrix Structure
        • 3x3 grid
        • Fact storage"]
    end
    
    subgraph "Evolution"
        direction TB
        E1["Pattern Recognition
        • Demographic analysis
        • Relationship mapping"]
        E2["Research Capabilities
        • Investigation tools
        • Knowledge discovery"]
    end
    
    subgraph "Current State"
        direction TB
        C1["Research Platform
        • Pattern analysis
        • Demographic insights"]
        C2["Investigation Tool
        • Fact combination
        • Relationship discovery"]
    end
    
    I1 --> E1
    I2 --> E1
    E1 --> E2
    E2 --> C1
    C1 --> C2
    
    style Initial fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Evolution fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Current fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Data Collection"
        direction TB
        D1["Demographic Data
        • Population patterns
        • Behavioral trends"]
        D2["Recruitment Patterns
        • Social connections
        • Influence networks"]
    end
    
    subgraph "Pattern Analysis"
        direction TB
        P1["Initial Connections
        • Possible overlaps
        • Demographic matches"]
        P2["Pattern Validation
        • Confidence scoring
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
    
    D1 & D2 --> P1
    P1 --> P2
    P2 --> K1
    K1 --> K2
    
    style Data fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Patterns fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Knowledge fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~
