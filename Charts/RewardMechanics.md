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
