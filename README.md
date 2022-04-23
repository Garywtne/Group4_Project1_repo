# Group4_Project1_repo
Project 1, Group 4, Shannon, Nathan, Maxwell &amp; Gary

# Hypothesis: Within the West Midlands during 2019 did the Index of Multiple Deprivation (IMD) Score of an area influence the exposure to certain crimes in that area.

## Research Question 1: Does the crime data sourced from the West Midlands Police Database correlate with the Index of Multiple Deprivation (IMD) score?

The IMD score is created with 7 domains of deprivation: Income (22.5%), Employment (22.5%), Education (13.5%), Health (13.5%), Crime (9.3%), Barriers to Housing & Services (9.3%), and Living Environment (9.3%). We expect that because crime is one domain used to create the IMD score that the crime rates in the LLSOAs should correlate with the IMD score. 
We also wanted to see if there are any outliers and what this would mean for those LLSOAs.

![image (3)](https://user-images.githubusercontent.com/85430216/164886609-087303b6-401a-477e-8785-93b3a9e89aeb.png)

![Crime Count all LSOA's VS IMD Score boxplot](https://user-images.githubusercontent.com/85430216/164886967-561b19d1-5d9a-4bf1-9eb0-2a8dc04d5a2b.png)

![Crime Count all LSOA's VS IMD Score](https://user-images.githubusercontent.com/85430216/164887045-2ce8530b-b358-4f24-b63d-5c4c848a3998.png)

A scatter plot was chosen as we are working with a large dataset. This plot highlights a few outliers which for the statistical analysis can be omitted for the sake of finding out whether there is a correlation between the LSOA crime count and LSOA IMD score. We have therefore reduced the y limits to 600 rather than over  4000 so that we can visualise any correlation and view the linear regression. 

![Crime Count all LSOA's VS IMD Score excluding outliers](https://user-images.githubusercontent.com/85430216/164887035-59cba2eb-6401-4719-aee9-b9f3f1a864f2.png)

The line of linear regression shows that there is a positive linear correlation but it is quite weak. 
The scatterplot shows that our hypothesis may not be correct. Whilst the amount of crimes increase the higher IMD score this is not uniform. There are also high crime rates in LSOAs with low IMD scores. 
We also recognise that crime is only one measurement used to create the IMD score.
We also decided to see if there was any difference in correlation when plotting each district individually.

We will then use this data to establish which areas are exposed to which crimes.

## Birmingham scatterplot to show LSOA crime count Vs LSOA IMD score

![image](https://user-images.githubusercontent.com/85430216/164882596-01420f6c-0160-4db2-8c39-70d360734b74.png)

The r value for the Birmingham scatterplot is lower than the r value for the total districts. This shows that there is an even weaker linear correlation and suggests that there would be more crime counts in areas with lower IMD scores. This plot also shows that for all areas regardless of IMD score there tends to be lower level of crimes.

# Boxplot
![Total LSOA crime in Birmingham 2019 boxplot](https://user-images.githubusercontent.com/85430216/164887787-9cb1b07e-5796-45f7-8a87-23c59962da68.png)

## Coventry scatterplot to show LSOA crime count Vs LSOA IMD score.

![image](https://user-images.githubusercontent.com/85430216/164882671-7a7c852b-581b-48c1-83d1-426725f5192d.png)

The Coventry scatterplot shows that there are fewer crimes in areas with a LMD score but there are also a significant proportion of LSOAs that see higher number of crimes the higher the LMD score. The r value for this plot is very similar to the overall district plot which shows a weak postive linear correlation.

# Boxplot
![Total LSOA crime in Coventry 2019 boxplot](https://user-images.githubusercontent.com/85430216/164887807-082e1c77-c6dd-482d-a361-67b813d08a31.png)

## Solihull scatterplot to show LSOA crime count Vs LSOA IMD score.

![image](https://user-images.githubusercontent.com/85430216/164882703-0119d1d3-0cb1-45c7-9e19-0b7e959573f5.png)

Solihull has a r value similar to the district plot as a whole. This shows that there is a weak positive correlation between LSOA IMD score and crime rate. There are more LSOAs that have a lower LMD score and low crime rate levels.

# Boxplot
![Total LSOA crime in Solihull 2019 boxplot](https://user-images.githubusercontent.com/85430216/164887820-c0e91395-5333-4529-9c36-30fedd152125.png)


## Sandwell scatterplot to show LSOA crime count Vs LSOA IMD score.

![image](https://user-images.githubusercontent.com/85430216/164882746-417f6675-5790-4ad5-8520-3a2abfec7359.png)

The Sandwell scatterplot shows that there aren't any LSOAs with an IMD score below 10. Despite this the r value shows the weakest correlation of all districts. This suggests that in Sandwell the crime count does not correlate with the IMD score and that crime occurs in all LSOAs - although this plot is similar to the other districts in that there are not many LSOAs that witness more than 300 counts of crime in 2019.

# Boxplot


## Walsall scatterplot to show LSOA crime count Vs LSOA IMD score.

![image](https://user-images.githubusercontent.com/85430216/164882772-4b91af6b-4a1e-499a-bd4d-4bd14f801013.png)

The Walsall r value shows the strongest positive liner correlation. This supports our hypothesis that the higher the IMD score the greater the crime count.

# Boxplot
![Total LSOA crime in Walsall 2019 boxplot](https://user-images.githubusercontent.com/85430216/164887841-363d7c6e-1836-42ec-a74a-c6995ea8997f.png)


## Wolverhampton scatterplot to show LSOA crime count Vs LSOA IMD score.

![image](https://user-images.githubusercontent.com/85430216/164882799-2a4aecf1-cd65-47a2-b94c-dcb6c348d79f.png)

Again, the Wolverhampton scatterplot is similar to the overall district plot. It shows a weak positive correlation with the majority of LSOA witnessing less than 300 counts of crime in 2019.

# Boxplot
![Total LSOA crime in Wolverhampton 2019 boxplot](https://user-images.githubusercontent.com/85430216/164887864-2b3c308d-322d-4004-ad3b-f5d359b7190e.png)


Overall, these scatterplots show that there is a weak positive correlation between LSOA Index of Multiple Deprivation score and crime count. Walsall has the strongest positive correlation and this supports our hypothesis. The other districts do not tend to have a significant majority of LSOAs that have crime counts higher than 300. Sandwell had the weakest linear correlation with higher counts of crime in all LSOAs. This highlights that not all areas with a high deprivation score have high crime counts, and vice versa, the areas with lower deprivation levels still see high levels of crime. 

We will continue this analysis by looking into which areas have higher rates of different types of crime. This may allow us to understand why we have not seen a strong positive correlation as expected.

# Research Question 2: Which district and Lower Layer Super Output Areas (LSOAs) have higher rates of crime?

![image](https://user-images.githubusercontent.com/85430216/164884192-2f272fd5-d394-48b0-ab95-99bc5cc5c2ea.png)

At a district level it is apparaent that in 2019 the crime rate in Solihull, which has a significantly lower district IMD score was slightly lower. But, in Coventry and Dudley where the District IMD scores are very close Coventry'c Crime rate was higher  

![image](https://user-images.githubusercontent.com/85430216/164882952-b97d3e23-d632-47dc-bbfe-5278521026ed.png)

The above bar plot shows that Birmingham sees the highest levels of crime by count but also shows that there is a higher percentage of crimes compared to the percentage of population in the West Midlands. This is also similar for Wolverhampton. This shows that the level of crime in Birmingham and Wolverhampton as districts is disproportionate to the population size. 
This bar chart also shows that it is significantly safer in Dudley and Solihull as the percentage of total crime is lower than the percentage of the total population.
We have used a heatmap to visualise the areas within districts that have a higher exposure to crime.

![image](https://user-images.githubusercontent.com/85430216/164882966-4501aab3-9286-47e5-b54d-3f2393a753f7.png)

This map visualises that there are higher crime rates in different areas. Here we can see that there are higher crime rates nearer the city centres, by universities, and near hospitals.

# Research Question 3: What type of crime might you be exposed to in certain Districts/LSOAs?

## Birmingham crime data

![image](https://user-images.githubusercontent.com/85430216/164883001-a899b73a-ec2c-4aff-bbb5-5b99f7ba47b8.png)

In Birmingham you are more likely to be exposed to violence and sexual offences which made up nearly a third of the crime in 2019. Anti-social behaviour and vehicle crime are the next two significant crime types in Birmingham.
We have chosen the LSOA with the highest crime rate in order to deeper dive into the data and see if we can find any patterns.

![image](https://user-images.githubusercontent.com/85430216/164883020-6bface6f-4c37-439f-a42b-7d64a4b566a7.png)

Interestingly, whilst violence and sexual offences make up a significant proportion of crimes, shoplifting has a slightly higher percentage. This means that in the LSOA area with the max crime count, shoplifting is the crime that you would be the most exposed to. Vehicle crime is significantly lower than Birmingham as a whole. We believe that the reason for this is due to this LSOA covering the area between Birmingham New Street and Birmingham Snow Hill station. There are a higher density of shops and less cars in the city centre.

## Coventry crime data.

![image](https://user-images.githubusercontent.com/85430216/164883054-c2e3defd-8e83-47d3-a9c4-af30d9e619a8.png)

The crime type in Coventry follows the same trend as the crime types in Birmingham. One notable difference, however, is the higher rate of bike theft. We will explore this further later on.

## Dudley crime data

![image](https://user-images.githubusercontent.com/85430216/164883080-cebb1dd3-a475-4c66-949f-dd2cea74426f.png)

This pie chart shows that Dudley has a higher rate of violence and sexual offences and burglary but is the least riskiest place to leave your bike. Again, this data shows that the crime types and the percentage of these crimes are similar to the other districts.

## Sandwell crime data

![image](https://user-images.githubusercontent.com/85430216/164883097-62780426-cf55-49a3-915c-ae3e19307e0e.png)

In Sandwell bike theft is also a very small percentage, but the percentage of violent and sexual offences is the second highest in the West Midlands. It made up over a third of crimes in 2019.

## Solihull crime data

![image](https://user-images.githubusercontent.com/85430216/164883128-fa675c40-285e-4834-ae12-8af46616f43b.png)

The violence and sexual offences rate in Solihull is still the most significant crime but the percentage is much lower than the other districts. The rate of vehicle crime, other theft, and burglary is higher than the other districts.
We decided to look into LSOAs for Solihull as it the crime data and IMD score did not behave in the way we expected. 

![image](https://user-images.githubusercontent.com/85430216/164883139-4fad29a1-ef5a-4e49-a8d7-4979394eba8b.png)

The area with the highest crime in Solihull shows us something interesting which does not reflect the overall pattern of crime types in the West Midlands in 2019, but it does correlate with the overall percentage of crime types in Solihull. The percentage of vehicle crime and other theft is much higher than other districts and the LSAO with the max crime rate in Birmingham. Interestingly possessions of weapons is another crime type with has a higher percentage than the other districts.

## Walsall crime data

![image](https://user-images.githubusercontent.com/85430216/164883166-16d86a80-4ce5-48d1-9c98-d593da6dd942.png)

The Walsall pie chart reflects the data from the other districts. There is nothing too dissimilar to the crime type percentages in the rest of the West Midlands.

## Wolverhampton crime data

![image](https://user-images.githubusercontent.com/85430216/164883184-f9a9b2d5-51b3-4269-9def-814ae43c2e97.png)

Wolverhampton has the highest percentage of violent and sexual offences in the West Midlands.
Overall: We found that despite the difference in IMD scores for each district the type of crime and the percentage of crime count in 2019 was mostly similar across the West Midlands. 
To test this we chose a sample of LSOA's with an IMD score of less than 5 to ascertain what types of crimes were committed in areas with low IMD scores vs high IMD scores.

![image](https://user-images.githubusercontent.com/85430216/164883200-a665e9de-25fd-4a9f-a4c4-2046a5161234.png)

This piechart shows that Burglary, Shoplifting, Criminal damage and arson is higher in LSOAs with lower IMD scores. Vehicle crime is massively higher in in LSOAs with lower IMD scores. However, Theft from person and public order crime is much lower than LSOAs with higher IMD scores.

# District Heatmaps

We have used heatmaps to further this point. The heatmaps plot all the crime for each district. So we can see how the crime is distributed geographically.

## Birmingham crime heatmap 2019

![image](https://user-images.githubusercontent.com/85430216/164883289-9d3eb354-291e-4d15-9b5b-22eb2345cc8d.png)

## Coventry crime heatmap 2019

![image](https://user-images.githubusercontent.com/85430216/164883334-57b580aa-b65a-4ad2-bea5-9f4b91165956.png)

## Solihull crime heatmap

![image](https://user-images.githubusercontent.com/85430216/164883352-b224c6de-ca7d-49ec-96cd-9e0ffd5f8fc2.png)

## Walsall crime heatmap 2019

![image](https://user-images.githubusercontent.com/85430216/164883369-57a31ba7-37bb-4ea2-ad75-3bbb8d5dd573.png)

## Sandwell crime heatmap 2019

![image](https://user-images.githubusercontent.com/85430216/164883381-15ea8d7d-1db2-4f37-b706-6d2f412f8960.png)

## Wolverhampton crime heatmap 2019

![image](https://user-images.githubusercontent.com/85430216/164883394-eabd10c2-9521-4ff9-be4e-18263870963a.png)

The above heatmaps show that crime was concentrated in the centres of the districts where we can assume that there are city centres and shopping centres. The heatmaps also show that there are smaller pockets of high crime rates in other areas within the districts. This is not entirely true for Birmingham, however, the city centre does follow this trend but there are pockets of high crime rates in many areas. This supports the other tests and visualisations so far which highlight that high crime rates tend to occur in city centres and around universities.
Interestingly this idea is evidently true for the crime type: bike theft. 

# Research Question 4: Where is the safest place to park your bike?

We have decided to focus on bike crime as the levels of bike crime are statistically less than other crimes in the West Midlands. We also notice on the heatmaps that there seemed to be a pattern in location of bike thefts.

![image](https://user-images.githubusercontent.com/85430216/164883492-1849054f-59a4-4250-9cd8-c0a671c8d987.png)

![image](https://user-images.githubusercontent.com/85430216/164883499-244bad89-3603-49b7-8207-5bbd37be307b.png)

We found that bike thefts are mainly focused around city centres with addititional area of concentrated crimes in and immediatly around Universities and student accommodation.

![image](https://user-images.githubusercontent.com/85430216/164884503-a24bb36c-a348-4c8f-907d-43b058860271.png)

Compared to the other districts Coventry has a much higher level of bike thefts and Dudley an unusally low level. So it may be safer to park your bike in Dudley or there may simply be less bikes.

# Conclusions 

There is a weak positive correlation between LSOA Index of Multiple Deprivation score and crime count. Walsall has the strongest positive correlation and this supports our hypothesis. The other districts do not tend to have a significant majority of LSOAs that have crime counts higher than 300. Sandwell had the weakest linear correlation with higher counts of crime in all LSOAs. This highlights that not all areas with a high deprivation score have high crime counts, and vice versa, the areas with lower deprivation levels still see high levels of crime. 

A lower IMD score does not mean that there will be less crime and a higher IMD score does not mean that there will be a higher crime rate. 

There are higher bike theft rates nearer the city centres, by universities, and near hospitals.

Each district in the West Midlands has a similar crime trend. Violent and sexual offences make up the largest proportion of crime for all districts. And the other types of crime also follow similar patterns.

Depending on which district and LSOA you are in you will witness different crimes, e.g. In Solihull you are more likely to witness vehicle crime or theft, whereas in Wolverhampton there are more violent offences. 

Wolverhampton has the highest rate of violent and sexual offences in the West Midlands.
