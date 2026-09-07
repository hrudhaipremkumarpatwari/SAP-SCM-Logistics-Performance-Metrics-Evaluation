# Reporting Data Flow

```mermaid
flowchart LR
    ERP[SAP ERP\nOrders / Deliveries / Inventory] --> DATA[Validated Reporting Layer]
    TM[SAP TM\nFreight / Shipment Data] --> DATA
    EWM[SAP EWM\nWarehouse Execution Data] --> DATA
    APO[SAP APO / SCM\nPlanning Alerts / Exceptions] --> DATA
    DATA --> KPI[KPI Calculation Engine]
    KPI --> DASH[Scorecard / Dashboard]
    DASH --> OPS[Operational Review]
    DASH --> MGT[Management Review]
    OPS --> ACTION[Corrective Actions]
    MGT --> ACTION
    ACTION --> DATA
```

The diagram is conceptual. The precise technical path can vary by SAP landscape and may use operational analytics, BW, ODP/CDS extraction or another enterprise reporting layer.
