```mermaid
erDiagram
  User ||--o{Relationship: ""
  
  User {
    id           integer
    email        string
    created_at   datetime
    updated_at   datetime
  }
  
  Relationship {
    id           integer
    followed_id  integer
    follower_id  integer
    created_at   datetime
    updated_at   datetime
  }
```

