# Hiring-Funnel-Analytics-PowerBI

**Hiring Funnel & Pipeline Analytics Dashboard
Problem Statement**

Hiring data was available month-wise but lacked a consolidated view to track hiring progress, identify bottlenecks, and forecast closure timelines. Leadership needed a single source of truth to monitor open roles, drop-offs, and delays across the hiring lifecycle.

**Objective**
To build an end-to-end hiring analytics dashboard that:
Tracks hiring progression across stages
Identifies drop-offs and bottlenecks
Measures time spent in each stage
Excludes non-active roles for accuracy
Forecasts hiring completion timelines

**Data Overview**
Each record represents one job requisition with the following stages:
Approved
Sourcing Started
Interview Started
Interview Completed
Offered
Filled
_Additional attributes:_
Business Unit
Region
Role
Hiring Status

**Solution Design**

**1. Data Preparation**
Combined month-wise files using Power BI Folder Connector
Standardized date formats and column names
Created a single fact table at job-requisition level
**2. Data Modeling**
Fact Table: Hiring
Dimension Table: Stage_Lookup (Stage Name + Stage Order)
Used stage ordering to ensure correct funnel sequencing
**3. Key Analytics Implemented**
Hiring Funnel: Stage-wise job progression
Drop-off Analysis: % roles failing to move to next stage
Stage Aging: Average days spent in each hiring stage
Operational Accuracy: Excluded on-hold roles from funnel

**Key Insights Enabled**
Identified stages with maximum drop-offs
Highlighted interview and offer delays
Enabled proactive intervention by HR and recruiters

**Tools Used**
Power BI Desktop
Power Query
DAX (Measures & Calculated Columns)

**Outcome**
The dashboard transformed hiring reviews from static reporting to actionable pipeline optimization, enabling leadership to reduce time-to-fill and improve hiring efficiency.
