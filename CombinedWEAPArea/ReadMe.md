**Description of Folder Contents**

Date |  Weap Area Name | Person | Stakeholder | Description of Modifications
--- | --- | --- | --- | ---
April 3, 2016  |LowerBearRiver-Spring2016-DataComplete    |David Rosenberg   |NA            |Base case version of the model
April 7, 2016  |LowerBearRiver-Spring2016-DataComplete    |Bryce and Tyler   |BRMBR         |No modifications to the model
April 10, 2016 |LowerBearRiver-Spring2016-DataComplete    |Rezaul and Sal   |BRCC         |No modifications to the model
April 11, 2016 |LowerBearRiver-Spring2016-DataComplete    |Nour and Mohamad   |Logan City       |No modifications to the model
April 12, 2016 |20160412 LowerBearRiver-Spring2016-DataComplete    |Prasanna and Ryan  |PacifiCorp       |Added three reservoirs to lower bear river
--------------------------------------------------------------------
**Stakeholder**: BRCC

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
Stakeholder: PacifiCorp

Performance Criteria: Measuring the amount of revenue generated ($/MWh) via hydropower at three reservoirs: Soda, Grace, and Oneida.  This will be tested with two methods: 1) observing changes in reservoir operation and release policy, 2) chaining the priority of energy production demand with respect to water delivery demand.

Changes to Model: Addition of three reservoirs to lower-bear river: Soda, Grace, and Oneida.  Each reservoir will have a storage capacity and a matching initial volume of water (assumption that reservoirs are full at start of model for convenience).  Max turbine flow for each reservoir and generating efficiency of turbines has been included.  Revenue generated via hydroelectricity included.

