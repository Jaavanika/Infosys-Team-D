# Infosys-Team-D
2024 Indian General (Lok Sabha) Election Dashboard
1. Project Overview
   This project focuses on analyzing and visualizing the 2024 Indian General (Lok Sabha) Election results using an interactive Power BI dashboard. The main goal is to transform complex and large-scale election data into clear, meaningful, and easy-to-understand visual insights for users at national, state, and constituency levels.
   The dashboard follows a macro-to-micro approach, allowing users to explore election results from an overall national view down to individual constituency details.

3. Objectives
   To clean and standardize raw election data for accurate analysis
   To design an efficient and scalable data model
   To present election outcomes through interactive and intuitive dashboards
   To enable dynamic filtering, drill-down, and comparison across different levels

3. Dataset Description
   The dataset includes detailed information related to the 2024 Lok Sabha elections, such as:
    Candidate names
    Political parties and alliances
    EVM votes and postal votes
    Total votes and vote share
    Winning margins
    State and constituency details
   Since the raw data did not directly provide many analytical insights, additional calculations and transformations were performed.

5. Data Cleaning & Preparation
   Before visualization, the following steps were carried out:
   Standardized party, alliance, state, and constituency names
   Handled inconsistencies and mismatches across datasets
   Derived additional metrics such as alliance-wise seat counts and vote share
   Created structured relationships to support interactive analysis

5. System Architecture & Data Modeling
The project uses a Star Schema architecture, optimized for Power BI performance and simplicity.

🔹 Fact Tables
ConstituencyWiseDetails – Candidate-level voting data including EVM votes, postal votes, total votes, and vote share
ConstituencyWiseResults – Final constituency results with winning party, alliance, and margin
StatewiseResults – Aggregated state-level election outcomes

🔹 Dimension Tables
PartyWiseResults – Party master table mapping parties to alliances
States – Standardized state reference table
All Measures – Central table for all DAX measures like total votes, seats won, vote share, and margins

6. Dashboards Included
 i. Overview Dashboard

Provides a national-level summary of election results, showing alliance-wise seat distribution and key KPIs to understand the overall outcome at a glance.

 ii. State Demographics Dashboard

Allows users to select a state and analyze party-wise and alliance-wise performance using maps and charts.

 iii. Political Landscape by State Dashboard

Highlights political competition across states by showing margins, leading and trailing parties, and competitive versus dominant states.

 iv. Constituency Analysis Dashboard

Offers detailed constituency-level insights including total votes, EVM and postal votes, winners, runners-up, and winning margins.

7. Key Features
   Interactive slicers and filters
   Cross-highlighting between visuals
   Drill-down from national to constituency level
   Consistent color coding for parties and alliances
   Optimized performance and fast loading

9. Tools & Technologies Used
    Power BI – Dashboard development and visualization
    DAX – Measures and calculations
    Excel / CSV – Data storage and preprocessing

9. Non-Functional Considerations
    Optimized data model for better performance
    Simple and intuitive navigation
    Clean and professional visual design
    Reusable and centralized DAX measures

11. Conclusion
    This project successfully converts raw election data into a structured, interactive, and insight-driven dashboard. By combining clean data modeling, effective visualization, and user-friendly design, the dashboard enables meaningful exploration of the 2024 Lok Sabha Election results at every level.
