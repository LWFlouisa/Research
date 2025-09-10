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
