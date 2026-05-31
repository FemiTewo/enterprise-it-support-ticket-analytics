# Power BI Dashboard

This folder contains the Power BI dashboard materials for the Enterprise IT Support Ticket Analytics project.

## Dashboard Purpose

The dashboard is designed to help support leaders monitor IT support performance, identify workload patterns, track SLA performance, understand customer satisfaction, and prioritize operational improvements.

## Planned Dashboard Pages

### 1. Executive Overview
This page summarizes the main support performance metrics, including total tickets, resolved tickets, open tickets, average resolution time, average CSAT score, and overall workload status.

### 2. Ticket Volume Analysis
This page shows how tickets are distributed by status, priority, support channel, product area, and issue type.

### 3. SLA Performance
This page focuses on SLA compliance and highlights areas where tickets may be missing expected service targets.

### 4. Customer Satisfaction
This page analyzes CSAT scores and customer sentiment to understand whether customers are satisfied after support interactions.

### 5. Operational Bottlenecks
This page highlights channels, product areas, and issue types with higher ticket volume or longer average resolution time.

## Key Metrics

The dashboard will track:

- Total tickets
- Resolved tickets
- Open tickets
- In-progress tickets
- On-hold tickets
- Average resolution time
- Average CSAT score
- Ticket volume by status
- Ticket volume by priority
- Ticket volume by channel
- Ticket volume by product area
- Ticket volume by issue type
- Customer sentiment distribution
- SLA performance

## Dataset Used

The dashboard uses the cleaned dataset exported from the Python analysis notebook:

```text
data/processed/cleaned_support_tickets.csv
