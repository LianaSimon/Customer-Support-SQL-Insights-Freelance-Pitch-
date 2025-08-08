# Customer-Support-SQL-Insights-Freelance-Pitch


## 📁 Dataset: customer_support_tickets.csv

This project analyzes customer support ticket data using SQL to uncover trends, issue breakdowns, and performance insights. It aims to demonstrate SQL proficiency and data storytelling in a real-world business context.


## 📦 Data Import & Exploration

### 1. Dataset Import

🔧 SQL Tool Used:

MySQL Workbench


📥 How the Dataset Was Imported:

Used the Table Data Import Wizard in MySQL Workbench to load customer_support_tickets.csv into a table named customer_support_tickets.


<img width="978" height="541" alt="image" src="https://github.com/user-attachments/assets/335a1c39-3239-4821-8569-24becd5d95c6" />


### 2. Data Understanding

Based on the uploaded customer_support_tickets.csv, here is a quick summary of the key columns and structure:


🔑 Key Columns Identified:

| Column Name    | Description                                |
|----------------|--------------------------------------------|
| TicketID       | Unique identifier for each ticket          |
| CustomerName   | Name of the customer                       |
| IssueType      | Type of issue reported                     |
| Priority       | Ticket urgency (Low, Medium, High, Urgent) |
| Status         | Ticket status (Open, In Progress, Closed)  |
| DateCreated    | Date the ticket was created                |
| Country        | Customer's country                         |




#### 📌 b) Are there any missing or duplicate records?

✅ Missing Value Check (SQL):
📌 Insight: This query will return the number of missing values per column. Ideally, all should be 0.

<img width="978" height="402" alt="image" src="https://github.com/user-attachments/assets/8b0186ce-bcbe-4fa7-b180-31d5b4f810e4" />


#### 🔁 Duplicate Check (by TicketID):
📌 Insight: If this query returns rows, those TicketIDs are duplicated and need review.

<img width="978" height="292" alt="image" src="https://github.com/user-attachments/assets/264e1948-dfcb-44aa-8b4f-93559c775aac" />



📌 c) Query to Preview First 10 Rows:


<img width="978" height="369" alt="image" src="https://github.com/user-attachments/assets/4d31cd3b-ab6a-424d-90f5-be6204a893f2" />


#### ✅ 3. Ticket Volume Analysis

🔹 Total Number of Tickets


<img width="978" height="248" alt="image" src="https://github.com/user-attachments/assets/d0fc3ca5-5552-48b3-bc8e-a6a17bc228e1" />



🔹 Tickets Currently “Open” or “In Progress”


<img width="978" height="268" alt="image" src="https://github.com/user-attachments/assets/36a7cc5e-1b81-4c10-a1ac-74753099e984" />



#### ✅ 4. Issue Type Breakdown

🔹 Most Frequent Issue Type

<img width="978" height="341" alt="image" src="https://github.com/user-attachments/assets/f0775666-774c-40b5-9bb7-208a9dcb0455" />


🔹 Count of All Issue Types (Descending)

<img width="978" height="354" alt="image" src="https://github.com/user-attachments/assets/74bfb03c-2804-4bf0-805e-52d5f5a0523e" />



#### ✅ 5. Priority & Status Insights

🔹 Tickets Marked as “High” or “Urgent”

<img width="978" height="351" alt="image" src="https://github.com/user-attachments/assets/dfca2b9e-3f5a-43cd-9d18-d6e8538df2a0" />


🔹 Unresolved Tickets in Each Priority Level

<img width="978" height="279" alt="image" src="https://github.com/user-attachments/assets/cb224e5f-800d-490d-b08a-9f15249bdd3d" />


#### ✅ 6. Geographical Insights

🔹 Countries with the Most Tickets

<img width="978" height="546" alt="image" src="https://github.com/user-attachments/assets/4f6afb37-9edb-46ae-8a18-9f78433148b3" />


#### ✅ 7. Monthly Trend Analysis

Since DateCreated is stored as TEXT, you must convert it to DATE using STR_TO_DATE.

🔹 Group by Month and Count Total Tickets

<img width="978" height="441" alt="image" src="https://github.com/user-attachments/assets/ca3f9c19-fa4c-498f-9984-26f2e7af69d6" />


📌 Trend Observations:

* This analysis helps identify seasonal spikes or dips in ticket volume.

* Useful for workload planning and staff allocation.



🔹 Identify Trends or Seasonal Spikes

To identify trends, run the above query and observe:

Which months have spikes in ticket counts?

Are there consistent drops or rises?

📊 You can also export the results into Excel or visualize it in Power BI for a line chart that highlights spikes.


📌 Summary of Insights

Top Issue: Account Suspended appears most frequently.

Ticket Status: Many tickets are still open or in progress.

High/Urgent Priority: Needs focused handling and faster resolution.

Geographical Load: Countries like Pakistan, Germany, and Indonesia generate high ticket volumes.

Seasonality: Ticket volume spikes observed between April–June.


## 💼 Freelance/Client Value Pitch

Organizations handling a large volume of customer support tickets can benefit significantly from data-driven insights. Freelancers specializing in SQL-based analysis and customer support metrics offer valuable support in this space.


#### 🔹 Services Typically Offered:

Comprehensive Ticket Data Analysis
Freelance analysts can extract and interpret key metrics such as ticket volumes, resolution status, priority distribution, and issue type frequency — helping businesses identify inefficiencies and bottlenecks in their support process.


#### SQL-Powered Reporting

SQL queries are used to generate real-time insights into customer service operations. These reports enable teams to monitor unresolved tickets, urgent/high-priority backlogs, and trends in ticket inflow over time.


#### Geographic & Seasonal Insight Mapping

Businesses can benefit from understanding which regions generate the most tickets and during which months spikes occur. Freelancers can provide detailed breakdowns and trend charts using cleaned SQL outputs.

#### Data Preparation for Dashboards

Many freelance professionals also provide clean, structured data outputs that can be plugged directly into Power BI, Tableau, or Google Data Studio for visualization and presentation to stakeholders.

#### Recommendations Based on Insights

Based on the findings, freelance analysts can suggest actionable improvements for ticket triaging, support team distribution, automation opportunities, and workflow optimization.



### 💬 When to Consider Freelance Support:

* If a business is scaling support operations and needs data visibility

* When internal teams lack time or expertise to dig into support metrics

* To produce polished, insight-rich reports for internal or client presentations

* When preparing for customer experience audits or KPI reviews



### 📩 To Explore Freelance Options

Platforms like Upwork, Fiverr, and LinkedIn offer access to freelance data analysts and SQL experts with experience in customer support analytics. Businesses can also directly collaborate with professionals for short-term projects or long-term monitoring solutions.






