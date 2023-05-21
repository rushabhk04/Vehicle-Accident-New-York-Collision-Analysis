# Vehicle-Accident-New-York-Collision-Analysis



Vehicle collision analysis is significant because it helps increase road safety, assist emergency services, determine insurance premiums, improve infrastructure planning, aid in legal proceedings, enhance vehicle design, and raise public awareness of the dangers of the road.

I.	PROBLEMS
1.	Problem statement:
The first correlation reveals a critical finding regarding the geospatial distribution of vehicle accidents. This crucial discovery highlights the pressing need for targeted interventions and strategic policies aimed at mitigating the risks and reducing the frequency of accidents in these areas, thereby promoting road safety, and safeguarding the well-being of the local community.
2.	Problem statement:
The next analysis represents a pivotal step towards gaining a deeper understanding of the intricate relationship between driver distraction and the severity of vehicle accidents, by investigating whether there is a discernible correlation between the cause of the incident and the resultant level of damage sustained, including minor or major injuries. This multifaceted approach to accident analysis can potentially offer invaluable insights into the underlying mechanisms and contributing factors of vehicle accidents.
3.	Problem statement:
This correlation represents a crucial step towards identifying potential associations between the type of vehicle involved in an accident and the likelihood of sustaining injuries, particularly in the case of bicycles. By delving into the intricacies of the dataset and accounting for a range of relevant attributes, this analysis offers the potential to generate valuable insights into the multifaceted factors that contribute to vehicle accidents and their outcomes.
4.	Problem statement:
This analysis seeks to determine the potential impact of external factors such as weather and time of day on the frequency and severity of accidents. Understanding the relationship between these factors and accident rates can aid in the development of targeted interventions to reduce the occurrence of accidents during high-risk periods. This information can also be used by emergency services to prepare for and respond to accidents more effectively
Datasets Used: For the topic of Vehicle Collisions in NYC between 2015 and 2016, we shall be using the dataset available on Kaggle (https://www.kaggle.com/datasets/nypd/vehicle-collisions). The dataset contains 29 columns and more than 10,000 records. 
II.	SOFTWARE DESIGN AND IMPLEMENTATION:
Tools Used:
1.	No-SQL Database: MongoDB
We chose Mongo DB over the others because we found it provides the flexibility to store and process unstructured and semi-structured data. It allows for efficient and fast querying of large datasets, making it ideal for analyzing and deriving insights from vehicle collision data. Additionally, MongoDB's scalability and high availability features make it suitable for handling large amounts of data and ensuring that data is always available for analysis.

2.	Languages: 
Python , Pymongo (Python based)
3.	IDE’s: 
Jupyter Notebook, IntelliJ

4. Data Visualization tools: 

Python, Jupyter Notebook 
Software Design:
•	We imported the data from the public dataset to the MongoDB Compass creating a database and collections and connected to IDE’s using the IP connection.
•	We used the IntelliJ/Jupyter Notebook for querying directly from the database. We used aggregate pipeline to perform data filtrations.
•	We used the library Pymongo to connect the MongoDB database to the IDE and we used group, match and sort functions to develop complex queries to analyze
•	We used matplotlib.pyplot as plt for creating an interactive data analytics and visualization chart which gives better representational ideas on the data analysis process. Also, we used this to cross verify the analysis with the queries we have done, and it both has given promising results.

III.	PROJECT OUTCOME Solution 1: Correlation of geospatial conditions and accidents
The data reveals that Brooklyn, Queens, Manhattan, and Queens exhibit high numbers of accidents, while the Staten Island records comparatively low accidents.
When boroughs' mortality rates are compared, it becomes clear that Staten Island has the highest rate despite having fewer accidents. The fatality rates in the remaining boroughs, however, are comparable.
Additionally, there are differences in the injury rate between the boroughs, with Manhattan having the lowest injury rate and the Bronx and Brooklyn having the highest rates.
Based on the analysis, it can be inferred that Manhattan poses the lowest risk of injury and fatality in the event of an accident in comparison to other boroughs of New York. Conversely, an accident in Staten Island carries a higher probability of injury and fatality.

Solution 2: Contribution Factors Trends 
The data indicates that the primary contributing factor for accidents in New York is driver inattention/distraction. It has 25% chance of injruy and second highest cause of fatality.
Further analysis shows that failure to yield/right of way exhibits the highest rate of injury and fatality and is second highest factor for causing accidents. In contrast, accidents caused by driver fatigue/drowsiness or prescription medication usage carry no chance of fatality.
Additionally, accidents resulting from unsafe backing by drivers record the lowest injury rat 

Solution 3: Type of vehicle analysis
Passenger Vehicles are the vehicle types involved in the greatest number of accident, followed by Sedans and SUVs/Station Wagons. Bicycle and Motorcycle have an extreme rate of injury (>50%). Hence, it can be concluded that two wheelers are prone to injuries. Motorcycle, Bicycle, Bus, Large Commercial Vehicles have the highest rate of fatality. Hence, it can be concluded that vehicles of the extreme weights are more deadly.

Solution 4: Date/ Time and weather correlation
Upon analyzing the data, it was found that the highest number of accidents occurred during the weather conditions of 'Snow, Rain, partially cloudy', followed closely by clear weather. Similar trends were observed in the injury rate, with 'partially cloudy' weather conditions having the highest injury rate, followed closely by clear weather. Hence, there appears to be no significant correlation between weather conditions and total accidents, and similarly no correlation between weather conditions and accident injury rate.
In terms of accident fatality rate, the weather conditions of 'Partially cloudy' and 'Rain, partially cloudy' showed the highest rate of fatality. However, clear weather conditions also followed closely behind, indicating that there may not be a significant correlation between weather conditions and accident fatality rate.
From this we can conclude that in New York city weather doesn't play a significate role for causing accidents, injury, or fatality in accidents.


Graphs and Results:-
This interactive chart displays the entire dataset, and its columns were transformed, cleaned, and linked to generate this visual representation. The chart's filters can be easily modified, allowing for customized analysis based on specific criteria.




