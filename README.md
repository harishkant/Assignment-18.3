# Assignment-18.3
Question 8: Consendering Age group of <20,20-35,35>,which age group spends the most amount of traveling.
sqlContext.sql("SELECT AgeGroup,Sum(Fare) TotalFare from AgeGroup Group by AgeGroup ORDER BY 2 DESC").show()

![q1](https://user-images.githubusercontent.com/34162166/37767632-c7610326-2df0-11e8-9816-edb650bf2ad2.png)



Question 9: What is the amount spent by each age-group,every year in travelling?

sqlContext.sql("SELECT AgeGroup,Year,Sum(Fare) TotalFare from AgeGroup Group by AgeGroup,Year ORDER BY 3 DESC").show()

![q2](https://user-images.githubusercontent.com/34162166/37767633-c79c9c24-2df0-11e8-9ee2-896fe56063da.png)

