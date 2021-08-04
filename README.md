# Amazon_Vine_Analysis


## Overview

In this project I am analyzing video game reviews on Amazon. For this analysis, I will be looking in to the Amazon Vine - which is a program used by Amazon to highlight reviews of their most "trusted reviewers -  program to determine whether there is a difference in 5-star reviews from customers who are paid for their reviews and customers that are not paid for their reviews. 

Using Google Colab and PySpark, I will extract, transform, and load (ETL) utilizing AWS RDS connected to pgAdmin.
## Software

Python
MRJob \
ApacheSpark \
PySpark \
Google Colaboratory \
Hadoop \
MapReduce \
NLP \
pgAdmin
AWS 

## Results

- Total number of reviews (Paid and non-paid):
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/total%20reviews.png)


- Total Vine Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/total_paid_reviews.png)


- Total NonVine(Non paid) Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/total_unpaid_reviews.png)


- Total 5-star Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/total_five_reveiws.png)

- Total 5 Star Vine Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/toatl_5_unpaid.png)


- Total 5 star NonVine(Non paid) Reviews:
![image]()


- Percentage of 5-star Vine Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/percent_5_paid.png)


- Percetage of 5-star NonVine(non paid) Reviews:
![image](https://github.com/roderickspells/Amazon_Vine_Analysis/blob/main/images/percent_5_unpaid.png)




## Summary 

There are a total of 15663 non paid 5-star reviews and 48 paid -star reviews. All though there is a huge discrepancy between the number of paid and non paid reviews the percentage of 5-star ratings to lower ratings is higher within PAID reviews than NONPAID reviews.

According to the analysis above, 51% of reviews in the Amazon Vine Program were 5-star (Those who were paid to provide a review for a particular product. Whereas only 39% of customer who weren't paid, gave a 5-star review. This indicates a positive bias for positive reviews for those that were paid to provide a review. To further determine if there is a statistically correlation, I could run a statistical distribution to give more insight into the mean, median, mode, and standard deviation of the data set. All though I have 40,565 total reviews adding more data to the population could help understand if there is a true bias or if the discrepancy is due to random chance.


