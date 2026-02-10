# Hiring-Funnel-Analytics-PowerBI

**Hiring Funnel & Pipeline Analytics Dashboard
Problem Statement**

Hiring data was available month-wise but lacked a consolidated view to track hiring progress, identify bottlenecks, and forecast closure timelines. Leadership needed a single source of truth to monitor open roles, drop-offs, and delays across the hiring lifecycle.

**Objective**
To build an end-to-end hiring analytics dashboard that:
1. Tracks hiring progression across stages
2. Identifies drop-offs and bottlenecks
3. Measures time spent in each stage
4. Excludes non-active roles for accuracy

**Data Overview**
Each record represents one job requisition with the following stages:
1. Approved
2. Sourcing Started
3. Interview Started
4. Interview Completed
5. Offered
6. Filled
_Additional attributes:_
7. Business Unit
8. Region
9. Role
10. Hiring Status

**Solution Design**

_**1. Data Preparation**_
1. Combined month-wise files using Power BI Folder Connector
2. Standardized date formats and column names
3. Created a single fact table at job-requisition level
   
_**2. Data Modeling**_
1. Fact Table: Employee Hiring Data
2. Dimension Table: Stage_Lookup (Stage Name + Stage Order)
3. Used stage ordering to ensure correct funnel sequencing
   
_**3. Key Analytics Implemented**_
1. Hiring Funnel: Stage-wise job progression
2. Drop-off Analysis: % roles failing to move to next stage
3. Stage Aging: Average days spent in each hiring stage
4. Operational Accuracy: Excluded on-hold roles from funnel

**Key Insights Enabled**
1. Identified stages with maximum drop-offs
2. Highlighted interview and offer delays
3. Enabled proactive intervention by HR and recruiters

**Tools Used**
1. Power BI Desktop
2. Power Query
3. DAX (Measures & Calculated Columns)

**Outcome**

The dashboard transformed hiring reviews from static reporting to actionable pipeline optimization, enabling leadership to reduce time-to-fill and improve hiring efficiency.
