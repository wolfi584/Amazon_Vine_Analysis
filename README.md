# Amazon Vine Analysis Challenge

## Analysis Overview
For this project I will have access to 50 different datasets from the Amazon Vine Review program. After choosing one dataset, I will be utilizing PySpark to conduct the ETL process (Extcract and transform  data, connect to AWS RDS instance, and load the data into PgAdmin). Following this process I will use the data to decide if there is any bias from favorable reviews from Vine members in the dataset. The final recommendation will help key stake holders to decide if paying for Vine Reviews is an opportunity cost, or a sunk cost. 

## Results
- Total of Vine reviews: 90
- Total of non-Vine reveiews: 40,471
- 5 star Vine reviews: 48 
- 5 star non-Vine reviews: 15,663
- Percentage of 5 star Vine reviews: 51.1% 
- Percentage of 5 star non-Vine reviews: 38.7%

## Summary
In conclusion I believe there is a slight positive bias for the offical Vine reviewers who are paid to try out a product and write a review. The non-Vine reviewers on Amazon seem to be more honest in their product reviews. Additional analysis can be conducted to challenge a null hypothesis by conducting this same analysis with different datasets (products) to see if the results are similar to this study. 


