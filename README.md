# PyBer_Analysis
## Analyze and visualize ride-sharing data using the power of Python, Pandas and Matplotlib
### Originally the [PyBer.ipynb](PyBer.ipynb) report had the following deliverables:
* Verify, import, and merge data frames.
* Create bubble charts that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
* There was also a mean, median and mode data calculated for each city type.
* Numerous bubble charts, box and whisker plots and pie charts showing the total percent of total fares, rides, and drivers.

### However, Mr. Visualize changed the scope of the Pyber report and there are new deliverables.  Utilizing Python, Pandas and Matplotlib, there will be a new data frame summary created for ride-sharing data by city type.  The other deliverable output is a multiple-line graph that shows the total weekly fares for each city type.  

## Results of Deliverable 1 - New Data Summary for each City Type.

![Deliverable1_1_3.jpg](Deliverable1_1_3.jpg)
### First the total drivers, rides and sum of fares were calculated by use of the groupby function for their respective population types.
![Deliverable1_4_6.jpg](Deliverable1_4_6.jpg)
### Then the average fare per ride per city type and the average fare per driver by city types were calculated.  The rough draft of the summary was formulated.  
![Deliverable1_7_8.jpg](Deliverable1_7_8.jpg)
### The data frame was then cleaned up by removing the index name, and the summary was cleaned up by formatting the columns with their respective significant digits.  The most significant findings are as follows:
* The number of total rides from urban / suburban / rural is 13:5:1 – that shows a massive disparity in the number of rides from urban when compared to its suburban and rural counterparts.
* This disparity also is displayed in the overall fares which the urban total fares accounts for 62.7% of the cash flow generation.
* Since there are more than 2300 less drivers in rural areas compared to urban areas, the average fare per rural driver is 71% more than the suburban driver and a whopping 235% more than the urban driver. 

## Summary and Results of Deliverable 2 - Weekly Fare Data for each City Type and Chart.
![Deliverable2_1_2.jpg](Deliverable2_1_2.jpg)
### The pyber data frame was read and sorted by the groupby function for date and type, then differentiated for the sum of fares.
![Deliverable2_3_4.jpg](Deliverable2_3_4.jpg)
### The index was reset from the merged data frame, then a pivot table was created with the “date” as the index, “type” as the columns, then “fare” as values. 
![Deliverable2_5.jpg](Deliverable2_5.jpg)
![Deliverable2_6_7.jpg](Deliverable2_6_7.jpg)
![Deliverable2_8_part1.jpg](Deliverable2_8_part1.jpg)
![Deliverable2_8_part2.jpg](Deliverable2_8_part2.jpg)
![Deliverable2_8_output_chart.jpg](Deliverable2_8_output_chart.jpg)

## Deliverable 3 Requirements
* Structure, Organization, and Formatting (6 points)
* The written analysis has the following structure, organization, and formatting:

## DELIVERABLE 3 RUBRIC
### There is a title, and there are multiple sections. (2 pt)
### Each section has a heading and subheading. (2 pt)
### Links to images are working and displayed correctly. (2 pt)

## Analysis (14 points)
The written analysis has the following:
### Overview of the analysis:
The purpose of the new analysis is well defined. (3 pt)
### Results:
There is a description of the differences in ride-sharing data among the different city types. 
Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
### Summary:
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

## Submission
Once you’re ready to submit, make sure to check your work against the rubric to ensure you are meeting the requirements for this Challenge one final time. It’s easy to overlook items when you’re in the zone!

As a reminder, the deliverables for this Challenge are as follows:

Deliverable 1: A ride-sharing summary DataFrame by city type.
Deliverable 2: A multiple-line chart of total fares for each city type.
Deliverable 3: A written report for the PyBer analysis (README.md).
Upload the following to your PyBer_Analysis GitHub repository:

The PyBer_Challenge.ipynb file.
The results need to be kept populated in the PyBer_Challenge.ipynb file. Do not clear the output from the PyBer_Challenge.ipynb file before uploading to GitHub.
The “Resources” folder with the city_data.csv and ride_data.csv files.
The “analysis” folder with the PyBer_fare_summary.png.
An updated README.md that has your written analysis.
