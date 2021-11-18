Performance analysis of tennis players over the decades

Members of Group 4:
Harikrishnan Sundaram 
Malhar Joshi
Dhruv Jani
Yash Chaudhari 


AIM OF THE PROJECT:
To draw insights from a Tennis dataset w.r.t players age and correlation with the win and loss trend and analyzing the change in participation and performance of the tennis players from major countries like USA, UK, etc. In the earlier days of Tennis, the players would retire by the age of 30, but in recent times, the players have been playing at the age of around 35 and performing well. We will be analyzing the change in the pattern of participation Among the tennis players.

RESEARCH QUESTIONS:
What is the win percentage of players having the age in the range of 20-25, 25-30, 30-35 vs 35 and above for male and female players?
What is the different winning percentage of a player from a specific country on different surfaces?
The percentage of wins between players from the US vs other popular countries and between age groups ranging from 20-25, 25-30, 30-35 vs 35 and above.
What factor is influencing the change in the trend of all male and female players winning the championship? If it's the surface, the age, or some other reason.


ANALYSIS:
For this project we will be using Descriptive Analysis. Descriptive analysis is the process of using statistical techniques to describe or summarize a set of data. It is popular for its ability to generate accessible insights from otherwise uninterpreted data.



Data Preprocessing Steps
We have established steps we’ll need to go through to make sure our data is successfully preprocessed.

1. Data quality assessment

2. Data cleaning

3. Data reduction


**1. Data quality assessment**

First we take a good look at our data and get an idea of its overall quality, relevance to our project, and consistency. There are a number of data anomalies and inherent problems to look out for in almost any data set, for example:

Mismatched data types: When you collect data from many different sources, it may come to you in different formats.

Mixed data values: Perhaps different sources use different descriptors for features – for example, man or male. These value descriptors should all be made uniform.

Data outliers: Outliers can have a huge impact on data analysis results.

Missing data: Take a look for missing data fields, blank spaces in text, or unanswered survey questions. This could be due to human error or incomplete data. To take care of missing data, you’ll have to perform data cleaning.

Since all our data comes from a single source we can conclude that there are no inconsistencies with respect to the quality, data types and data values.


**2. Data cleaning**

Data cleaning is the process of adding missing data and correcting, repairing, or removing incorrect or irrelevant data from a data set. Dating cleaning is the most important step of preprocessing because it will ensure that your data is ready to go for your downstream needs.

Data cleaning will correct all of the inconsistent data you uncovered in your data quality assessment. Depending on the kind of data you’re working with, there are a number of possible cleaners you’ll need to run your data through.

Missing data There are a number of ways to correct for missing data, but the two most common are:

Ignore the tuples: A tuple is an ordered list or sequence of numbers or entities. If multiple values are missing within tuples, you may simply discard the tuples with that missing information. This is only recommended for large data sets, when a few ignored tuples won’t harm further analysis.

Manually fill in missing data: This can be tedious, but is definitely necessary when working with smaller data sets.


**3. Data reduction**


The more data you’re working with, the harder it will be to analyze, even after cleaning and transforming it. Depending on your task at hand, you may actually have more data than you need. Data reduction not only makes the analysis easier and more accurate, but cuts down on data storage.

It will also help identify the most important features to the process at hand.

Attribute selection: Similar to discreditization, attribute selection can fit your data into smaller pools. It, essentially, combines tags or features, so that tags like male/female and professor could be combined into male professor/female professor.

Numerosity reduction: This will help with data storage and transmission. You can use a regression model, for example, to use only the data and variables that are relevant to your analysis.

Dimensionality reduction: This, again, reduces the amount of data used to help facilitate analysis and downstream processes. Algorithms like K-nearest neighbors use pattern recognition to combine similar data and make it more manageable.



Few of the graph analysis below:



![image](https://user-images.githubusercontent.com/69467542/142350967-0f581904-3d69-4718-8ec1-13449f27ed33.png)

The above graph gives a view of country vs surface which can help us understand which country plays better on which surface. This can help us understand where players of a certain country need to improve. Eg: USA plays very good on Hard surfaces as compared to Grass. This shows us that players in United States need to focus on Grass courts more.


![image](https://user-images.githubusercontent.com/69467542/142350358-4aa9d45e-66a9-40b0-ab00-d006e42d1467.png)

The above graph gives a view of age vs year of male players, which shows us which age group performed well given an year. The colors represent the following

1. Blue : Ages 20 to 25

2. Red: Ages 25 to 30

3. Green: Ages 30 to 35

4. Orange: Ages 35 and above

As we can see, players between the ages of 25 and 30 had consistent wins in games as compared to other age groups.

Age group 20 to 25 had some years with higher win percentage but weren't consistent for long.

Age groups 30 to 35 and 35 and above had the worst win percentages.




![image](https://user-images.githubusercontent.com/69467542/142350441-24443c6d-f79f-4d12-a656-7dc22712d648.png)

The above graph gives a view of age vs year of female players, which shows us which age group performed well given an year. The colors represent the following

1. Blue : Ages 20 to 25

2. Red: Ages 25 to 30

3. Green: Ages 30 to 35

4. Orange: Ages 35 and above

We can conclude that female players are more likely to win when they are in the age group of 20 to 25, not consistent, but this age group has the maximum wins overall.

Female players are leaste likely to play and win with age above 35.




FURTHER ANALYSIS WILL BE DONE USING VARIOUS DECRIPTIVE ANALYSIS METHODS PROVIDED DURING THE MODEL PLANNING. WE TEND TO INCLUDE MANY MORE GRAPHS AND CHARTS TO UNDERSTAND WHY CERTAIN FACTOR IS INFLUENCING THE CHANGE IN THE TREND OF ALL MALE AND FEMALE PLAYERS WINNING THE CHAMPIONSHIP.






Data Resources: 
https://github.com/JeffSackmann/tennis_atp

https://github.com/JeffSackmann/tennis_wta

Project Github:- 

https://github.com/harishsundaram07/KnowledgeDiscoveryInDatabases_Group4_Project.git


 


