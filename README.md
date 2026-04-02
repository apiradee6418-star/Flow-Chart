```mermaid
flowchart TD
A[Start] --> B[Login]
B --> C{Check Data}
C -->|Yes| D[Process]
C -->|No| E[End]
D --> E
```
