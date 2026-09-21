# F1-Formula-1-Performance-Dashboard-
An end-to-end Power BI analytics solution engineered to evaluate driver dominance, constructor standings, circuit geography, and vehicle reliability across four seasons of modern Formula 1 racing.

📌 Project Purpose
The primary objective of this project is to transform complex F1 race data into an executive-ready, single-page interactive dashboard. Designed with a custom dark UI, it allows analysts, team strategists, and fans to track multi-season trends, evaluate driver performance, and analyze equipment reliability across regulation cycles.

🛠️ Tech Stack
Power BI Desktop: Visual development, canvas architecture, dynamic slicers, and interactive cross-filtering.
Power Query (M): Data extraction, cleaning, type casting, and ETL transformations.
DAX (Data Analysis Expressions): Custom time-intelligence measures, dynamic distinct aggregations, and performance metrics.
SVG / UI Canvas Design: Custom dark layout template (#1A1A1A charcoal background, #282828 containers, and #E10600 F1 red accents)
Data Modeling: Star Schema architecture ($1 : *$ relationships) connecting Fact and Dimension tables. 

📁 Data Source
Dataset Scope: 4 Formula 1 Seasons (2022, 2023, 2024, 2025).
Data Structure:
         Fact Table: Race Results (Central fact table containing finishing positions, points, lap times, and status).
         Dimension Tables: Drivers, Constructors, Race Calendar.
✨ Feature Highlights
🎯 Business Problem
In high-stakes motorsport, race strategists and analysts need to extract clear insights from thousands of telemetry data points across multiple seasons. Raw spreadsheets make it difficult to compare constructor dominance against mechanical reliability (DNFs) or track driver performance across shifting regulation years.

🏁 Goal of the Dashboard
To build an executive-level single-page dashboard that consolidates multi-year driver wins, constructor points, team reliability, and geographic race data into a dark F1 interface.

📊 Walkthrough of Key Visuals
Executive KPI Cards: Real-time dynamic metrics tracking total active drivers, competing teams (constructors), and total race DNF incidents.
Wins by Driver (Horizontal Bar Chart): Ranks top drivers by total victories across selected seasons.
Points by Constructor (Column Chart): Tracks total constructor championship points, highlighting team dominance across Red Bull, Ferrari, Mercedes, McLaren, and others
Driver Nationalities & Circuit Distribution (World Map): Interactive map displaying driver origins and race locations with dynamic bubble scaling.
Reliability Breakdown (Donut Chart): Categorizes Did Not Finish (DNF) counts by constructor to highlight engine failures and incident rates.
Dynamic Season Slicers: Multi-year filtering buttons (2022–2025) that instantly slice the entire dashboard via Star Schema relationships.

💡 Business Impact & Insights
Reliability vs. Speed: Identifies high-performing teams whose championship campaigns are hindered by frequent mechanical DNFs.
Constructor Dominance Tracking: Visualizes point distribution gaps across regulation shifts to identify competitive parity.
Driver Efficiency: Measures points and wins earned relative to constructor package strengt

Screenshots / Demos 
show what dashboard look like -![F1 Performance Analytics Dashboard](https://raw.githubusercontent.com/Abdullahprobro/F1-Formula-1-Performance-Dashboard-/main/Screenshot%20(971).png)
![F1 Performance Analytics Dashboard] (https://github.com/Abdullahprobro/F1-Formula-1-Performance-Dashboard-/blob/main/Screenshot%20(973).png)






