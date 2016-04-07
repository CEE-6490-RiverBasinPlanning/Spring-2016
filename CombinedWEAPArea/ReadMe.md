Description of Folder Contents

Date |  Weap Area Name | Person | Stakeholder | Description of Modifications
--- | --- | --- | --- | ---
April 3, 2016  |LowerBearRiver-Spring2016-DataComplete    |David Rosenberg   |NA            |Base case version of the model
April 7, 2016  |LowerBearRiver-Spring2016-DataComplete    |Bryce and Tyler   |BRMBR         |No modifications to the model


--------------------------------------------------------------------
**Stakeholder**: BRMBR

**Definitions of Performance Criteria Statistical Evaluations**
Adapted from Loucks et. al., 2005

Reliability – the fraction of time the system is in a satisfactory condition. It is calculated as the number of monthly observations that is unsatisfactory, divided by the total number of monthly observations. 

Resilience – the likelihood that system will return to the satisfactory condition after reaching an unsatisfactory state. It is calculated as the number of times a satisfactory value follows an unsatisfactory value divided by the number of times and unsatisfactory value occurred. 

Vulnerability – is the magnitude of failure to be expected when the system reaches an unsatisfactory state. It is calculated as the sum of the positive value of the difference between the observed value and the target value, divided by the number of unsatisfactory monthly observations. 

Monthly percent of demand delivered weighted to bird use for that month - is the percentage of demand delivered weighted by the number of priority bird species that occupy habitat areas within BRMBR for that month. This metric creates a higher weight for months that have higher bird usage. For example, April and May have higher priority bird species use than June and July or December and January, thus, when unmet demand occurs for higher weighted months, a greater negative effect on the performance metric is incurred. 

**Description of Performance Metric Calulations**:
Reliability, resilience, vulnerability are calculated using a MATLAB script. Monthly percent of demand delivered weighted to bird use for that month is calculated using an excel spredsheet. Both calculations require export of the unmet demand results from WEAP. The calculation files can be found in our GitHub folder. 
