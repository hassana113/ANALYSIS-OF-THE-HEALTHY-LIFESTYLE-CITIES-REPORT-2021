# ANALYSIS-OF-THE-HEALTHY-LIFESTYLE-CITIES-REPORT-2021
A complete analysis of the healthy lifestyle cities report 2021 using Microsoft Excel. 


----
# Project Objective: Problem Statement
The aim of this project is to perform an in-depth analysis of the Healthy lifestyle cities report 2021 and to answer the following questions;

1.	What are the Top 2 cities with the most life expectancy?
2.	What city has the highest Number of take-out places?
3.	What city raked in the most Cost of a monthly gym membership and Cost of a bottle of water?
4.	What American city has the most Outdoor activities?
5.	What are the top 10 cities with the most Pollution index score?
6.	What 5 cities have the most Sunshine Hours?
7.	What are the cities with the most and least Happiness levels?

#### The tool used to clean, explore and visualize the dataset is Microsoft Excel
The Rank in the datasets will be ignored and more attention will be placed on the variables to find the relationships in the dataset.

----
# Data Sourcing
The dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/prasertk/healthy-lifestyle-cities-report-2021) and imported into Microsoft Excel. 44 cities across the globe were analyzed by the team at Lenstore across 10 healthy living metrics. You can read more about the dataset [here](https://www.lenstore.co.uk/research/healthy-lifestyle-report/) .


---
# Data Cleaning
The dataset was imported into Microsoft excel and it contained 45 rows and 12 columns.
The column width was increased, Misspellings and Duplicates were checked for and removed. The Find and Replace features in Microsoft Excel were used to replace the cells with ‘-’ to ‘0’, thus, making the cells uniformly numeric. The fonts of the headers were edited, the Table formatted and renamed. The values in column D and L; Cost of a bottle of water and the Cost of a monthly gym membership respectively, were changed to numbers/currency as they were initially saved as text. 
![healthy lifestyle cities report](https://user-images.githubusercontent.com/105663796/195101374-fad9ad2a-a6f3-4338-8916-87d9e3ba638e.jpg)

---
# Exploratory Data Analysis (EDA)
To dig further into the data, Exploratory Data Analysis was performed. 
A starting point for the EDA was to perform descriptive statistics. This was done to offer a concise overview of how different observations in the dataset are distributed.
**Descriptive statistics** was performed to summarize and describe the characteristics of the dataset.
![Descriptive statistics](https://user-images.githubusercontent.com/105663796/195101771-70e14ced-ed31-4b24-958d-0b31d2f6ac2f.jpg)

To further analyze the relationship within the datasets, **Correlation Matrix** was created using the data analysis tool pack in Microsoft excel.
Half of the matrix is complete, this is because the results would be the same if the empty cells are calculated.
![Correlation Matrix](https://user-images.githubusercontent.com/105663796/195101841-f5d3a8df-384f-48d8-a58c-f658c84f5313.jpg)

More analysis was performed using pivot table to answer the following questions;
1.	What are the Top 2 cities with the most life expectancy?
2.	What city has the highest Number of take-out places?
3.	What city raked in the most Cost of a monthly gym membership and Cost of a bottle of water? 
4.	What American city has the most Outdoor activities?
5.	What are the top 10 cities with the most Pollution index score?
6.	What 5 cities have the most Sunshine Hours?
7.	What are the cities with the most and least Happiness levels?

---
# Findings
1.	From the Descriptive Statistics, The columns; Sunshine hours, Pollution (index score), and Annual Avg. Hours worked, all have a min value of  ‘0’. This is because initially the columns contained a ‘-‘ and was then replaced by ‘0’ during the data cleaning stage. Hence, ‘0’ represents the smallest number in each column

2.	The following conclusions can be drawn from the Correlation matrix; The two positive correlations include;
- Happiness levels and Cost of a bottle of water
- Happiness levels and Life Expectancy

This means, Happiness levels are greater in cities with a high life expectancy and a high cost of living. The increase in the Cost of a bottle of water may stipulate that the residents can actually pay that much for an indispensable item, which could also mean the residents earn at least a high wage, hence, a high standard of living, which would definitely boost happiness levels.

While the negative correlations include;
- Cost of a bottle of water and Pollution (index score)
- Life expectancy and Pollution (index score). 
- Pollution (index score) and Happiness levels.

This means, Life expectancy and Happiness levels are lower in cities with high Pollution levels. High levels of Pollution suppresses economic growth, heightens poverty and is the largest cause of disease and premature death.



3.	What are the Top 2 cities with the most life expectancy?
![image010](https://user-images.githubusercontent.com/105663796/195103049-d6e70975-26f1-48c9-867e-b735386ae239.png)

4.	What city has the highest Number of take-out places?
![image011](https://user-images.githubusercontent.com/105663796/195103108-d79118fd-3a33-42b3-94e6-8b45f6c3a713.png)

5.	What city raked in the most Cost of a monthly gym membership and Cost of a bottle of water? 
![image012](https://user-images.githubusercontent.com/105663796/195103213-b5cf7d3c-efb3-4376-8f03-724268a848e1.png)

6.	What American city has the most Outdoor activities?
![Untitled](https://user-images.githubusercontent.com/105663796/196054609-bf277ba1-359f-4e56-b5c7-426ea58c82de.jpg)

7.	What are the top 10 cities with the most Pollution index score?
![image014](https://user-images.githubusercontent.com/105663796/195103401-b79a7a61-ea7d-4be1-9ea0-12f82713ef27.png)

8.	What 5 cities have the most Sunshine Hours?

![image015](https://user-images.githubusercontent.com/105663796/195103467-02777d45-2ee3-4ccc-bd77-cb92783db08a.png)

9.	What are the cities with the most and least Happiness levels?
![image016](https://user-images.githubusercontent.com/105663796/195103521-6f03d936-8909-4c8a-8568-32924f0d2126.png)

---
# Data Visualization
Excel Dashboard
![DASHBOARD](https://user-images.githubusercontent.com/105663796/196054629-2eede3a9-70eb-4548-8456-07b7dc65095c.jpg)



---
# Limitations
1.	The dataset was not easily manipulated or analysed because of the missing data, mostly in 13 cells.
2.	It was difficult coming to a generalized finding because the dataset contains just 44 cities and not every city in the world.

---
# Conclusions:Key Takeaways
1.	Zurich with Geneva, located in Switzerland and Tokyo with Fukuoka, located in Japan, are cities with the most Happiness levels, Life expectancy and Cost of bottle of water.

2.	The Top 10 Polluted cities are not among the cities with the most happiness levels, life expectancy and Cost of bottle of water.


---
# Relevant Links
- [LinkedIn](http://linkedin.com/in/hassana-abdulkadir-1639301b8)
- [Portfolio Website](https://hassana113.github.io)
- Link to Medium article









