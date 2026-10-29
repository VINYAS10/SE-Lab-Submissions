# SE Lab 1 — Problem Statement #45

## Multi-Cloud Asset Cost Optimization Portal

This submission contains the required Lab 1 deliverables:

1. `Problem45_Requirements_Table.docx` — complete requirements table with exactly 5 FRs and 2 NFRs.
2. `Problem45_Requirements_Table.xlsx` — editable requirements table.
3. `Problem45_UML_Use_Case_Diagram.pdf` — UML use-case diagram with all actors, core use cases, `«include»`, and `«extend»`.
4. `Problem45_Use_Case_Flow.pdf` — one-page use-case flow specification for UC-04.

## Actors
- FinOps Analyst
- Cloud Administrator
- Notification Service

## Main Use Cases
UC-01 Ingest Cloud Billing CSVs; UC-02 Categorize Cloud Costs; UC-03 Analyze Asset Utilization;
UC-04 Identify Idle / Unattached Assets; UC-05 View Cost Optimization Dashboard;
UC-06 Configure Budget Thresholds; UC-07 Evaluate Budget Breach; UC-08 Dispatch Budget Breach Alert.

## UML Relationships
- UC-01 `«include»` UC-09 Validate Billing CSV
- UC-04 `«include»` UC-10 Calculate Monthly Savings Estimate
- UC-08 `«extend»` UC-07 Evaluate Budget Breach

The requirements and modeling follow the terminology and submission constraints in the provided Lab 1 handout and Problem Statement #45.
