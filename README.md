The project is about data exploration and visualization of Olympic Games data. Here are the steps involved in the project:


• Data extraction:
The dataset utilized for our analysis is sourced from Kaggle. The dataset with 70,000 rows encompasses a wealth 
of information about the Olympics, including historical data, details about host cities, participating nations, and 
athletic achievements. This dataset serves as a valuable resource for uncovering patterns, trends, and insights that 
contribute to a nuanced understanding of the Olympics
The dataset comprises several key columns, each playing a role in providing a holistic perspective on the Olympic 
Games. The columns include:
1. ID: A unique identifier for each entry in the dataset.
2. Name: The name of the participating athlete.
3. Sex: The gender of the athlete.
4. Age: The age of the athlete at the time of the event.
5. Height: The height of the athlete.
6. Weight: The weight of the athlete.
7. Team: The name of the team to which the athlete belongs.
8. NOC: National Olympic Committee code, representing the country.
9. Games: Information about the specific Olympic Games, including the year and season.
10. Year: The year in which the Olympic Games were held.
11. Season: The season of the Olympic Games.
12. City: The host city for a particular edition of the Olympics.
13. Sport: The type of sport involved in a specific event.
14. Event: The specific event or competition within a sport.
15. Medal: The type of medal awarded (Gold, Silver, Bronze, or None).
These columns collectively provide a comprehensive dataset that allows for a detailed exploration of the Olympic 
Games over time, offering insights into historical trends, athlete performances, and the broader context of this 
global sporting event.


• Data Preprocessing:
The data preprocessing phase is crucial to ensure the quality and reliability of our dataset. In this step, we first 
dropped the initial column ID, as it did not contribute to the analysis. Next, we conducted a comprehensive check 
for missing values across all columns. The following columns were identified as having missing values:
- Age: 2732 missing values
- Height: 16254 missing values
- Weight: 17101 missing values
- Medal: 60310 missing values

- • Data Exploration:
The resulting dataset, free from duplicates and outliers, is ready for analysis. A pandas Data Frame is created with 14 columns and 49,211 rows, containing information about Olympic athletes. The statistical summary is calculated for the columns Year, Age, Height, and Weight, providing insights into the central tendency, distribution, and potential outliers of the data. Histograms are plotted to visualize the distributions of people by age, height, and weight over time. Box plots are generated to show the distribution of age, height, and weight for Olympic athletes grouped by year. A scatter plot is created to illustrate the relationship between height and weight, differentiated by gender. Finally, a pair plot examines the relationships between Year, Age, Height, Weight, and Medal in Olympic athletes, with each subplot color-coded by the type of medal won.

• Data Visualization:
Data visualization is a key aspect of the project. After preprocessing the dataset, the project aims to visually represent the data to gain insights and communicate findings effectively.











