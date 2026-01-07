📊 2024 Indian General (Lok Sabha) Election Dashboard
📌 Project Overview

This project focuses on analyzing and visualizing the 2024 Indian General (Lok Sabha) Election results using an interactive Power BI dashboard. The main goal is to transform complex and large-scale election data into clear, meaningful, and easy-to-understand visual insights for users at national, state, and constituency levels.

The dashboard follows a macro-to-micro approach, allowing users to explore election results from an overall national view down to individual constituency details.

🎯 Objectives

To clean and standardize raw election data for accurate analysis

To design an efficient and scalable data model

To present election outcomes through interactive and intuitive dashboards

To enable dynamic filtering, drill-down, and comparison across different levels

📂 Dataset Description

The dataset includes detailed information related to the 2024 Lok Sabha elections, such as:

Candidate names

Political parties and alliances

EVM votes and postal votes

Total votes and vote share

Winning margins

State and constituency details

Since the raw data did not directly provide many analytical insights, additional calculations and transformations were performed.

🧹 Data Cleaning & Preparation

Before visualization, the following steps were carried out:

Standardized party, alliance, state, and constituency names

Handled inconsistencies and mismatches across datasets

Derived additional metrics such as alliance-wise seat counts and vote share

Created structured relationships to support interactive analysis

🏗️ System Architecture & Data Modeling

The project uses a Star Schema architecture, optimized for Power BI performance and simplicity.

🔹 Fact Tables

ConstituencyWiseDetails – Candidate-level voting data including EVM votes, postal votes, total votes, and vote share

ConstituencyWiseResults – Final constituency results with winning party, alliance, and margin

StatewiseResults – Aggregated state-level election outcomes

🔹 Dimension Tables

PartyWiseResults – Party master table mapping parties to alliances

States – Standardized state reference table

All Measures – Central table for all DAX measures like total votes, seats won, vote share, and margins

📊 Dashboards Included
1️⃣ Overview Dashboard

Provides a national-level summary of election results, showing alliance-wise seat distribution and key KPIs to understand the overall outcome at a glance.

2️⃣ State Demographics Dashboard

Allows users to select a state and analyze party-wise and alliance-wise performance using maps and charts.

3️⃣ Political Landscape by State Dashboard

Highlights political competition across states by showing margins, leading and trailing parties, and competitive versus dominant states.

4️⃣ Constituency Analysis Dashboard

Offers detailed constituency-level insights including total votes, EVM and postal votes, winners, runners-up, and winning margins.

⚙️ Key Features

Interactive slicers and filters

Cross-highlighting between visuals

Drill-down from national to constituency level

Consistent color coding for parties and alliances

Optimized performance and fast loading

🚀 Tools & Technologies Used

Power BI – Dashboard development and visualization

DAX – Measures and calculations

Excel / CSV – Data storage and preprocessing

✅ Non-Functional Considerations

Optimized data model for better performance

Simple and intuitive navigation

Clean and professional visual design

Reusable and centralized DAX measures

📌 Conclusion

This project successfully converts raw election data into a structured, interactive, and insight-driven dashboard. By combining clean data modeling, effective visualization, and user-friendly design, the dashboard enables meaningful exploration of the 2024 Lok Sabha Election results at every level.
