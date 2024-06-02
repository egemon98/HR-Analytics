# HR Analytics-Dashboard

### Dashboard Link : [[https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection](https://drive.google.com/file/d/1cuoLk3H2oAAfu86TnnT9tywUsp-TrOEK/view?usp=drive_link)
](https://drive.google.com/file/d/1OFxfoTsyVzOQwLEV_AjJfaubo1mk8YWE/view?usp=sharing)
## Problem Statement

Pinali Mandalia, from AtliQ technologies, manages HR for her company. She currently relies on manually analyzing spreadsheets containing employee attendance data for the past 3 months. This data includes codes for various leave types, such as paid leave (PL) and sick leave (SL).


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.  
- Step 2 : If dates are spread across multiple columns, Power Query can be used to combine them into a single date column. This simplifies future calculations and visualizations.
- Step 3 : create a template for data transformation. This template can be applied to all sheets containing similar data, saving time and effort.
- Step 4 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 5 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 7 : Before loading the transformed data into Power BI for visualizations, it's essential to double-check and ensure everything looks clean and accurate.
- Step 8 : Once the data is clean and transformed, it's ready to be loaded into Power BI for creating visualizations (charts, graphs, etc.) to gain insights from the data.

           
     
- Step 9 : After data transformation, you'll define the metrics (measures) you want to calculate from the data. These metrics will provide insights into what the data is telling you.
	Examples of metrics include:
		Percentage of work-from-home days
		Percentage of sick leave days
		Total working days

- Step 10 : Ratings Visual was used to represent different ratings mentioned below,Power BI uses DAX (Data Analysis Expressions) to create custom calculations and metrics.Measures are typically stored in a separate table within Power BI for better organization.


- Step 11 : Each measure requires a formula to specify the calculation logic. The formula can use functions like COUNT or CALCULATE to manipulate the data and arrive at the desired metric value. Understanding functions like CALCULATE is crucial for working with measures.

- Step 12 : Measures can leverage existing data fields from the transformed data set.
		For example, a measure calculating total working days might count the number of entries with specific codes (like "WO" and "HO") representing work statuses.
- Step 13 : You can specify the time period (e.g., day, month) over which the measure is calculated. Power BI allows creating new calculated columns to represent time periods (e.g., "Start of Month") for use in measures.



![image](https://github.com/egemon98/HR-Analytics/assets/91773966/0eac2117-3d39-4967-aa56-94ee9e56bff5)

        
- Step 14 : It's recommended to group all measures in a single table within Power BI for better organization and easier management.

![image](https://github.com/egemon98/HR-Analytics/assets/91773966/5f5aa3bc-6dd3-4e04-8016-ddfac88cc9a2)

        
 - Step 15 : Once you have the essential measures, you can use them to create the visual elements (charts, graphs) within your Power BI dashboard. Additional measures can be created on the fly as needed to support specific visualizations in the dashboard.
 
![image](https://github.com/egemon98/HR-Analytics/assets/91773966/566ccb99-6f8c-4cb7-b03f-d61909f78262) 

 
 - Step 16 : Identify the most important metrics you want to display on the dashboard to answer your business questions.
Examples of metrics on the HR dashboard include:
	    
        Presence Percentage
		Work From Home Percentage
		Sick Leave Percentage
 
 
![image](https://github.com/egemon98/HR-Analytics/assets/91773966/621d7a3a-6aa4-4969-aa8d-c8a17f326aa3)
 
 - Step 17 : Use the chosen metrics to create charts and graphs that effectively communicate insights.Power BI offers various chart types like line charts, bar charts, etc.

# Snapshot of Dashboard (Power BI Service)


 - Step 18 : You can apply filters to the visualizations to focus on specific data subsets. For example, you might filter out weekends to get a clearer picture of weekday trends.
 - Step 19 : You can adjust the time period displayed in the visualizations (e.g., daily vs. monthly). Formatting the date can improve readability (e.g., displaying just the day of the week).
 - Step 20 : Once you have all the desired visualizations arranged and formatted, your Power BI dashboard is complete. 



 # Report Snapshot (Power BI DESKTOP)
![image](https://github.com/egemon98/HR-Analytics/assets/91773966/16f3bae8-ce2d-4015-9034-7c6ca6985278)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Working Days = 4369

   Day of Present = 4014

   Day of Seak Leave = 48

  
### [2] Persentage

    a) Present Day - 91.83%
    b) WFH - 10%
    c) Seak Leave- 1.2%
