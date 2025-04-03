![Aircraft-Crashes-Fatalities-Analysis](https://github.com/user-attachments/assets/886d63a6-f484-417c-8e3c-d0a315d7b13b)
Dataset:
The dataset used for this analysis is "Air Crashes Full Data 1908 -2024," sourced from Kaggle https://www.kaggle.com/datasets/jogwums/air-crashes-full-data-1908-2023. This dataset provides a comprehensive historical record of airplane crashes worldwide, spanning from 1908 to April 2024, including details such as date, location, aircraft manufacturer, fatalities, quarter, and operator.
Overview
Aviation safety has significantly improved over the past century, with enhanced regulations, advanced technology, and stricter operational standards contributing to a steady decline in aviation-related fatalities. Despite these improvements, public perception often differs from statistical reality, especially when major accidents receive widespread media attention. According to CNN, while some recent high-profile crashes have fueled concerns, air travel remains one of the safest modes of transportation, with accident rates continuing to decrease (Enten, 2025). The dataset analyzed in this project provides an opportunity to examine historical trends in aviation fatalities, highlighting which aircraft manufacturers, countries, and airline operators have had the most significant accident records. Understanding these patterns can help improve aviation safety policies and risk mitigation strategies.

Objective
By conducting this analysis, I hope to answer the following questions:
Which aircraft manufacturers have had the most fatalities?


How have aviation fatalities fluctuate annually from 1908 to April 2024?


Which countries or regions have experienced the highest number of aviation fatalities?


How do fatalities differ between land and air crashes?


Which airline operators have recorded the most fatalities?



Analysis
1. Which aircraft manufacturers have had the most fatalities?
Visualization Used: Treemap


Purpose: This chart highlights the top manufacturers with the highest number of fatalities, allowing us to identify patterns related to aircraft design and operational history.


2. How have aviation fatalities fluctuated over time?
Visualization Used: Line Chart (Fatalities by Year, also used as a global filter)


Purpose: The line chart tracks fatalities over time, showing trends and significant fluctuations, such as spikes during war periods or declines due to safety advancements.


3. Which countries or regions have the highest aviation fatalities?
Visualization Used: Horizontal Bar Chart


Purpose: This chart ranks countries based on total aviation fatalities, providing insight into regional trends and potential infrastructure challenges.


4. How do fatalities differ between air crashes and ground-impact fatalities?
Visualization Used: Double Scatter Plot (Land vs. Air Fatalities)


Purpose: This visualization compares two types of fatalities:


Air Fatalities – Passengers and crew members killed in an airplane crash.


Ground Fatalities – People on the ground killed when an aircraft collided with a structure, building, or populated area.


5. Which airline operators have recorded the most fatalities?
Visualization Used: Pie Chart (Fatalities by Airline Operator)


Purpose: This pie chart highlights the proportion of total fatalities attributed to different airline operators, providing insights into airline safety records.


Additionally, a Total Fatalities KPI metric is included in the dashboard, which dynamically updates based on the year filter from the line chart, providing a quick snapshot of fatalities for the selected period.

Conclusion
This analysis provides a data-driven perspective on aviation fatalities over the past century. The treemap revealed which aircraft manufacturers were involved in the highest number of fatal accidents, while the line chart highlighted significant trends over time, including major declines in fatalities due to safety advancements. The bar chart pinpointed high-risk regions, and the scatter plot compared the severity of land and air crashes. Lastly, the pie chart showed which airline operators had the highest fatality rates.
Despite recent high-profile aviation incidents, CNN reports that air travel remains safer than ever, with 2025 marking one of the lowest accident rates in history (Enten, 2025). Future research could explore additional contributing factors to aviation accidents, such as weather conditions, mechanical failures, and human error, to develop more targeted safety interventions.



References

Dizikes, P. (2024, August 7). Study: Flying keeps getting safer. MIT News | Massachusetts Institute of Technology. https://news.mit.edu/2024/study-flying-keeps-getting-safer-0807 


Harry Enten. (2025, February 19). It feels like there are suddenly way more plane crashes and incidents. Here’s the truth. CNN Business. https://www.cnn.com/2025/02/19/business/airplane-crashes-statistics/index.html 


