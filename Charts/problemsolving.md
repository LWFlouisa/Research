~~~mermaid
flowchart TD
    subgraph "Hierarchical Decomposition"
        HD_Start["Complex Problem"] --> HD_Break["Break Down"]
        HD_Break --> HD_Small["Smaller Problems"]
        HD_Small --> HD_Solve["Solve Sequentially"]
        HD_Solve --> HD_Combine["Combine Results"]
        
        style HD_Start fill:#FFE4B5,stroke:#DAA520,color:#000000
        style HD_Break fill:#98FB98,stroke:#228B22,color:#000000
        style HD_Small fill:#87CEEB,stroke:#4169E1,color:#000000
        style HD_Solve fill:#DDA0DD,stroke:#9370DB,color:#000000
        style HD_Combine fill:#F08080,stroke:#CD5C5C,color:#000000
    end
    
    subgraph "Three-Known Facts"
        TK_Start["Complex Problem"] --> TK_Structure["Structure Three Facts"]
        TK_Structure --> TK_Analyze["Analyze Relationships"]
        TK_Analyze --> TK_Solve["Derive Solution"]
        
        style TK_Start fill:#FFE4B5,stroke:#DAA520,color:#000000
        style TK_Structure fill:#98FB98,stroke:#228B22,color:#000000
        style TK_Analyze fill:#87CEEB,stroke:#4169E1,color:#000000
        style TK_Solve fill:#DDA0DD,stroke:#9370DB,color:#000000
    end
    
    subgraph "Traditional AI"
        AI_Start["Complex Problem"] --> AI_Process["Process Elimination"]
        AI_Process --> AI_Generate["Generate Solution"]
        
        style AI_Start fill:#FFE4B5,stroke:#DAA520,color:#000000
        style AI_Process fill:#98FB98,stroke:#228B22,color:#000000
        style AI_Generate fill:#DDA0DD,stroke:#9370DB,color:#000000
    end
~~~

~~~mermaid
flowchart TD
    subgraph "Known Domain"
        KH["Hierarchical Knowledge"] --> KA["Clear Relationships"]
        KA --> KR["Fixed Structure"]
        
        style KH fill:#90EE90,stroke:#006400,color:#000000
        style KA fill:#ADD8E6,stroke:#00008B,color:#000000
        style KR fill:#DDA0DD,stroke:#4B0082,color:#000000
    end
    
    subgraph "Unknown Domain"
        UH["Three Known Facts"] --> UA["Flexible Analysis"]
        UA --> UR["Adaptive Structure"]
        
        style UH fill:#FFB6C1,stroke:#8B0000,color:#000000
        style UA fill:#98FB98,stroke:#228B22,color:#000000
        style UR fill:#87CEEB,stroke:#4169E1,color:#000000
    end
    
    KH -.->|"Transitions"| UH
    KR -.->|"Adapts"| UR
    
    subgraph "Example: Medical Diagnosis"
        M1["Symptoms"] --> M2["Patient History"]
        M2 --> M3["Treatment Options"]
        
        style M1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style M2 fill:#DEB887,stroke:#8B4513,color:#000000
        style M3 fill:#F0E68C,stroke:#BDB76B,color:#000000
    end
    
    subgraph "Example: Financial Analysis"
        F1["Market Trends"] --> F2["Risk Factors"]
        F2 --> F3["Investment Options"]
        
        style F1 fill:#FFE4B5,stroke:#DAA520,color:#000000
        style F2 fill:#DEB887,stroke:#8B4513,color:#000000
        style F3 fill:#F0E68C,stroke:#BDB76B,color:#000000
    end
    
    UH --> M1
    UH --> F1
~~~
