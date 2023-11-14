# Data model

```{mermaid}

erDiagram
    CMORVar ||--o{ MipVar : specifies

    CMORVar {
        string standard_name
    }

    MipVar {
        string spatial_info
    }
```