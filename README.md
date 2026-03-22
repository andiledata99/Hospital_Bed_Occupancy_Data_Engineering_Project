# Hospital_Bed_Occupancy_Data_Engineering_Project
This repository demonstrates a data engineering workflow for building a healthcare analytics solution. The project models hospital bed occupancy using a star schema, implemented in SQL Server Management Studio (SSMS), and showcases the full lifecycle from schema design to querying insights.

**🏥 Hospital Bed Occupancy Data Engineering Project**
The objective of this project is to design and implement a data warehouse solution that enables healthcare stakeholders to monitor, analyze, and optimize hospital bed occupancy. By applying data engineering principles—including star schema modeling, database creation in SQL Server Management Studio (SSMS), data population, and SQL querying—this project demonstrates how raw hospital data can be transformed into actionable insights.

**🔧 Data Engineering Workflow**

**1. 	Schema Design (Star Schema)**
• 	Central Fact Table:  (measures like OccupiedBeds, AvailableBeds, Admissions, Discharges, OccupancyRate).
• 	Supporting Dimension Tables: , , , .
• 	Enables efficient OLAP-style queries and BI integration.

**2. 	Database Creation (SSMS)**
• 	Create a new database for hospital bed occupancy analytics.
• 	Define tables with primary and foreign keys to enforce referential integrity.

**3. 	Data Insertion**
• 	Populate dimension tables with sample hospital, bed type, patient type, and date data.
• 	Insert fact records simulating real-world hospital activity (admissions, discharges, occupancy snapshots).

**4. 	SQL Queries & Joins**
• 	Perform INNER JOINs and LEFT JOINs across fact and dimension tables.
• 	Example analyses:
• 	Occupancy trends by hospital region and season.
• 	ICU vs. surgical bed utilization.
• 	Emergency vs. elective patient flow.
• 	Surge capacity monitoring (e.g., winter flu season).

**5. 	Analytics & Reporting**
• 	Query outputs can be connected to BI tools (Power BI) for dashboards.
• 	Supports healthcare resource planning and national benchmarking.

**🚀 Why It Matters**
This project highlights core data engineering skills:
• 	Database design (star schema modeling).
• 	ETL fundamentals (data loading and transformation).
• 	SQL proficiency (joins, aggregations, calculated measures).
• 	Analytics enablement (turning raw hospital data into actionable insights).
