~~~xychart
xychart-beta
    title "Honeypot Activity During Methodology Transition"
    x-axis ["Traditional Detection", "Early Transition", "Mid Transition", "Late Transition", "Three Known Facts"]
    y-axis "Attack Attempts" 0 --> 100
    line "Total Attempts" [90, 80, 60, 30, 10]
    line "Successful Bypasses" [40, 35, 25, 15, 5]
    line "Unique Attack Vectors" [70, 60, 45, 30, 20]
~~~

~~~mermaid
flowchart LR
    subgraph "Surface Similarities"
        direction TB
        S1["Information Gathering"] --> S2["Pattern Analysis"]
        S2 --> S3["Structured Approach"]
        
        style S1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style S2 fill:#98FB98,stroke:#228B22,color:#000000
        style S3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    subgraph "Deeper Differences"
        direction TB
        D1["Systematic Fact Integration"] --> D2["Confidence-Based Reasoning"]
        D2 --> D3["Adaptive Problem Solving"]
        
        style D1 fill:#FFB6C1,stroke:#8B0000,color:#000000
        style D2 fill:#ADD8E6,stroke:#00008B,color:#000000
        style D3 fill:#DDA0DD,stroke:#4B0082,color:#000000
    end
    
    S1 -.->|"Missed by Comparison"| D1
    S2 -.->|"Missed by Comparison"| D2
    S3 -.->|"Missed by Comparison"| D3
    
    subgraph "Example: Pet Analysis"
        E1["Fact 1: Cats are cleanest pets"] --> E2["Fact 2: Dogs are man's best friend"]
        E2 --> E3["Fact 3: Gerbils don't use hamster wheels"]
        
        style E1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style E2 fill:#98FB98,stroke:#228B22,color:#000000
        style E3 fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    D1 --> E1
    D2 --> E2
    D3 --> E3
~~~
