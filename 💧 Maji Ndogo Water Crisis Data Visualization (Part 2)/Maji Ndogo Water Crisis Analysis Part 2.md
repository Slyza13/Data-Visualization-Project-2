Project Summary: Building an Interactive Water Access Dashboard for Maji Ndogo
Objective: To transform a multi-table SQL dataset into an interactive Power BI dashboard, enabling deep analysis of water access, quality, and related social issues in the fictional region of Maji Ndogo.

1. Data Model Foundation
The project began by establishing a robust data model in Power BI. Data was imported from an Excel workbook containing multiple tables previously cleaned and structured in SQL.

Key Challenge & Solution: A core challenge was integrating a table on water-source-related crimes (water_source_related_crime). A direct link to the main visits table created a problematic many-to-many relationship. The solution was to connect the crime data to the location table, which contained a unique list of location IDs, effectively using it as a bridging table.

Schema Type: The final model is a multi-star schema, as it connects separate fact tables (like visits and water_source_related_crime) to shared dimension tables (like location). This allows for complex analysis but requires careful management of relationship filtering.

2. National-Level Overview Dashboard
The first dashboard page provides a high-level, national perspective.

Visuals Created:

A map of provinces.

A pie chart showing the urban/rural population split.

A treemap displaying the number of people served by each water source type.

Bar charts breaking down water sources by town and type.

Key Insight: The interactive nature of the dashboard allows a user to click on a province on the map and instantly see all other visuals (population, water sources) filter to that specific context, enabling quick provincial-to-national comparisons.

3. Queue Analysis Dashboard
This page focuses on understanding wait times and demographics at shared water taps.

Data Preparation: New columns for day_of_week and hour_of_day were created from the time_of_record timestamp in the visits table using Power Query.

Visuals Created:

A line plot showing average queue time by hour of the day.

A bar chart for average queue time by day of the week.

A composition chart showing the average percentage of men, women, and children in queues.

Interactive Insight: A decision-maker can discover nuanced patterns by cross-filtering. For example, selecting a specific province, day, and time reveals the exact queue composition, which is vital for planning infrastructure and social services.

4. Water Source Pollution Dashboard
This page visualizes the results of well water testing.

Visuals Created:

A map where color saturation indicates the number of pollution tests per province.

A composition chart showing the count of wells categorized as Clean, Chemically Contaminated, or Biologically Contaminated.

Interactive Insight: By clicking on a pollution type in the chart, the map updates to show which provinces are most affected by that specific issue. This helps prioritize remediation efforts—for instance, identifying a province with a high rate of chemical contamination.

5. Crime and Safety Dashboard
This page links crime data to water access, exploring the safety of individuals collecting water.

Data Preparation: Similar to the queue analysis, day_of_week and hour_of_day columns were added to the crime table.

Visuals Created: Various charts were built to analyze crime patterns by:

Victim type (Women, Men, Children) and specific crime type (e.g., Harassment, Assault).

Time of day and day of the week.

Geographic province.

Critical Findings: The data revealed stark patterns:

Women are twice as likely as men to be victims of crime at water sources.

Harassment and sexual assault are the most common crimes against women.

Crime spikes in the early morning and late evening, coinciding with common water collection times.

6. Conclusion and Next Steps
The project successfully built a multi-faceted analytical tool. The final note emphasizes that while the foundational visuals are powerful, the next phase involves refining the report for clarity and impact. This includes simplifying complex visuals, using key performance indicators (KPIs), and improving the layout to tell a more compelling data story to stakeholders.

Disclaimer: This summary is an original synthesis of the concepts and procedures described in the source material, created to demonstrate understanding and application of data analysis and visualization principles.