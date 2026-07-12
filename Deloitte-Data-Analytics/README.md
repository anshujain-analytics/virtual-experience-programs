# Deloitte Data Analytics Virtual Experience (Forage)

## Overview

Completed Deloitte Australia's Data Analytics Virtual Experience Program on Forage.

The program focused on solving real-world manufacturing and HR analytics problems using Tableau and Excel.

---

## Skills Demonstrated

- Tableau Dashboard Development
- Data Cleaning
- Calculated Fields
- Excel Functions
- Data Analysis
- Business Insights
- Manufacturing Analytics
- HR Analytics

---

# Task 1 — Manufacturing Downtime Analysis

## Business Problem

Daikibo Industries collected telemetry data from four manufacturing plants to identify:

- Which factory experienced the highest machine downtime
- Which machine types contributed most to production downtime

## Tools

- Tableau

## Dashboard

Dashboard created using:

- Calculated Field
- Interactive Filters
- Bar Charts

### Key Findings

- Daikibo Factory Seiko experienced the highest downtime.
- Laser Welder machines generated the maximum downtime.
- Laser Cutter machines were the second highest contributor.

### Business Recommendation

- Prioritize preventive maintenance for Laser Welders.
- Increase monitoring of equipment at the Seiko factory.
- Schedule predictive maintenance to minimize production interruptions.

---

# Task 2 — Gender Pay Equality Analysis

## Business Problem

Analyze employee equality scores across factories and classify departments according to pay equality.

## Tool

- Microsoft Excel

## Excel Formula

```excel
=IF(OR(C2>20,C2<-20),"Highly Discriminative",
IF(OR(C2>10,C2<-10),"Unfair","Fair"))
