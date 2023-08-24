# Unveiling-Kickstarter-Trends-An-Excel-Data-Analysis
<img src="images/back.JPG" width="1000" height="491">

## Introduction
Diving into 4,000 past Kickstarter projects, I aim to unveil trends and patterns. Using Excel, I analyse data, visualise outcomes, calculate success rates, and dissect categories. Insights about funding, donations, and timing emerge. Statistical analysis enriches understanding. Let's embark on this data journey.

## Source of Data
Within the Resources folder:
* CrowdfundingBook.xlsx

## Findings

1. The crowdfunding campaign category for theatre is by far the most prevalent, while journalism is the least prevalent as seen in the graph below:
   
![1](images/1.JPG)

2. The crowdfunding campaign subcategory for plays is by far the most prevalent, while world music is the least prevalent as seen in the graph below:
    
![2](images/2.JPG)

3. July tends to have many more successful crowdfunding campaigns while August has the least. January tends to have many more failed crowdfunding campaigns while September has the least as seen in the graph below:

![3](images/3.JPG)


![4](images/4.JPG)
4. If you look at the min and max values for both successful and unsuccessful, there is a massive range meaning that they are outliers. Because we used these outliers to calculate the mean, this would give us an inccurate result. So, the median best represents this data as it is a more exceptable value and is closer to 'most' of the dataset.

5. We can see that there is more varability with the successful campaigns based on the variance (how far the data is from the mean) and the standard deviation (how spread the data is from the mean). This distinction can be explained by the fact successful campaigns typically succeed as a result of a large number of backers who made sufficient pledges for campaigns to succeed. On the other side,  unsuccessful campaigns frequently had a low number of backers or none at all. Additionally, due to their huge backer counts, successful projects frequently surpass their objectives, however there are considerable differences amongst campaigns. As a result, almost all unsuccessful projects have a low backer count with little variance between campaigns, while many successful campaigns succeeded not just because they had more ambitious or realistic aims.


## Conclusion
Exploring the realm of Kickstarter campaigns through extensive data analysis has yielded significant insights into the dynamics of crowdfunding. The prevalence of certain categories and subcategories, such as theatre and plays, highlights the areas that garner the most interest and attention from backers. Additionally, understanding the temporal patterns of successful and failed campaigns provides a strategic advantage for campaign planning and execution.

The statistical analysis of the backers' numbers further refines our comprehension of crowdfunding outcomes. The median stands out as a more meaningful representation of data, considering the presence of outliers. This emphasises that the median better encapsulates the typical scenario, whereas the mean could be skewed by extreme cases.

Moreover, the analysis of variability in successful and unsuccessful campaigns sheds light on a crucial distinction. The diversity in backer counts for successful campaigns, leading to high variance and standard deviation, reflects their capacity to surpass goals due to a larger pool of backers. Conversely, unsuccessful campaigns often exhibit low variance, signaling limited backer engagement, which aligns with their inability to reach funding targets.

Overall, deciphering these Kickstarter trends refines strategic decision-making for campaigners and platform administrators alike. These insights are essential for optimising campaign approaches, refining resource allocation, and enhancing the crowdfunding experience for backers and creators alike.

## Limitations of this dataset?
Firstly this data set shows the average donation in different currencies which makes it hard to compare as they have different values. As this data is taken from over many years, it does not take into account for inflation for example, donating £1, 10 years ago is worth more than donating £1 today. This makes it hard to see which companies generated the most funding. 

The funding goal for various parent categories and subcategories also contain a number of deviations. While each crowdfunding campaigns has a "blurb," it would be beneficial to have additional and specific information about what each crowdfunding campaigns aims to achieve. Including both with very optimistic goals and campaigns with modest (or lower) goals in the same study may not be beneficial as it increases the range exceptionally which increases the chances of having lots of outliers. Thus, making the data unreliable. 

Also, for the outcomes there should only be ‘successful’ or ‘failed’. Having live data that is continually changing doesn’t do the dataset any good as it is incomplete. As well as having cancelled data, this is also like having incomplete data which is not useful for this dataset. Unnecessary data like ‘staff pick’ and ‘spotlight’ is not needed as it does not really have an influence if a campaign is successful or not. 

Finally, the dataset lacks information on the benefits that donors expect receiving in return for their contributions, for example a free sample of the product. If a donor feels like if they will receive anything meaningful in return for their donation, it may affect their decision to contribute.

## What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
1. For the companies that have failed in achieving their goals, we should have another table to see if we give them more time, would they be able to reach their goal.
2. A table showing an average timeline for a parent/sub-category to succeed in their goal.
3. Charts/graphs showing all the stats with and without "plays" as it is a very high outlier.
4. Pie charts for parent/sub-category to see which is the most successful in percentage and which is the least successful in percentage. From this we could create a success rate for each parent/sub-category. This could give us a clear indication foe which a parent/sub-category will generate the most revenue without taking into account the ‘amount’.
5. We can find the median, min, max and standard deviation for each campaign so that a bell curve can be generated and see what categories have the highest percentile in terms of reaching their goals (this can also be done for data outcome that have failed).
6. We can separate each data according to the country the campaign is in so that the tables generated are in the same currencies. Once each of them are made, we can convert all the currencies into one type of currency to easily identify which category generates the most donations. 


