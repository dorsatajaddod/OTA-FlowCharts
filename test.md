```mermaid
graph LR
    A[Start] --> B{Is it?};
    B -- Yes --> C[Do it];
    B -- No --> D[Don't do it];
    C --> E[End];
    D --> E;
