Insurance Customer & Claims Analytics
Power BI | SQL Server | DAX | Power BI Service | Row-Level Security

Project Overview:
This project demonstrates the development of an end-to-end Business Intelligence solution for analyzing insurance policy, customer, premium, coverage, claims, and customer feedback data.

The solution was designed to help business stakeholders monitor insurance portfolio performance, understand customer and policy trends, analyze claims activity, and access relevant information through interactive Power BI reports.

The project covers the complete reporting workflow:

Source Data
     ↓
SQL Server
     ↓
Data Preparation & Modeling
     ↓
Power BI Report Development
     ↓
DAX Measures
     ↓
Row-Level Security
     ↓
Drill-through Analysis
     ↓
Power BI Service
     ↓
Published Dashboard

Business Problem:
- Insurance organizations need to monitor their customer and policy portfolios while maintaining visibility into premium performance, coverage values, claim activity, and customer experience.
- When this information is distributed across multiple datasets and reporting processes, stakeholders may face challenges in understanding overall performance, identifying claim trends, analyzing customer segments, and accessing detailed customer-level information.
- The objective of this project was to build an interactive Business Intelligence solution that brings together insurance policy, customer, claims, and feedback information into a centralized reporting environment.

Business Questions Answered:
Portfolio Performance
- How many customers and policies are included in the portfolio?
- What is the total premium value?
- What is the total coverage amount?
- How is the portfolio distributed across different policy types?
- How does the customer base vary by age and gender?

Claim Analysis
- How many claims have been submitted?
- What is the total claim amount?
- How are claims distributed across different claim statuses?
- Which policy types generate the highest claim activity?
- How does claim activity vary across the customer portfolio?

Customer Analysis
- What are the characteristics of customers across different policy types?
- Which customers have active policies or claims?
- How can stakeholders navigate from high-level portfolio information to individual customer details?

Customer Feedback
- What feedback has been received from customers?
- Can customer feedback be reviewed alongside customer and policy information?

Technical Implementation
Data Sources
- Insurance policy and claims data
- Customer feedback data
- SQL Server as the source environment
- Power BI for reporting and visualization

Row Level Security
Implemented Row-Level Security in Power BI to restrict report access based on user permissions.

The implementation demonstrates how different users can access only the data relevant to their assigned scope while using the same centralized report.

Drill Through Analysis
Implemented drill-through functionality to allow users to move from summary-level analysis to detailed customer or policy-level information.

Power BI Service
The report was published to Power BI Service to demonstrate the transition from report development to cloud-based consumption.

The implementation included:
- Publishing the Power BI report.
- Creating a dashboard in Power BI Service.
- Pinning relevant report visuals to the dashboard.
- Configuring and validating report access.
- Applying Row-Level Security to the published solution.

Key Features
- SQL Server data source integration
- Insurance portfolio analysis
- Customer and policy analysis
- Claims performance analysis
- Interactive Power BI report
- DAX-based KPI calculations
- Drill-through analysis
- Row-Level Security implementation
- Power BI Service deployment
- Power BI Service dashboard creation
- Customer feedback analysis
- Business-focused reporting
