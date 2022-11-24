```mermaid
sequenceDiagram
  participant U as Untracked
  participant S as Staged
  participant C as Committed
  U->>S: git add
  S->>C: git commit
  C-->>U: (Cambios en el fichero)
```
