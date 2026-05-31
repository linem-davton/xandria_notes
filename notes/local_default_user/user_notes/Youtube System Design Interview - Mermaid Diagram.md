---
title: Youtube System Design Interview - Mermaid Diagram
---

# Youtube System Design Interview

```mermaid {width=1013 align=left}
flowchart TD
    U[Users] --> CDN[CDN / Edge Cache]
    U --> LB[Load Balancer]

    LB --> API[API Gateway]
    API --> US[User Service]
    API --> VS[Video Metadata Service]
    API --> UP[Upload Service]
    API --> REC[Recommendation Service]
    API --> SEARCH[Search Service]
    API --> COM[Comment Service]

    UP --> OBJ[Object Storage / Blob Store]
    UP --> MQ[Message Queue]
    MQ --> TR[Transcoding Workers]
    TR --> OBJ
    TR --> TH[Thumbnail Generator]
    TH --> OBJ

    VS --> META[(Metadata DB)]
    US --> USERDB[(User DB)]
    COM --> COMDB[(Comment DB)]
    SEARCH --> IDX[Search Index]
    REC --> FEAT[(User Activity / Feature Store)]

    CDN --> OBJ
    SEARCH --> META
    REC --> META

    subgraph Analytics
        LOG[Logs / Events]
        PIPE[Stream Processing]
        DW[Data Warehouse]
    end

    API --> LOG
    CDN --> LOG
    LOG --> PIPE
    PIPE --> DW
    PIPE --> FEAT
```


## Talking points
- Upload path: upload → object storage → queue → transcoding → thumbnails
- Serving path: users → CDN → metadata/API → video chunks from cache/storage
- Core services: auth/users, metadata, search, recommendations, comments
- Scale concerns: hot videos, caching, async processing, partitioning, replication
- Reliability: retries, idempotency, monitoring, multi-region CDN





