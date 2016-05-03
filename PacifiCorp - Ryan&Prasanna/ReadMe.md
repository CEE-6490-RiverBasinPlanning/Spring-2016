
#Evaluating Reservoir Operation Rules to Improve Hydropower Production and Reduce Unmet Water Demands: A case study in the Bear River Basin Using the Water Evaluation and Planning (WEAP) System

By: Prasanna Dahal, Ryan James

Last Updated: May 03, 2016

Submitted For: David Rosenberg, spring 2016 CEE6490 – Integrated River Basin/Watershed Planning and Management

--------------------------------------------------------------------
--------------------------------------------------------------------

##1. What is Included in this Repository

The following files are included in this repository.

#####Presentation and Report
This folder conatins the final report and the power point presentation given by the authors on April 28, 2016 to the spring 2016 CEE 6490 Integrated River Basins/ Watershed Planning and Management.  The report is the final findings for this proejct and describes in detail how the solutions were found.  This presentation highlights the findings of the model on reservoir operations for the Soda, Grace, and Oneida reservoirs.

#####Model
This is the zipped file containing the WEAP model on reservoir operations for the Soda, Grace, and Oneida reservoirs along the Bear River (Prasanna Dahal - Ryan James_LowerBearRiver_Spring2016_PacifiCorp.zip).  This WEAP model does not contain the results, as the results file was too large to upload.  Instead, interested users will have to follow the below user friendly directions to load and view the results manually.

#####Documentation
These folder consist of a few figures to support the repository, the 2002 explantory statement report that highlights the settlement agreement among PacifiCorp, and the progress report for this project submitted on March 15, 2016 by the two authors to the spring 2016 CEE 6490 Integrated River Basins/ Watershed Planning and Management.  It should be noted that information found within the progress reports here is no longer up-to-date and users interested in the findings should look instead at the Final Report submission.


##2. How to Download the Model and Run Results

Users interested in downloading and repeating the results should follow these instructions.

1.	This model was built using the WEAP ("Water Evaluation and Planning" system) software.  Interested users will need to have this software installed and running before they can download and repeat the results of this project.  This project was built using the 2015.0, August 5, 2015 WEAP model version. WEAP a be found at the following link. http://www.weap21.org/
2.	Click on the “Prasanna Dahal - Ryan James_LowerBearRiver_Spring2016_PacifiCorp.zip” link within the Spring-2016/PacifiCorp - Ryan&Prasanna GitHub repository.
3.	Click on the “Raw” button on the right hand side.
4.	Download and extract the file to wherever you have instructed WEAP to read and access files (Ex: for this project we assigned our model to a folder we titled “WEAP Areas” within out Documents folder, but any similar location will work providing it is the location that the WEAP software was instructed to look and load files during the software installation).
5.	Open the WEAP software.
6.	Go to Area > Open > and look for the folder “Prasanna Dahal – Ryan James_LowerBearRiver_Spring2016_PacifiCorp” you downloaded and extracted to the WEAP accessible folder.
7.	Once loaded, click on the “Results” button on the far left hand side.  This file contains over 30 scenarios, and will take time to run through and complete each scenario in order to view the results.
8.	Once the runtime has finished, users should be able to browse results at their leisure.


##3. Project Outline and Abstract

This study evaluates the effectiveness of updating reservoir operations for the Soda, Grace, and Oneida reservoirs along the Bear River in southeastern Idaho.  These reservoirs are currently owned and operated by the PacifiCorp Electric Company.  The primary purpose of these reservoirs is to supply downstream water demand, protect against flooding events, provide a source of recreational use, and produce hydro generated electricity.

Despite the wide range of use, these three reservoirs are not performing as well as they could.  The current implemented reservoir operation is to supply immediate downstream water demand at the cost of potential storage and greater hydroelectricity generation.  We believe there is a potential for greater performance for these reservoirs by making adjustments to their operation metrics.
We have found that by altering the release policy of these reservoirs it is possible to increase potential hydropower generation by 55% or alternatively further decrease downstream water demand by (-)0.26% for all demand sites.  This is possible via a combination of reservoir operations including 1) changing the amount of water that is considered inactive for water demand, 2) the volume of water that is constrained below a specific level, 3) by adopting a seasonal change in demand priority that increases storage during the refill period.

