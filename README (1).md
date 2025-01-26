# Diagram.md

```mermaid

// Flowchart TD

A[Start Leaving for Work] --> B{Do I Have My Keys?}
B -->|Yes| --> C{Have I Made My Lunch?}
C -->|Yes| D[Start car]
D -->[END]
B --->|No| C[Go find them]
C ----> B
C -->|No| E[Go make it]
E -----> C


