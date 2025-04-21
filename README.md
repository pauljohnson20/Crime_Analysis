# Crime Analysis Using Power BI

### Table of Contents:
- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [KPIs](#kpis)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis-eda)
- [Power BI Optimization](#power-bi-optimization)
- [Data Analysis (Power BI Visuals)](#data-analysis-power-bi-visuals)
- [Project Insights](#project-insights)
- [Recommendations](#recommendations)
- [How to Use This Report](#how-to-use-this-report)
- [Contact](#contact)


### Project Overview:
The Crime Analysis Dashboard visualizes crime data, providing insights into crime trends, types, and resolutions. The dashboard includes a variety of visuals to track total crimes, resolved/unresolved crimes, and crime distribution over time and geography. Interactive drill-throughs offer detailed analysis of crime types and time patterns.

### Business Objective:
With rising crime rates, it’s crucial for law enforcement agencies and local authorities to understand crime patterns, track resolutions, and make informed decisions. The goal of this project is to provide a comprehensive view of crime data, helping to identify high-crime areas, seasonal trends, and resolution efficiency, ultimately aiding in resource allocation and strategy formulation.

### Data Source:
Crime Dataset
  - [Crimes.xlsx](https://github.com/user-attachments/files/19831355/Crimes.Data.xlsx)
  - [Crime Type.xlsx](https://github.com/user-attachments/files/19831356/Other.Data.xlsx)

### Tools Used:
  - Excel
  - Power BI

### Data Understanding:
  - Crime Data: Contains information about individual crime time and date, country and resolution status.
  - Crime Type: A separate dataset that categorizes the crimes into crime types

### KPIs:
  1. Total Crime, Total Resolved Crime and Total Unresolved Crime
  2. Crime Rate by Month and Crime Rate by Year
  3. Crime Rate by Time Slot (3-hour intervals)
  4. Percentage Change in Crime (Month-to-Month)
  5. Crime Rate by Weekday
  6. Crime Distribution by Country
  7. Crime Rate by Type of crime
  8. Interactive dashboard [View Dashboard](#https://github.com/user-attachments/assets/144d35b9-c7f3-4a9f-a002-0d81c57362f4)

### Data Cleaning:
  - In Excel: Data was cleaned by removing unwanted columns. Additionally, columns were formatted to ensure consistent date/time formats and data types.
  - In Power BI: Data was further cleaned using Power Query, including transforming columns, and ensuring accurate relationships between tables.

### Exploratory Data Analysis (EDA):
  1. **Crime Type Distribution:**
      - Anti-Social Behaviour and Violence and Sexual Offences represent around 60% of the total crime incidents.
      - These two categories indicate a significant portion of the crime landscape, pointing to social issues that need targeted intervention.
  2. **Monthly Crime Analysis:**
      - The crime rate in September and October accounts for approximately 23% of the total crimes.
      - A noticeable spike in crime during these months suggests seasonal patterns or external factors (e.g., festivals, holidays, or environmental conditions) that could be influencing criminal behavior.
  3. **Time-Based Crime Analysis:**
      - 45% of crimes occur between 9 PM and 3 AM, indicating a high concentration of incidents during late-night hours.
      - This is particularly concerning for law enforcement and community safety, as these hours might coincide with increased social activity, lack of supervision, or alcohol/drug-related behavior.

### Power BI Optimization:
To improve the performance and efficiency of my Power BI report, I applied the following best practices:
  - Used a star schema: Structured the data model with fact and dimension tables instead of flat tables to reduce redundancy and optimize query performance.
  - Removed unnecessary columns and rows: Imported only the required columns and filtered out irrelevant rows to minimize memory usage and improve refresh speed.
  - Turned off Auto Date/Time: Disabled the Auto Date/Time feature to prevent Power BI from creating unnecessary hidden date tables that impact performance.
  - Optimized DAX by using measures: Replaced calculated columns with DAX measures wherever possible to improve calculation performance and reduce memory load.

### Data Analysis (Power BI Visuals):
  - Card Visuals: Display total crimes, resolved crimes, and unresolved crimes.
  - Table Visual: Shows monthly crime data, comparing it with the previous month and calculating percentage changes.
  - Matrix: Displays total crime data by weekday and month, providing a breakdown of crime patterns.
  - Map: Geographical visualization showing total crimes by country.
  - Line Chart: Displays the trend of total crime over time (monthly).
  - Bar Chart: Compares total crimes by year.
  - Bar Chart (Time-based): Displays total crimes by time, with 8 bars representing 3-hour intervals.

Snap of Crime Analysis Dashboard

![Image](https://github.com/user-attachments/assets/144d35b9-c7f3-4a9f-a002-0d81c57362f4)

Snap of Drill Through

![Image](https://github.com/user-attachments/assets/355acda0-f9cd-4352-93e4-089ff410f53e)

### Project Insights:
  - **Concentration in Specific Crime Types:** A large proportion of crimes are concentrated in Anti-Social Behaviour and Violence and Sexual Offences, suggesting that public awareness campaigns, community engagement, and specialized law enforcement strategies could reduce incidents in these categories.
  - **Seasonal Trends:** The September and October spike indicates potential factors driving crime during these months. This could be due to local events, cultural holidays, or even environmental factors such as weather.
  - **Night-Time Crimes:** With 45% of crimes occurring late at night, this suggests a need for increased night patrols, surveillance, or community outreach during these hours to curb criminal activity.

### Recommendations:
  - Targeted Interventions: Focus on community policing, neighborhood watch programs, and specialized units for Anti-Social Behaviour and Violence & Sexual Offences.
  - Resource Allocation: Increase law enforcement and community engagement in September and October, monitoring for external factors like holidays or festivals.
  - Night-Time Policing: Boost patrols, use surveillance tech, and offer late-night community support (e.g., safe zones) from 9 PM to 3 AM.
  - Data-Driven Strategies: Regularly analyze crime trends to adjust prevention measures based on patterns and external factors.
  - Community Collaboration: Work with local businesses, schools, and organizations to address root causes and engage at-risk individuals early.

### How to Use This Report: 
  - Use Filters: Apply filters for Crime Type and Country to narrow down the data for targeted analysis based on location and crime category.
  - Track Key Metrics: Monitor high-level KPIs such as Total Crime, Resolved Crime, and Unresolved Crime to assess overall crime activity and resolution performance.
  - Explore Crime Patterns: Use the heatmap matrix (Weekday vs. Month) to identify patterns in crime occurrence across different days and months.
  - Drill Through Time-Based Trends: Click on specific time slots in the 3-hour interval bar chart to drill through and analyze crime types and frequency during that period.
  - Analyze Trends and Changes: Review the monthly line chart for overall crime trends and use the % change column in the table to compare current vs. previous month performance.

### Contact:
For further information or inquiries regarding this project, feel free to reach out:
  - Email     : pauljohnson2094@gmail.com
  - LinkedIn  : www.linkedin.com/in/pauljohnson2094
  - GitHub    : https://github.com/pauljohnson20
