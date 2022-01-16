**World Happiness Report: Exploratory Data Analysis **

So before jumping on the World Happiness Report, let's try to understand the World Happiness Index. So basically, the World Happiness Index is just a ranking based on how happy the citizen of a country consider themselves to be. About 156 countries are ranked based on this index.
The World Happiness Report is published by the United Nations Sustainable Development Solutions Network. It contains topics and measurements of world happiness, based on the responses of the respondents of their lives, a report that is also associated with a variety of (quality) life items.
If we talk about the report of this Happiness Index for the year- 2020, Finland has been named Happiest Country in the world for the fourth time in a row.
Now, you are wondering about the factors on which the Happiness score is calculated. Let’s talk about them in the next section.

**Factors based on which countries are ranked in the World Happiness Index**_

Every year, Only six factors are considered for the determination of the Happiness Score that is achieved by all the 156 countries and this score decides their ranking. These Factors are:
1.	Economy( GDP per Capita): the extent to which GDP contributes to the calculation of Happiness score.
2.	Social Support: this is the factor describing the extent of help available to an individual when he is in trouble.
3.	Health life expectancy: The extent to which Life expectancy contributed to the calculation of the Happiness Score
4.	Freedom to make life choices: The extent to which Freedom contributed to the calculation of the Happiness Score.
5.	Perceptions of corruption: The extent to which Perception of Corruption contributes to Happiness Score.
6.	Generosity: The extent to which Generosity contributed to the calculation of the Happiness Score.


**Analysis of the Year 2015–2019**
I think the introduction section is enough to make you understand what the World Happiness Index is. Now it's time to analyze the report based on the data collected. The dataset used for the analysis is from the Kaggle itself which has the data for the year 2015-2019.
This Exploratory Data Analysis has been done using Python and its libraries like Pandas, Matplotlib, Seaborn, Numpy, etc
 
Before starting the analysis in Python, you must import the required libraries. After importing the file, next should be importing the dataset and this can be done using the library ‘opendatasets’. Now you should assign the panda dataframe to each one of the CSV files.
The important thing to check the dataset that whether it has some null values on not. In case a dataset has null values in its columns, it must be handled either by imputing them or by removing them.
 The above image shows that none of the columns has null values. so it’s good for us.
Once we get confirmed about the existence of any null values. Let’s check the correlation matrix of the data. The following cell can be used for this purpose.
 
the output would be a heatmap showing the correlation matrix.
 
For the year 2015, the happiest country in the world is Switzerland

With the Help of the correlation Matrix, let’s try to analyze the columns for the other columns
From the  correlation matrix, we can have the following major Conclusion:
•	The happiness Rank has a negative correlation with the Happiness score.
•	Happiness Score has the highest correlation with Economy followed by family.
•	The economy has the highest Correlation with Health Expectancy.

**Economy vs Happiness Score
 **

The scatterplot shows that the Happiness score is linearly dependent on the Economy. The economy is playing an important factor. Country in which people are unable to afford even their basic needs because of the decreasing economy cant be happy. On the other hand, a country having a good economy almost achieved a good happiness score.

**Social Support vs Happiness score**
The Family have the same meaning as Social Support does
A family always makes a good environment around them. An environment of joy is always there. This fact is also explained by the fact. Having a family possesses happiness. The Plot shows that the Happiness score is almost linearly dependent on the Social Support factor.

 
For the years 2016, 2017,2018,2019 the same trend is followed and the correlation does not vary too much. Plots are also similar for the year 2016–2019. The correlation matrix for each year is shown in the Python Notebook.
For the year 2016, the happiest country in the world is Denmark
For the year 2017, the happiest country in the world is Norway.
For the year 2018, the happiest country in the world is Finland
For the year 2019, the happiest country in the world is Finland.
 
**Conclusion Made From this Trends**
1.	The economy plays an important role while calculating the Happiness Score. Higher the economy more will be the resource to fulfill in daily life.
2.	Social support is a factor that covers many other aspects. If there is better social support, mental health would also be good as there are supporters for the individual which keeps him motivated in every situation. So, the Health factor is also correlated with Social support.
3.	generosity is like giving your time, talent, or resources, and expecting nothing in return and it has been proven to be good for our health. Generous individuals are personally more fulfilled, happier, and more peaceful within themselves, not to mention more productive at home and in the workplace.

**Countries with strong social and institutional capital not only support greater well-being, but are more resilient to social and economic crises. **



