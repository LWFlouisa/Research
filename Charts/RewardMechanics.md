~~~mermaid
flowchart TD
    subgraph "Reward Processing"
        direction TB
        I["Iterative Processing
        • Individual rewards
        • Direct confidence updates
        • Manual control"]
        
        C["Chained Processing
        • Sequential rewards
        • Automated chains
        • Risk of over-correction"]
    end
    
    subgraph "Signal Types"
        direction TB
        S1["Competitive Signals
        • Independent goals
        • Relative performance"]
        
        S2["Cooperative Signals
        • Shared objectives
        • Mutual success"]
    end
    
    subgraph "Control Mechanisms"
        direction TB
        R["Probability Reset
        • Threshold: 0.9
        • Normalization
        • System stability"]
        
        M["Manual Override
        • User intervention
        • Correction chains
        • System balance"]
    end
    
    I --> S1 & S2
    C --> S1 & S2
    S1 & S2 --> R
    R --> M
    
    style Reward fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Signals fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Control fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Economic Experiments"
        direction TB
        E1["Increment Signals
        • Reward mechanisms
        • Positive feedback"]
        E2["Decrement Signals
        • Penalty mechanisms
        • Negative feedback"]
    end
    
    subgraph "Behavior Patterns"
        direction TB
        B1["Cooperative Behavior
        • Shared goals
        • Mutual benefit"]
        B2["Competitive Behavior
        • Individual goals
        • Relative success"]
    end
    
    subgraph "System Adaptation"
        direction TB
        S1["Probability Updates
        • Confidence scores
        • System learning"]
        S2["Behavior Adjustment
        • Strategy changes
        • Balance maintenance"]
    end
    
    E1 & E2 --> B1 & B2
    B1 & B2 --> S1 & S2
    
    style Economic fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Behavior fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style System fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Economic Model"
        direction TB
        E1["Middle Class Setup
        • Equal resources
        • Balanced incentives"]
        E2["Stress Conditions
        • Limited resources
        • Survival pressure"]
    end
    
    subgraph "Behavior Patterns"
        direction TB
        B1["Human Protection
        • Pet preservation
        • Resource allocation"]
        B2["Resource Management
        • Survival strategies
        • Priority setting"]
    end
    
    subgraph "System Outcomes"
        direction TB
        S1["Survival Patterns
        • Pet survival
        • Human sacrifice"]
        S2["Resource Distribution
        • Protection allocation
        • Sacrifice patterns"]
    end
    
    E1 --> E2
    E2 --> B1 & B2
    B1 & B2 --> S1 & S2
    
    style Economic fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Behavior fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style System fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Base System"
        direction TB
        B1["Equal Stats
        • HP = ATK = DEF"]
        B2["Economic Model
        • Resource Management
        • Behavior Patterns"]
    end
    
    subgraph "Lunar Effects"
        direction TB
        L1["Phase Impact
        • Behavioral Changes
        • Resource Allocation"]
        L2["Cycle Patterns
        • Long-term Effects
        • System Adaptation"]
    end
    
    subgraph "Behavioral Outcomes"
        direction TB
        O1["Resource Distribution
        • Protection Priority
        • Survival Strategies"]
        O2["System Adaptation
        • Learning Patterns
        • Behavioral Evolution"]
    end
    
    B1 --> L1
    B2 --> L1
    L1 --> L2
    L2 --> O1
    O1 --> O2
    
    style Base fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Lunar fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Outcomes fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~

~~~mermaid
flowchart TD
    subgraph "Lunar Cycle"
        direction TB
        NM["New Moon
        • Enemy survival ↑
        • Pet/player survival ↓"]
        FM["Full Moon
        • Pet/player survival ↑
        • Enemy survival ↓"]
    end
    
    subgraph "State Distribution"
        direction TB
        SD["Dynamic Adjustment
        • Survival probabilities
        • Resource allocation"]
    end
    
    subgraph "Behavioral Impact"
        direction TB
        BI["Resource Management
        • Protection strategies
        • Survival tactics"]
    end
    
    NM --> SD
    FM --> SD
    SD --> BI
    
    style Lunar fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000000
    style Distribution fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px,color:#000000
    style Impact fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000000
~~~
