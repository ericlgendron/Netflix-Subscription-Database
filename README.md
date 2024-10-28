-- Query 1: Countries ranked by usage
	Observations:
    US is the highest revenue country
    UK has the highest average subscription amount

-- Query 2: Countries ranked by device
	Observations:
    Every country uses a Laptop the most
    Every country uses a Smart TV the least

--Query 3: Average Revenue per streaming service level
	Observations
    The Basic Subscription is the most popular
    The Premium Subscription is the least popular
    The Subscription costs are not fixed
    The Standard Subscription costs the least on average
    The Premium Subscription costs the most on average

--Query 4: Age by Country
	Observations
    The country with the oldest subscribers on average is the UK
    The country with the youngest subscribers on average is Brazil
    There is not much data variance with the minimum or maximum age, with the youngest for every country being 27, with the exception of the US being 26, and the oldest for every country being 51

--Query 5: Age by Device
	Observations
    The youngest subscribers use a smart TV, and the oldest use a laptop

--Query 6: Gender by Device
	Observations
    The most popular device for females is a Laptop, but the most popular device for males is a Smartphone
    The least popular device for females is a Smartphone, and the least popular device for Males is a Smart TV

--Query 7: Gender by Total Population
	Observations
    There are more female users than male users

--Query 8: Last Payment Date
	Observations
    For the sake of this study, the Churn Rate will be customers have not renewed their membership within the last 20 days, so users > 20 days will be flagged

--Query 9: Overall Churn Rate
  Observations
    The overall subscriber base has an average churn rate of 3.36%

--Query 10: Churn Rate by Country
	Observations
    Brazil has a substantially larger churn rate than most other countries, at 8.2%
    Canada has the lowest churn rate

--Query 11: Churn Rate by Gender
  Observations
    Females have a slightly higher churn rate than males

--Query 12: Churn Rate by Subscription Type
	Observations
    The Subscription Type with the highest churn rate is Premium, and the lowest is Standard

--Query 13: Churn Rate by Age
  Observations
    Best used as a scatterplot
    Seemingly no correlation between churn rate and age, as the highest churn rate (with the exception of the 1 outlier at 26) is for 45 year olds, at a 10.11% churn rate, and the lowest is for 48 year olds at .99

--Query 14: Churn Rate by Gender and Country
    Men in Canada have the lowest churn rate, and women in Brazil have the highest churn rate

--Query 15: Churn Rate by Device
  Observations
    People who use their smartphones more commonly have a higher churn rate, and people who use a Smart TV have the lowest churn rate

--Query 16: Churn Rate by Longevity
Observations
I have read other studies that have shown there isn’t much if any correlation between longevity and churn rate, but this might seem to suggest otherwise; however, there is limited data, so it would be unwise to make a conclusion based off the limitations, especially since the subscriber count is much less for longer months
