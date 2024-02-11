```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/spa 
    activate server
    server-->>browser: [{ "content": "Hello world", "date": "2024-2-11" }, ... ]
    deactivate server
```