Our provided alternatives in reservoir operation were designed in mind with the goal of increasing hydroelectricity generation and lowering unmet water demand.  This report provides a detailed description of how we came to these conclusions and how they can be included into the reservoir practice.  We feel confident that our solutions are a benefit for the PacifiCorp Electric Company and strongly recommend that they be implemented. 

![Map of the Reservoirs](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/PacifiCorp%20-%20Ryan%26Prasanna/Documentation/Fig%20Res%20Location.jpg)

Figure: Online screen shot of the locations of the three reservoirs in question along the Bear River.

![Soda Powerhouse](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/PacifiCorp%20-%20Ryan%26Prasanna/Documentation/Fig%20Soda%20Powerhouse.png)

Figure: Soda Reservoir Powerhouse. 



##4. Performance Metrics Used

####4.1 Definitions of Performance Criteria

Hydropower Generation:  Megawatts (MW). The amount of electrical energy produced by the dam when water is released. The objective is to maximize this value.

Unmet Water Demand:  Acre-foot (ac-ft). The target water delivery demand not met by the entire system. The objective is to minimize this value.

These metrics will be tested using the following methods: 1) changes in reservoir operation and release policy, 2) chaining the priority of energy production demand with respect to water delivery demand.

####4.2 How Performance Metrics Were Calculated:

Hydropower Generation. [Screen Shot here!](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/CombinedWEAPArea/PacifiCorp%20Performance%20Metric%20Example/Hydropower%20Generation%20Ex.PNG)

1.	Go to the Results page in your WEAP model.
2.	In the first drop down box, go to “Supply and Resources” > “Reservoir” > “Hydropower Generation”.
3.	For the x-axis select “All Years” from the drop down list.
4.	For the y-axis select “Selected Reservoirs” from the drop down list.   From the list, click on the check box for the “Soda, Grace, and Oneida” reservoirs.  Then click the “OK” button.
5.	In the legend, select which scenarios you would like to view (in our image example we show alternative solutions for 1) Best Hydropower Generation, 2) Best for Unmet Water Demand, 3) Mid-Range Results, 4) The Reference scenario, where no reservoir operations have been selected).
6.	For units, select “Megawatt.”
7.	Select “All months (12).”
8.	For simplicity, click on the “Monthly Average” check box.
9. 	Click the “'Export Table to Excel“ icon on the right most column. 
10.	We compared our alterative solutions to the Reference Scenario, but you can compare you results with any other scenario.  For this, we did the percent difference.  To calculate the percent difference: 1) first work out the difference (increase) between the two numbers you are comparing, 2) then divide the increase by the original number (reference for us) and multiply the answer by 100.

For Unmet Water Demand. [Screen Shot here!](https://github.com/CEE-6490-RiverBasinPlanning/Spring-2016/blob/master/CombinedWEAPArea/PacifiCorp%20Performance%20Metric%20Example/Unmet%20Demand%20Ex.PNG)

1.	Go to the Results page in your WEAP model.
2.	In the first drop down box, go to “Demand” > “Unmet Demand.”
3.	For the x-axis select “All Years” from the drop down list.
4.	For the y-axis select “All Demand Sites” from the drop down list (or choose a specific demand site.
5.	In the legend, select which scenarios you would like to view (in our image example we show alternative solutions for 1) Best Hydropower Generation, 2) Best for Unmet Water Demand, 3) Mid-Range Results, 4) The Reference scenario, where no reservoir operations have been selected).
6.	For units, select “Acre-foot.”
7.	Select “All months (12).”
8.	For simplicity, click on the “Monthly Average” check box.
9. 	Click the “'Export Table to Excel“ icon on the right most column. 
10.	We compared our alterative solutions to the Reference Scenario, but you can compare you results with any other scenario.  For this, we did the percent difference.  To calculate the percent difference: 1) first work out the difference (increase) between the two numbers you are comparing, 2) then divide the increase by the original number (reference for us) and multiply the answer by 100.
