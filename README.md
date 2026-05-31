# Enterprise IT Support Ticket Analytics

## Project Overview

This project analyzes an enterprise IT support ticket dataset to identify operational patterns, SLA performance issues, customer satisfaction concerns, support bottlenecks, and opportunities to improve IT support performance.

The analysis focuses on ticket volume, ticket status, SLA performance, ticket priority, resolution time, customer sentiment, CSAT score, support channel, product area, issue type, and overall support workload.

The goal of the project is to turn raw support ticket data into clear business insights that can help support leaders improve service quality, reduce backlog, strengthen customer satisfaction, and make better operational decisions.

## Business Problem

IT support teams handle large volumes of customer and internal support requests across multiple channels, product areas, issue types, and priority levels. Without structured analysis, it can be difficult to understand:

- Which ticket categories create the most workload
- Whether urgent and high-priority tickets are being resolved faster
- Which channels or product areas create bottlenecks
- Whether customers are satisfied after tickets are closed
- Where support leaders should focus improvement efforts

This project uses Python-based data analysis to answer these questions and prepare the cleaned dataset for dashboard reporting.

## Dataset

The dataset contains 10,000 enterprise IT support tickets with fields related to:

- Ticket status
- SLA plan
- Priority
- Resolution time
- CSAT score
- Customer sentiment
- Support channel
- Product area
- Issue type
- Ticket metadata

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI
- GitHub

## Project Structure

```text
enterprise-it-support-ticket-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│       └── cleaned_support_tickets.csv
│
├── dashboard/
│
├── notebooks/
│   ├── 01_data_inspection_and_cleaning.ipynb
│   └── 02_ticket_sla_analysis.ipynb
│
├── reports/
│
├── sql/
│
└── README.md
Analysis Performed

The project includes the following analysis areas:

Data inspection and cleaning
Ticket status analysis
SLA performance analysis
Priority analysis
Customer sentiment analysis
CSAT score analysis
Support channel analysis
Product area analysis
Issue type analysis
Executive summary and recommendations
Key Findings
Overall Ticket Workload

The dataset contains 10,000 support tickets. Out of these, 5,014 tickets are resolved, meaning just over half of all tickets have been completed. However, there are still 997 open tickets, 2,020 tickets in progress, and 1,029 tickets on hold.

This shows that a significant portion of the support workload is still active or pending.

Resolution Time

The average resolution time across all tickets is 43.33 hours. This means that, on average, tickets take almost two days to resolve.

This indicates that there may be opportunities to improve ticket handling speed, escalation workflows, and operational efficiency.

Customer Satisfaction

The average CSAT score is 2.23 on a 0 to 5 scale. This is low and suggests that many customers may not be very satisfied with the support experience.

The analysis also shows that many tickets received a CSAT score of 0, which is a major concern and should be investigated further.

Priority Handling

Urgent tickets have the fastest average resolution time at 22.00 hours, followed by high-priority tickets at 30.37 hours. Medium-priority tickets take 41.80 hours on average, while low-priority tickets take the longest at 54.38 hours.

This suggests that the support team is generally prioritizing tickets correctly based on urgency.

Customer Sentiment

Neutral sentiment is the largest customer sentiment category, with 3,160 tickets. However, negative and very negative sentiment are also high, with 2,636 and 1,695 tickets respectively.

This suggests that customer experience needs improvement, especially around communication, resolution quality, and follow-up.

Support Channels

Ticket volume is fairly evenly distributed across all support channels. Email has the highest ticket volume with 2,048 tickets, followed closely by phone transcript with 2,037 tickets and web form with 2,011 tickets.

Chat tickets have the longest average resolution time at 46.02 hours, which may indicate a support bottleneck in the chat channel.

Product Areas

The analytics dashboard has the highest number of tickets with 1,486 tickets. Mobile app and API integration follow closely with 1,434 tickets each.

Mobile app has the longest average resolution time at 46.48 hours, followed by billing at 45.56 hours. These product areas may require deeper review.

Issue Types

Security concern has the highest number of tickets with 1,332 tickets, followed closely by how-to issues with 1,325 tickets.

How-to tickets take the longest to resolve at 44.80 hours, followed by bug tickets at 44.24 hours. This may indicate gaps in documentation, self-service resources, product usability, or technical troubleshooting workflows.

Recommendations
Reduce the active ticket backlog by prioritizing open, in-progress, and on-hold tickets.
Investigate low CSAT scores to understand why many customers are not satisfied after ticket closure.
Improve resolution quality, not just resolution speed.
Review chat support operations because chat has the longest average resolution time.
Strengthen documentation and self-service resources for how-to issues.
Review mobile app and billing support workflows because both product areas have longer resolution times.
Monitor security concern tickets closely because they represent the highest ticket volume by issue type and may indicate risk-sensitive customer problems.
Build a Power BI dashboard using the cleaned dataset so stakeholders can track ticket volume, SLA performance, resolution time, CSAT, sentiment, channel performance, and product-area performance in one place.
Final Conclusion

The analysis shows that the IT support team is generally prioritizing urgent and high-priority tickets correctly, but there are clear opportunities to improve SLA performance, customer satisfaction, and support efficiency.

The biggest concern is not only how quickly tickets are closed, but whether customers feel their issues were handled well. Improving SLA handling, reducing active backlog, strengthening support documentation, reviewing chat operations, and investigating low CSAT scores should be the main operational priorities.
Resolution time by product area
Ticket volume by issue type
Resolution time by issue type
