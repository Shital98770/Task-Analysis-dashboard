📌 Project: Task Management Dashboard | Power BI

Business Problem:
Organizations often manage projects and tasks using Excel or multiple files, making it difficult to track task status, priorities, deadlines, employee assignments, and actual vs. estimated working hours. Managers may not quickly identify blocked, overdue, or high-priority tasks, which can lead to project delays.

Solution:
Developed an interactive Power BI Task Management Dashboard to provide a centralized view of project performance. The dashboard tracks task status, priority, assigned employees, due dates, estimated hours, actual hours, and overdue tasks using interactive KPIs, tables, filters, and visual indicators.

🔹 Key Features
Task Status: Done, In Progress, In Review, Blocked, To Do
Priority tracking: Critical, High, Medium, Low
Estimated vs. Actual Hours
Overdue task monitoring
Employee/task assignment tracking
Interactive filters and KPI cards
Color-coded status and priority badges
Excel data used as the source


### Task Analysis Dashboard 📊

A sleek, dark-themed, end-to-end data analytics dashboard designed to monitor team productivity, track task completion timelines, and evaluate project hours estimation accuracy. 

This dashboard provides project managers and development teams with actionable insights to eliminate workflow bottlenecks and optimize operational efficiency. 

### 🚀 Key Features & Layout Analysis

The dashboard is structured into several high-impact visualization modules: 

### 1. High-Level KPI Summary (Task Status Metrics)

Quick-glance aggregate metrics highlighting the current state of operations: 

* **Total Tasks:** 189
* **Completed Tasks:** 36 (Tracked relative to timelines)
* **On-Time Tasks:** 11
* **Critical Items:** 46

### 2. Task Prioritization Breakdown

A segmented bar chart and legend detailing distribution by urgency level: 

* 🔴 **Critical:** 46 tasks
* 🟠 **High:** 48 tasks
* 🟡 **Medium:** 42 tasks
* 🟢 **Low:** 53 tasks

### 3. Workflow Bottlenecks & Progress Monitoring

* **Status Groups:** Direct visibility into standard agile statuses like *To-Do* (32), *In Progress* (42), *Blocked* (43), and *Completed* (36).
* **Hour Variance Tracking:** Gauge chart analyzing the discrepancy between **Average Estimated Hours (43.40)** vs. **Average Actual Hours (38.12)** to optimize planning precision.
* **Overdue Hours:** A rolling indicator showing **2K+ total overdue hours** across delinquent tasks.

### 4. Granular Employee & Task Tracking

* **Active Workforce:** Tracks daily active headcount (**25 Active Employees** today).
* **Task Table Matrix:** A comprehensive breakdowns of specific tasks (e.g., API Development) paired with employee IDs (EMP1014, EMP1024, EMP1029), color-coded priority/status badges, actual vs. estimated hour tracking, and exact due dates.

### 🛠️ Technology Stack

* **Business Intelligence / Visualization:** Microsoft Power BI / Tableau
* **Data Sources / Warehousing:** SQL Server / Excel / Jira API
* **Languages Used:** DAX (Data Analysis Expressions), Power Query M formula language
* **Theme Styling:** Customized dark-mode UI json theme template

### 📈 Key Insights Derived

* **High Blockage Rate:** A significant volume of tasks (43) are currently flagged as **Blocked**, indicating dependencies or process gaps that require structural intervention.
* **Overestimate Tendency:** The team's average actual hours are tracking lower than estimated hours, suggesting that initial planning cycles may benefit from more conservative, tightly-scoped time boxes.

