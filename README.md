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
### The loc function was then utilized for the dates from 1/1/2019 to 4/29/2019.
![Deliverable2_6_7.jpg](Deliverable2_6_7.jpg)
### The “date” index was set to data time data type and verified using the info function.
![Deliverable2_8_part1.jpg](Deliverable2_8_part1.jpg)
![Deliverable2_8_part2.jpg](Deliverable2_8_part2.jpg)
![Deliverable2_8_output_chart.jpg](Deliverable2_8_output_chart.jpg)
### Finally, a new data frame was created utilizing the resample function by the week and able to obtain the sum of the fares for each week.  Then a plot was created using the object-oriented interface method.  Matplotlib was imported and the “fivethirtyeight” graph style was used.  
## Deliverable 2 Key Takeaways
* The line graph of weekly fare data confirms the summation of market share dominated by urban fares.
* It is also worth noting the weekly sum of fares data is consistent, ranging from $2000 to $2500.
* Weekly fare data is not nearly as consistent for rural and suburban types, there is a ton of variance for each respective city type.  
* It is worth noting there were weeks where the rural city type got less than $100 in fares for the week.  It is unsure the cost of overhead, but these numbers are meager and need to be addressed by the CEO and COO.

## Conclusion and Recommendations
###  From the findings of this analysis and knowledge of the ride-sharing business model, here are some things for the C-Level leadership to consider:
1.	These data frames had no information on rider feedback about drivers – it would be wise to incentivize your best drivers, especially in urban areas to represent PyBer and perform excellent customer service.
2.	Consider raising prices during non-peak times in suburban and rural cities to balance out the weekly troughs in revenue shown in the final visualization.  This can surely be accomplished in suburban areas since they will have a higher willingness to pay.
3.	Consider shutting down rural service in non-peak times – the overhead cost to operate the service is more than $100 per week, therefore PyBer operates at a significant loss servicing rural areas.
