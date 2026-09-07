# KPI Framework

The Week 5 framework uses ten logistics KPIs selected to balance customer service, transportation efficiency, warehouse execution, inventory control and cost.

| KPI | Formula | Example Baseline | Target | Review |
|---|---|---:|---:|---|
| OTIF | Orders delivered on time and in full / total orders × 100 | 89% | 96% | Weekly / Monthly |
| Order Accuracy | Correct orders / total orders × 100 | 96.5% | 99% | Weekly |
| Inventory Turnover | Annualized COGS / average inventory value | 7.2x | 9.0x | Monthly |
| Truck Utilization | Actual load / available vehicle capacity × 100 | 70.3% | 93.75% | Per shipment / Weekly |
| Pick Accuracy | Correct picks / total picks × 100 | 97.2% | 99.5% | Daily / Weekly |
| Dock Turnaround | Departure time − arrival time | 110 min | 75 min | Daily |
| Stock-out Rate | Stock-out events / demand opportunities × 100 | 7.5% | 2.4% | Weekly |
| Freight Cost per Tonne | Total freight cost / tonnes shipped | ₹2,150 | ₹1,825 | Monthly |
| Order Cycle Time | Delivery completion time − order creation time | 3.6 days | 2.5 days | Weekly / Monthly |
| Inventory Accuracy | Correct system quantity records / counted records × 100 | 94% | 99% | Cycle count / Monthly |

## Framework Design

Each KPI is defined with six control elements:

1. **Business definition** — what the metric measures and why it matters.
2. **Formula** — exact numerator, denominator and unit.
3. **Data source** — ERP, TM, EWM, APO or reporting layer.
4. **Target / threshold** — expected level and escalation trigger.
5. **Owner** — role accountable for investigation and corrective action.
6. **Review frequency** — operational, weekly or management cadence.

## Weighted Composite Score

A weighted scorecard prevents the evaluation from depending on a single metric. Service KPIs receive higher weight, while transport, warehouse, inventory and cost indicators provide balance.

For a higher-is-better KPI:

`Attainment = min(Actual / Target, 1.0)`

For a lower-is-better KPI:

`Attainment = min(Target / Actual, 1.0)`

`Weighted Score = Attainment × KPI Weight`

The sum of all weighted scores gives the composite logistics score.

## Escalation Principle

A KPI below its defined threshold should trigger root-cause classification, owner assignment, corrective action and follow-up review. The framework is designed as a management-control process, not only a dashboard.
