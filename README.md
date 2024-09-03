

# Global Terrorism Dashboard Report 2000 - 20220

## Problem Statement

The Global Terrorism Dashboard is designed to help analysts and policymakers understand the global patterns, trends, and impacts of terrorism. By visualizing data related to terrorist incidents, this dashboard allows users to identify key areas of concern, analyze the effectiveness of counter-terrorism strategies, and make informed decisions to enhance global security. The dashboard provides insights into the frequency, types, and geographical distribution of terrorist activities, as well as the human and economic costs associated with these incidents.

Given that terrorist activities have shown significant variation across different regions and over time, it is crucial for stakeholders to understand the underlying trends and patterns. This dashboard aims to provide a comprehensive overview of global terrorism, helping to identify high-risk areas and prioritize resource allocation for counter-terrorism efforts.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Column Profiling: In Power Query Editor, under the Data Preview section, options like "Column Distribution," "Column Quality," and "Column Profile" were enabled to assess the data quality.

- Step 3 : Handling Missing Values: It was observed that certain columns had missing values, particularly in casualty data. These were handled appropriately during calculations to avoid skewed results.

- Step 4 : Data Transformation: New columns were created for decade-based analysis, geographical aggregation, and categorization of attack types and target groups.
 
- Step 5 : In the report view, under the view tab, theme was selected.

- Step 6 : Visual Filters (Slicers): Slicers were added for fields such as Country, Region, Year, Attack Type, and Weapon Type, allowing users to filter the data dynamically. 
- Step 7 :Key Metrics: Card visuals were created to display key metrics such as the total number of incidents, total casualties, and the most active terrorist groups.


- Step 8 : Trend Analysis: A line chart was used to depict the trend of terrorist incidents over time, with decade intervals highlighted.
- Step 9 : Geographical Distribution: A map visual was added to display the geographical distribution of incidents, with regions shaded according to the number of incidents. 
- Step 10 : Custom Measures: Several DAX measures were created to calculate the average number of incidents per year, the percentage of attacks by specific groups, and the average casualties per incident.



        
- Step 11 : Decade Grouping: A calculated column was created to group incidents by decade, facilitating trend analysis over time.
        
A card visual was used to represent Total incidents ,successful attacks,Failed attacks.

![Screenshot 2024-09-03 115849](https://github.com/user-attachments/assets/ce695db4-0a9a-4a53-9ab1-c1e739ceb57e)

        

# Snapshot of Main Page

![Screenshot 2024-09-03 120841](https://github.com/user-attachments/assets/a6240e47-08e5-4a04-a3f2-a25baa79ac0a)

# Snapshot of Dashboard

![Screenshot 2024-09-03 120611](https://github.com/user-attachments/assets/a64b6448-d98c-4d02-aa77-8bf165f8f25f)

![Screenshot 2024-09-03 123630](https://github.com/user-attachments/assets/cab4bdb6-5fa2-448a-b116-cd5a51242652)

![Screenshot 2024-09-03 120730](https://github.com/user-attachments/assets/08d5428b-9d7c-40ec-bb0a-822269e28568)




![Screenshot 2024-09-03 120807](https://github.com/user-attachments/assets/d4cda415-4f20-498f-8c55-4a038fc37384)


# Insights

A 4 page report was created on Power BI Desktop 

Following inferences can be drawn from the dashboard;

### [1]  Global Incident Overview


Total Incidents:58586

Most Affected Region: Middle East & North Africa

Most Active Group: Taliban
           
### [2] Temporal Trends


Peak Decades: The highest number of incidents occurred during the 2000s, with significant spikes in specific years linked to major global events.

Recent Trends: A noticeable decline/increase in terrorist activities in recent years, possibly due to international counter-terrorism efforts.  
  
  ### [3] Geographical Hotspots 
  Top 5 Countries by Incidents: Countries like Iraq, Afghanistan, and Pakistan rank highest in terms of the number of incidents, indicating ongoing conflict and instability.

Regional Distribution: The Middle East and South Asia emerge as the most affected regions, highlighting the need for targeted counter-terrorism strategies in these areas.

 ### [4] Attack and Target Analysis
 

Common Attack Types: Bombings/explosions account for the majority of attacks, followed by armed assaults and kidnappings.

Target Groups: Civilians are the most frequent targets, followed by government officials and security forces.
 
 ### Casualty Analysis
 
Total Casualties: 231.42k

Deadliest Attacks: Certain incidents have resulted in exceptionally high casualties, often associated with large-scale bombings or coordinated attacks.
         
### Policy Implications

Resource Allocation: The data underscores the importance of allocating resources to high-risk regions and enhancing international cooperation to combat terrorism.

Preventive Measures: The need for community engagement, intelligence gathering, and targeted interventions is evident from the patterns observed in the data.


