![Aircrafts Image](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/Aircrafts.png)
# Aviation Company Risk Analysis
## Overview
This project analyzes the risks involved in the running of an aircraft business. This is essential as the company is planning on expanding its portfolio by getting into that sector. In this notebook, we analyze a dataset that entails the logs of aircraft accidents that run from 1948 to 2022. The company will utilize this analysis in the allocation of resources machine procurement, operation and risk mitigation, so as to achieve the highest profitability and human safety in the sector.
## Business Problem
![Small Aircraft](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/AIrcraft_2.png)
The company may be able to realize where their resources will be most profitable and risk mitigative when beginning the aircraft business operations. This will make sure cost overruns resulting from accidents are reduced and safety to the staff and customers is enhanced. This will also result in business growth as resources can be redirected to expansion. Using Aviation Data provided which logs all accidents and their respective information, I use this project to define accident trends and possible causes to predict the company's sourcing for recommended aviation machinery, their maintenance and best working period with the least number of recorded accidents.
## Data
The aviation data that has been selected to be used in this analysis project has a list of recorded accidents that run from 1948. Every entry has a unique ID that distinguishes them from the rest. The aviation data provides information about the plane involved in the accidents (e.g. make, number of engines), as well as the situation surrounding the aircraft at the time of occurrence of the accident.
## Methods
This project uses descriptive analysis, including the description of trends over time. This provides a useful overview of aviation accidents to identify accident risks.
## Results
The following factors are the most prominent in accidents; having a single engine, a reciprocating engine type, traveling for personal purposes, as well as being in the landing phase of flight.
![Value Counts](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/value_counts.png)
The most common aircraft make involved in accidents is the Cessna.
![Aircraft Make Frequency](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/top_10_most_common_makes.png)
The data has a single peak in July with this having the highest number of recorded aircraft accidents.
![Number of Accidents by Month](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/number_of_accidents_by_month.png)
## Conclusions
This analysis leads to three recommendations for the upcoming aviation business enterprise:
 - **Take up aircrafts with more than one engine.** This ensures overall safety as in case of an engine failure, there is at least one backup engine which reduces the risk of accidents.
 - **Take up the Cessna model.** Though from the analysis these have the most recording of accidents, this can be attributed  to the single-engine type being more popular and thus ending up in more accidents. Therefore taking up the two-engined Cessna would prove to be safer.
 - **Make sure maintenance is regularly done especially on the landing gear and instruments.** Most accidents were clocked during the landing phase of the flights. This can be mostly attributed to faulty landing gear and instruments that are fundamental to an incident-free flight.
 - **Picking aircrafts which do not utilize the reciprocating engine type.** The reciprocating engine type is most prone to accidents since it is less powerful than the rest, such as turboprop. Selecting the other types will reduce the accidents that occur.
## Next Steps
Further analyses that could yield additional insights to further improve the aviation business are:
 - **Maintenance methods.** This modeling will enhance the maintenance methods and after implementation will reduce the number of maintenance-caused accidents.
 - **Pilot selection.** This modeling will show priority to experienced pilots to enhance the safety of the customers and limit accidents.
 - **Weather data analysis** This model will provide critical data on the different weather patterns and which of those can be handled by the aircrafts and which will need a halt in operations for passenger and aircraft safety.
## For More Information
See the full analysis in the [Jupyter Notebook](aviation_company_risk_analysis.ipynb).
## Repository Structure
