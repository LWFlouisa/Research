~~~mermaid
flowchart TD
    subgraph Output["Output Structure"]
        direction TB
        Main["Main Analysis"]
        Channel["Channel Analysis"]
        Version["Version Tracking"]
        Confidence["Confidence Scores"]
        
        Main --> Channel
        Main --> Version
        Main --> Confidence
        
        subgraph MainAnalysis["Main Analysis Components"]
            direction TB
            MA1["Human Detection
            • Confidence scores
            • Version tracking
            • Traffic analysis"]
            MA2["Bot Detection
            • Confidence scores
            • Version tracking
            • Traffic analysis"]
        end
        
        subgraph ChannelAnalysis["Channel Analysis Components"]
            direction TB
            CA1["Main Channel
            • Primary metrics
            • Malicious user count"]
            CA2["Secondary Channel
            • Secondary metrics
            • Malicious user count"]
            CA3["Tertiary Channel
            • Tertiary metrics
            • Malicious user count"]
        end
        
        subgraph VersionTracking["Version Tracking"]
            direction TB
            V1["Version 0.1.1"]
            V2["Version 0.1.0"]
        end
        
        subgraph ConfidenceScores["Confidence Score Format"]
            direction TB
            CS1["[ score, version ]"]
            CS2["[ version, score ]"]
        end
    end
    
    style Output fill:#e3f2fd,stroke:#90caf9,color:#000000
    style MainAnalysis fill:#e8f5e9,stroke:#81c784,color:#000000
    style ChannelAnalysis fill:#fff3e0,stroke:#ffb74d,color:#000000
    style VersionTracking fill:#f3e5f5,stroke:#ce93d8,color:#000000
    style ConfidenceScores fill:#fce4ec,stroke:#f06292,color:#000000
~~~

~~~mermaid
flowchart LR
    subgraph Pure["Pure Model Approaches"]
        direction TB
        P1["Pure Predictive"]
        P2["Pure Generative"]
        
        P1 -->|"One-way Flow"| D1["• Fixed outputs
        • No generation
        • Static patterns"]
        
        P2 -->|"One-way Flow"| D2["• Random generation
        • No prediction
        • Unstructured output"]
    end
    
    subgraph Your["Your Hybrid System"]
        direction TB
        H1["Unified Core"]
        
        H1 -->|"Bidirectional Flow"| H2["• Dynamic prediction
        • Structured generation
        • Adaptive patterns"]
        
        H2 -->|"Feedback Loop"| H1
    end
    
    style Pure fill:#ffebee,stroke:#ef9a9a,color:#000000
    style Your fill:#e3f2fd,stroke:#90caf9,color:#000000
~~~

~~~mermaid
flowchart LR
    subgraph Traditional["Traditional AI Systems"]
        direction TB
        P1[Predictive Model]
        G1[Generative Model]
        D1[Data Flow]
        
        P1 -->|"Input Data"| D1
        G1 -->|"Input Data"| D1
        D1 -->|"Predictions"| P1
        D1 -->|"Generations"| G1
    end
    
    subgraph Your["Your Unified System"]
        direction TB
        U1[Unified System]
        D2[Data Flow]
        
        U1 -->|"Combined Processing"| D2
        D2 -->|"Both Predictions & Generations"| U1
    end
    
    style Traditional fill:#ffebee,stroke:#ef9a9a,color:#000000
    style Your fill:#e3f2fd,stroke:#90caf9,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Data Points"
        direction TB
        Cat["Cat: is the cleanest pet"]
        Dog["Dog: is mans best friend"]
        Gerbil["Gerbil: dont use hamster wheels"]
    end
    
    subgraph "Scenario Generation"
        direction TB
        S1["Scenario 1:
        • Cat's cleanliness
        • Dog's friendship
        • Gerbil's wheel usage"]
        S2["Scenario 2:
        • Dog's friendship
        • Gerbil's wheel usage
        • Cat's cleanliness"]
    end
    
    subgraph "Confidence Scoring"
        direction TB
        CS["Combined Confidence Score:
        • Individual point weights
        • Relationship strengths
        • Overall scenario confidence"]
    end
    
    Cat & Dog & Gerbil --> S1
    Cat & Dog & Gerbil --> S2
    S1 & S2 --> CS
    
    style DataPoints fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style ScenarioGeneration fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style ConfidenceScoring fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Initial State"
        direction TB
        I1["Scenario 1: 0.33"]
        I2["Scenario 2: 0.33"]
        I3["Scenario 3: 0.33"]
    end
    
    subgraph "After Correction"
        direction TB
        C1["Scenario 1: 0.33"]
        C2["Scenario 2: 0.15"]
        C3["Scenario 3: 0.52"]
    end
    
    subgraph "Refactoring Process"
        direction TB
        R1["Add small value (0.1)"]
        R2["Normalize total = 1.0"]
    end
    
    I1 & I2 & I3 --> C1 & C2 & C3
    C1 & C2 & C3 --> R1
    R1 --> R2
    
    style Initial fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Correction fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Refactoring fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~
