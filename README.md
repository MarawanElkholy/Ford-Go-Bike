# Ford-Go-Bike

Dataset
The data consisted of prices and attributes of approximately 183,411 ford go bike trips . The Categorical Features included Membership,Gender,start station name,end station name and bike sharing feature as well as numerical Features such Duration, Start station longitude and latitude, End Station longitude and latitude and member birth year 16,623 points(rows) were removed from the analysis due to inconsistencies or missing information and distance was calculated from longitude and latitude.

Summary of Findings
In the exploration, I found that there was a strong relationship between the duratio and distance of trips i had to log tranform duration as it had a huge range that was hard to analyze and after that i started bivariate exploration and found out that there is an effect of gender and membership on duration and time also age groups seemed to affect duration and time slightly then i ran a multivariable analysis between all categorical variables and the 2 variables of interest and found out the following: 1- being a male subscriber with the bike sharing feature and between age group 27-19 and 32-28 (majority) decreases duration and distance

2 - being a male customer with no bike sharing feature seems to increase duration by a margin regardless of age group

3- being a female subscriber with bike sharing feature does decrease duration and distance regardless of age group

4- being a female customer without bike sharign feature seems to increase duration and distance regardless of age group

Outside of the main variables of interest, I verified the relationship between start and end station names and number of trips and found out that the top 5 start stations and the top 5 end stations are the same with a huge spike

Key Insights for Presentation
For the presentation, I focus on just the influence of the 4 categorical features Age, membership Gender and bike sharing feature and left out most of the intermediate derivations. I start by introducing the duration variable, followed by the pattern in distance distribution, then plot the scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start, I use the bar plots of duration and distance across bike sharing feature. The other two categorical variables, Membership and Gender, are covered afterwards, using heatmaps . then a huges treemap between all four categorical variables and duration and distance was made to conclude all possible variable effects on the 2 variables of interest duration and distance I've madesure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
