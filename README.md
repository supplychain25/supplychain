# Supply Chain Performance Dashboard

## 1. Project Planning & Management

### Project Proposal
**Objective:**  
Develop an interactive Power BI dashboard to analyze key supply chain performance metrics, including sales trends, delivery performance, product insights, and customer segmentation. The goal is to support faster decision-making and provide a clearer understanding of operational efficiency.

**Scope:**  
- **Sales Performance:** Track total sales, profit, profit margin, and monthly sales trends.  
- **Shipping Performance:** Monitor delivery status, on-time delivery percentage, and shipping modes.  
- **Customer Insights:** Analyze customer segments and their contribution to overall performance.  
- **Regional Analysis:** Compare performance across regions, states, and cities.  
- **Product Analysis:** Evaluate product categories and identify high-performing items.  

---

### Project Plan

| Phase | Tasks | Duration | Milestone |
|-------|-------|---------|----------|
| 1 – Data Collection | Collect orders, customers, shipping, regions, and product data | Week 1 | Dataset finalized |
| 2 – Data Cleaning & Transformation | Fix missing values, remove duplicates, adjust data types | Week 2 | Clean dataset ready |
| 3 – Data Analysis & Metrics Creation | Build KPIs, trends, product and shipping metrics | Week 3 | Key insights identified |
| 4 – Dashboard Development | Build pages: Sales Overview, Shipping Performance, Product Analysis | Week 4 | First dashboard version |
| 5 – Review & Refinement | Improve visuals, verify data accuracy, optimize model | Week 5 | Final dashboard ready |
| 6 – Presentation & Documentation | Prepare documentation and present results | Week 6 | Project completed |

**Resources Used:**  
Power BI, Python

**Task Assignment & Roles:**  
- Data Collection: Ahmed Atta  
- Data Cleaning & Transformation: Ahmed Atta, Alaa Kelany  
- Data Analysis & KPI Creation: Neveen Mohamed, Ahmed Atta  
- Dashboard Development: Neveen Mohamed, Alaa Kelany  
- Review & Refinement: All team members  
- Presentation & Documentation: All team members

---

### Risk Assessment & Mitigation
- **Data quality issues:** Apply validation rules and cross-checks  
- **Slow dashboard loading:** Optimize DAX, remove extra columns, and build a lean data model  

---

### KPIs Included
- Total Sales, Total Profit, Profit Margin, Profit % of Sales  
- Average Order Value  
- Monthly Sales & Profit Trend  
- On-Time Delivery %  
- Sales by Category, Customer Segment, Region, State  

---

### Dataset Overview

| Column Name | Description |
|-------------|-------------|
| Order ID | Unique order identifier |
| Order Date | Date when the order was created |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method (Standard, Express, Same Day) |
| Customer ID | Unique customer identifier |
| Customer Name | Full customer name |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Country / City / State | Customer location details |
| Region | Geographic region |
| Product ID | Product identifier |
| Category / Sub-Category | Product classification |
| Sales | Sales amount |
| Quantity | Number of units |
| Delivery Status | On-time or late delivery |
| Month Name | Used for trend visualizations |
| Sales by Month | Monthly sales distribution |

---

## 2. Literature Review
- **Feedback & Evaluation:** Input from supply chain managers on key indicators  
- **Suggested Improvements:** Enhance filtering options, simplify navigation, improve layout  
- **Grading Criteria:** Accuracy, visualization quality, clarity of insights, dashboard usability  

---

## 3. Requirements Gathering
**Stakeholders:** Supply Chain Managers, Sales Ops, Warehouse Supervisors, Senior Management  

**User Stories:**  
- “As a supply chain manager, I want to track on-time delivery to understand shipping efficiency.”  
- “As a sales manager, I want to analyze sales trends to identify seasonal patterns.”  

**Functional Requirements:**  
- Display KPIs for sales, profit, and delivery performance  
- Analyze sales by region, product category, and customer segment  
- Provide filters for year, region, category, and shipping mode  
- Include interactive visuals and drill-down analysis  

**Non-Functional Requirements:**  
- Dashboard should load within 5 seconds  
- Consistent color palette and readable fonts  
- Simple and intuitive navigation  

---

## 4. System Analysis & Design
**Problem Statement:** Manual reporting made it difficult to track supply chain performance quickly.  

**Use Case Overview:**  
- Admin: Updates and maintains the data  
- Business Users: View and interact with the dashboard  
- Analysts: Build metrics, perform deep analysis  

**Software Architecture:**  
- Data stored in Excel/CSV  
- Cleaning & transformation in Power Query  
- Data modeling in Power BI  
- Visual layers: Sales Overview, Shipping & Delivery, Product & Market Analysis  

**ER Diagram Summary:** Orders, Customers, Products, Regions, Shipping Details  

**Logical & Physical Schema:**  
- Main relationships: Order ID – Customer ID – Product ID – Region  
- Primary keys and indexes defined to improve performance  

**Data Flow (DFD):** Source Files → Power Query → Data Model → Power BI Dashboard  

**UI/UX Guidelines:**  
- Blue shades for sales, green for delivery performance  
- Clear slicers for Year, Region, Segment  
- Clean layout with well-spaced visuals  

---

## 5. Deployment System & Integration
**Technology Stack:** Power BI Desktop, Power BI Service, Excel/CSV, Optional SQL  

**Deployment Diagram:** Data Source → Power BI Desktop → Power BI Service → End Users  

**Component Diagram:** Data Source Layer, Transformation Layer (Power Query), Data Model Layer, Visualization Layer  

---

## 6. Additional Deliverables
**Testing & Validation:**  
- Verified DAX measures  
- Checked relationships & slicer behavior  
- Ensured visuals respond correctly to filters  

**Deployment Strategy:**  
- Publish on Power BI Service  
- Set up scheduled refresh  
- Share with stakeholders with appropriate permissions
