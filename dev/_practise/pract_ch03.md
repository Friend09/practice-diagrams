# Ch03: Visualize Application and User Flows

## Define Actors and participants

```mermaid
---
title: User Sign Up Flow
---

sequenceDiagram
    actor Browser
    participant Sign Up Service
    participant User Service
    participant kafka

    Browser->>Sign Up Service: GET /sign_up
    activate Sign Up Service
    Sign Up Service-->>Browser: 200 OK (HTML page)
    deactivate Sign Up Service

    Browser->>+Sign Up Service: POST /sign_up

```
