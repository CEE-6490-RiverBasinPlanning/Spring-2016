##What is Included in this Repository

The following files are included in this repository.


#####Final Presentation- CEE 6490_V2.pptx
A power point presentation given by the authors on April 28, 2016 to the spring 2016 CEE 6490 Integrated River Basins/ Watershed Planning and Management.  This presentation highlights the findings of the model on reservoir operations for the Soda, Grace, and Oneida reservoirs.

####Prasanna Dahal - Ryan James_LowerBearRiver_Spring2016_PacifiCorp.zip
This is the zipped file containing the WEAP model on reservoir operations for the Soda, Grace, and Oneida reservoirs along the Bear River.  This WEAP model does not contain the results, as the results file was too large to upload.  Instead, interested users will have to follow the below user friendly directions to load and view the results manually.

####Prasanna_Ryan_PacifiCorp_BRP_ProgressReport.docx AND Prasanna_Ryan_PacifiCorp_BRP_ProgressReport.pdf
These two documents consist of the progress report for this project submitted on March 15, 2016 by the two authors to the spring 2016 CEE 6490 Integrated River Basins/ Watershed Planning and Management.  It should be noted that information found here is no longer up-to-date and users interested in the project findings should look instead at the final report submission.


##How to Download the Model and Run Results

Users interested in downloading and repeating the results should follow these instructions.

1.	This model was built using the WEAP ("Water Evaluation and Planning" system) software.  Interested users will need to have this software installed and running before they can download and repeat the results of this project.  WEAP a be found at the following link. http://www.weap21.org/
2.	Click on the “Prasanna Dahal - Ryan James_LowerBearRiver_Spring2016_PacifiCorp.zip” link within the Spring-2016/PacifiCorp - Ryan&Prasanna GitHub repository.
3.	Click on the “Raw” button on the right hand side.
4.	Download and extract the file to wherever you have instructed WEAP to read and access files (Ex: for this project we assigned our model to a folder we titled “WEAP Areas” within out Documents folder, but any similar location will work providing it is the location that the WEAP software was instructed to look and load files during the software installation).
5.	Open the WEAP software.
6.	Go to Area > Open > and look for the folder “Prasanna Dahal – Ryan James_LowerBearRiver_Spring2016_PacifiCorp” you downloaded and extracted to the WEAP accessible folder.
7.	Once loaded, click on the “Results” button on the far left hand side.  This file contains over 30 scenarios, and will take time to run through and complete each scenario in order to view the results.
8.	Once the runtime has finished, users should be able to browse results at their leisure.


##Project Outline and Introduction

The Bear River, located near the border of Idaho, Wyoming and Utah, stretches 491 miles throughout the Uinta Mountains. The river is primarily used for irrigation throughout the area but does offer some recreational use through the three states of Idaho, Utah and Wyoming. Of its many uses, the Bear River is a source of hydroelectricity for the surrounding communities. The primary stakeholders in charge of Bear River power production PacifiCorp, a leading utility operators in the midwest US.  PacifiCorp has three primary purposes for the Bear River: hydropower production, flood control, and water supply through the Bear River Project (BRP).  The BRP is a series of rivers and reservoirs that generate a total of 77-megawatt (mw) worth of hydroelectric energy.  The BRP is largely dependent on the irrigation water diverted from Bear Lake, located in Northern Utah.  The BRP consist of three primary reservoir and dams for the production of hydroelectricity: Soda (Alexander), Grace, and the Oneida development.
The objective specific to the project is to evaluate and recommend reservoir operational policies to improve hydropower generation and decrease unmet water demand for downstream users. This will include suggestions on the weight of reservoir parameters such as reservoir filling priority, top of buffer, buffer coefficient, etc. to improve hydropower production, or to decrease downstream demand sites’ unmet water demand.


##Performance Metrics Used

####Definitions of Performance Criteria

Hydropower Generation:  Megawatts (MW). The amount of electrical energy produced by the dam when water is released. The objective is to maximize this value.

Unmet Water Demand:  Acre-foot (ac-ft). The target water delivery demand not met by the entire system. The objective is to minimize this value.

These metrics will be tested using the following methods: 1) changes in reservoir operation and release policy, 2) chaining the priority of energy production demand with respect to water delivery demand.

####How Performance Metrics Were Calculated:

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
