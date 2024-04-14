# HR Analytics Dashboard

A dashboard created to analyze employee data and provide insights into workforce demographics, turnover trends, and areas for improvement.

## Data
The data was obtained from the HR department and contained over 22,000 employee records from 2000-2020 including:
- Employee ID
- Name 
- Department
- Location
- Hire date
- Termination date 
- Job title
- Gender
- Ethnicity
- Other attributes

## Data Cleaning
The raw data was imported into MySQL Workbench for cleaning and analysis. Records with:
- Negative ages (967 records)
- Future termination dates (1599 records)
Were excluded to ensure only valid data was analyzed. 

Additional derived fields like age, tenure, state were calculated during this stage.

## Data Visualization
The cleaned data from MySQL was connected to Power BI for interactive visualization and dashboarding. A variety of chart types like pie charts, bar graphs, and maps were used.

## Insights
Key insights into workforce demographics, trends, and opportunities included:
- Male to female ratio 
- Ethnicity representation
- Age and tenure distributions
- Headquarters vs remote split
- Departmental and location turnover
- Gender distribution by role and department
- Changes over time from 2000-2020

## Future Enhancements
Areas of potential improvement include:
- Incorporating additional years of data as it becomes available
- Deep diving insights by role, level, ethnicity subgroups
- Benchmarking against industry/location norms  
- Predictive modeling for attrition risks
- Interactive filters and drilldowns

Let me know if you have any other questions!
