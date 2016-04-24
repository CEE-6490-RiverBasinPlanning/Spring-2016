#Description of Folder Contents

Date |  Weap Area Name | Person | Stakeholder | Description of Modifications
--- | --- | --- | --- | ---
April 3, 2016  |LowerBearRiver-Spring2016-DataComplete    |David Rosenberg   |NA            |Base case version of the model
April 7, 2016  |LowerBearRiver-Spring2016-DataComplete    |Bryce and Tyler   |BRMBR         |No modifications to the model
April 10, 2016 |LowerBearRiver-Spring2016-DataComplete    |Rezaul and Sal   |BRCC         |No modifications to the model
April 11, 2016 |LowerBearRiver-Spring2016-DataComplete    |Nour and Mohamad   |Logan City       |No modifications to the model
April 12, 2016 |20160421_LowerBearRiver-Spring2016-DataComplete    |Prasanna and Ryan  |PacifiCorp       |Added three reservoirs to lower bear river

--------------------------------------------------------------------
##Stakeholder: BRMBR

### Definitions of Performance Criteria Statistical Evaluations for the BRMBR
Adapted from Loucks et. al., 2005

Reliability – the fraction of time the system is in a satisfactory condition. It is calculated as the number of monthly observations that is unsatisfactory, divided by the total number of monthly observations. 

Resilience – the likelihood that system will return to the satisfactory condition after reaching an unsatisfactory state. It is calculated as the number of times a satisfactory value follows an unsatisfactory value divided by the number of times and unsatisfactory value occurred. 

Vulnerability – is the magnitude of failure to be expected when the system reaches an unsatisfactory state. It is calculated as the sum of the positive value of the difference between the observed value and the target value, divided by the number of unsatisfactory monthly observations. 

Monthly percent of demand delivered weighted to bird use for that month - is the percentage of demand delivered weighted by the number of priority bird species that occupy habitat areas within BRMBR for that month. This metric creates a higher weight for months that have higher bird usage. For example, April and May have higher priority bird species use than June and July or December and January, thus, when unmet demand occurs for higher weighted months, a greater negative effect on the performance metric is incurred. 

### How to calculate performance metrics for the BRMBR:
[Screen shots here!](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/tree/master/CombinedWEAPArea/BRMBR%20Performance%20Metric%20Calcs)

1. **Download** the performance calculation workbook for the BRMBR ([BRMBR_workbook.xlsx](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/CombinedWEAPArea/BRMBR%20Performance%20Metric%20Calcs/BRMBR_workbook.xlsx)). This can also be found in the BRMBR folder. Click **View Raw** to download the file. 
2. Go to the Results page in your **WEAP model**.
  1. Select the 'chart' tab in the top right.
  2. Select the 'Damand', then **'Unmet Demand'** in the first drop down. 
  3. On the right most drop down select **'All Scenarios'**.
  4. On the bottom drop down select **'All Years'**. 
  5. On the bottom left drop down select **'Demand Site: Bird Refuge'**.
  6. Units should be in **'Thousand' 'Acre-foot'** and **'All months (12)'** and **'No comparison'** should be chosen. 
  7. Click the excel icon on the right most column of options. Hovering over the icon it will say **'Export Table to Excel'**
3. Go to **Excel**.
  1. Select all the data (Ctr+A).
  2. Copy the data (Ctr+C).
4. Open the **BRMBR_workbook.xlsx** Excel file.
  1. Go to the **'Input Data'** sheet, click on cell A:1, then select all the cells (Ctr+A).
  2. Paste all the data (Ctr+V).
  3. Go the the **'Performnace Summary'** sheet to see the calculated results.
  4. WeightedMonthlyBirdUse, Reliability, Resilience, and Vulnerability sheets are used to make the calculations. 
  5. See the Instructions and Definitions sheets for guidence. 
5. Use the data in the **'Performance Summary'** sheet for your analysis.


--------------------------------------------------------------------
##Stakeholder: BRCC

Stakeholder: Bear River Canal Company (BRCC).
Definitions of Performance Criteria:
Reliability, Resilience, and Vulnerability (RRV) metrics measure different aspects of a water resources system performance (Hashimoto et al., 1982). RRV metrics provide one of the most comprehensive approaches for analyzing the probability of success or failure of a system, the rate of recovery of a system from unsatisfactory states, as well as quantifying the expected consequence of being in unsatisfactory states for extended periods (Asefa et at., 2014).
Reliability: Reliability is the fraction of time the system is in a satisfactory state and is given as:
Reliability=(# of observations that are satisfactory)/(Total # of observations)……………………(1)

Resiliency: Resiliency is the likelihood for the system to recover from an unsatisfactory state and is given as:
Resiliency=(# of transitions from failure in time t to unsatisfactory state in time t+1)/(Total # of failures)……(2)

Vulnerability: Vulnerability is the average difference from the threshold for unsatisfactory states and is given as:
Vulnerability=(∑_(t is at failures)▒〖|P_t-Threshlod|〗)/(Total # of failures)…………(3)
Where, Pt = Value of the parameter when the system is in unsatisfactory state
		Threshold = Threshold value of the parameter in question for identifying the system to be in satisfactory state.

Description of Performance Metric Calculations: The unmet demand of BRCC for the base case scenario from WEAP is exported to an MS excel file. Reliability, resilience, vulnerability of BRCC are calculated according to equations 1 through 3. 


--------------------------------------------------------------------
--------------------------------------------------------------------
##Stakeholder: PacifiCorp
###Changes to Model: Addition of three reservoirs to lower-bear river have been included: Soda, Grace, and Oneida.  Each reservoir will have a Storage Capacity, Volume Elevation Curve, Net Evaporation, and a delivery Priority.
###Definitions of Performance Criteria
Hydropower Generation:  Megawatts (MW). The amount of energy produced by the dam when water is released.  
Unmet Water Demand:  Acre-foot (ac-ft). The amount of water delivered to demand sites of the entire system. 
This will be tested with two methods: 1) observing changes in reservoir operation and release policy, 2) chaining the priority of energy production demand with respect to water delivery demand.
###How to calculate performance metrics:
1.	Hydropower Generation
2.	[Screen Shot here!](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/CombinedWEAPArea/PacifiCorp%20Performance%20Metric%20Example/Hydropower%20Generation%20Ex.PNG)
a.	Go to the Results page in your WEAP model.
b.	In the first drop down box, go to “Supply and Resources” > “Reservoir” > “Hydropower Generation”.
c.	For the x-axis select “All Years” from the drop down list.
d.	For the y-axis select “Selected Reservoirs” from the drop down list.   From the list, click on the check box for the “Soda, Grace, and Oneida” reservoirs.  Then click the “OK” button.
e.	In the legend, select which scenarios you would like to view (in our image example we show alternative solutions for 1) Best Hydropower Generation, 2) Best for Unmet Water Demand, 3) Mid-Range Results, 4) The Reference scenario, where no reservoir operations have been selected.
f.	For units, select “Megawatt.”
g.	Select “All months (12).”
h.	For simplicity, click on the “Monthly Average” check box.
3.	For Unmet Water Demand
4.	[Screen Shot here!](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/CombinedWEAPArea/PacifiCorp%20Performance%20Metric%20Example/Unmet%20Demand%20Ex.PNG)
a.	Go to the Results page in your WEAP model.
b.	In the first drop down box, go to “Demand” > “Unmet Demand.”
c.	For the x-axis select “All Years” from the drop down list.
d.	For the y-axis select “All Demand Sites” from the drop down list (or choose a specific demand site.
