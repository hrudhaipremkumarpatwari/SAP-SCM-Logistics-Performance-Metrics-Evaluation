# KPI Measurement Cycle

```mermaid
flowchart TD
    A[Define KPI & Formula] --> B[Identify SAP Data Sources]
    B --> C[Collect Reporting Data]
    C --> D[Validate Completeness & Accuracy]
    D --> E[Calculate KPI]
    E --> F[Compare with Target]
    F --> G{Within Threshold?}
    G -- Yes --> H[Publish Scorecard]
    G -- No --> I[Investigate Root Cause]
    I --> J[Assign Corrective Action]
    J --> K[Review Result]
    K --> C
```

This cycle represents the control logic used in the Week 5 performance framework. KPI calculation is treated as part of a continuous management process rather than a one-time reporting activity.
