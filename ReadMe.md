 PROBLEM STATEMENT

"Apex Bank seeks to optimize services and retain customers by analyzing demographic and financial characteristics 
of its customers to inform effective decision making.


OBJECTIVES

. To explore and analyze the bank's customer and account dataset to uncover valuable insights on customer behaviour that inform the bank's decision making process.

. To identify trends and patterns in customer engagement .

. To understand financial standing of customers

. To  highlight potential areas for business improvement


 APPROACH

. Read in,understand and clean the customer and account dataset

. Explore and analyze the financial and demographic variables

. Visualize data to identify trends and patterns

. Develop insights and recommendations for business improvement


DATA DICTIONARY
	
 Field	                -                 Description

0.	CustomerId      -          A unique identifier for each customer

1.	Surname         -          The customer's last name

2.	CreditScore      -         A numerical value representing the customer's the customer's credit score.

3.	Geography        -         The country where the customer resides (France,Spain,Germany).

4.	Gender	         -         The customer's gender (Male or Female)

5.	Age	         -         The customer's age

6.	Tenure	         -         The number of years the customer has been with the bank

7.	Balance          -     	   The customer's account balance

8.	NumOfProducts	  -        The number of bank products the customer uses e.g(savings account,credit card)

9.	HasCrCard	   -       Whether the customer has a credit card (1 = yes,0=no)

10.	IsActiveMember     -  	   Whether the customer is an active member (1 =yes,0=no)

11.	EstimatedSalary	   -       The estimated salary of the customer

12.	Exited             - 	    Whether the customer has churned (1 = yes, 0 = no)

 



1-DEMOGRAPHIC ANALYSIS:


DISTRIBUTION OF CUSTOMERS BASED ON GEOGRAPHY , GENDER AND AGE:



GEOGRAPHY DISTRIBUTION	       	

RESULT:France has the highest customer distribution.Germany and Spain has similar values with Germany slightly higher.

![](Images/Geography_distribution_of_customers.png)


GENDER DISTRIBUTION	

RESULT:Male customers have a higher percentage of population(55%) than female customers(45%).

![](Images/Gender_distribution_of_customers.png)


AGE DISTRIBUTION	

RESULT:The highest number of customers is between  34-37 years old, while the  age group 88-92 has the least 

population.

![](Images/Age_distribution_of_customers.png)


WHICH GEOGRAPHICAL LOCATION HAS THE HIGHEST CREDIT SCORE?	

RESULT:Based on our analysis,by average Germany and Spain have the highest credit scores, followed closely by 

France.

![](Images/Geography_distribution_of_credit_score.png)


WHICH GENDER HAS THE HIGHEST BALANCE?

RESULT: The male gender has a higher account balance compared to the females.

![](Images/Balance_distribution_of_customers.png)


WHAT IS THE ESTIMATED SALARY BY GENDER AND GEOGRAPHY?		                  

RESULT:Male customers have higher estimated salaries than female customers in all geographical locations.

![](Images/Estimated_salary_by_gender_and_geography.png)


CUSTOMER ENGAGEMENT PATTERN

RELATIONSHIP BETWEEN CUSTOMER'S TENURE AND BANK'S PRODUCTS:

CREDIT CARD DISTRIBUTION

RESULT:In terms of credit card distributiom,slightly more than half of the customers have credit cards ,however there is a relatively small difference between credit card owners and non credit card owners.

![](Images/credit_card_distribution.png)


NUMBER OF PRODUCTS DISTRIBUTION BY TENURE	

RESULT:New customers (0years) own the lowest number of products,while customers with one and two years tenure 
own the highest number of products

![](Images/relationship_between_tenure_and_number_of_products.png)


CREDIT CARD DISTRIBUTION BY TENURE	

RESULT:

1. Highest demand for credit card are from customers with (1-2years) tenure.

2. There is a decline in credit card ownership among long term(10 years) customers.

4. New customers(oyear) tenure have the lowest demand for credit cards.

![](Images/credit_card_by_tenure.png)


COUNT OF ACTIVE MEMBERS

RESULT:The percentage of active members is slightly higher than non active members.

![](Images/percentage_of_active_members.png)


ACTIVE MEMBER DISTRIBUTION BY TENURE	

RESULT:

1. Active members are primarily concentrated in 1-2 years tenure range(1047 and 1035) respectively.

2. Members with 7years of tenure (1028),are almost as numerous as those with 1-2 years tenure.

3. Members with 10years are significantly fewer(490).

4. New members account for the smallest proportion(413).


![](Images/active_member_by_tenure.png)


BALANCE DISTRIBUTION BY TENURE	

RESULT:

1.Customers with 1-2 years tenure have the highest account balance.

2. Customers between(3-9) years tenure have relatively high balances.

3.Customers with 0 and 10 years have the lowest account balance.  

![](Images/balancedistribution_over_time.png)


FINANCIAL PERFORMANCE ANALYSIS

RESULT:

1.Middle aged individuals(34-38) have higher credit scores,while older adults (82-88) have lower credit scores.

2.Credit score peak around mid-life(34-38) and decline with age.

![](Images/credit_score_distribution.png)


CREDIT SCORE BY GEOGRAPHY	

RESULT:France has the highest creditscore among the three locations.Germany and Spain share similar values,with 
Germany slightly higher.

![](Images/credit_score_by_geography.png)


CREDIT SCORE BY GENDER	

RESULT:Male customers have higher percentage of creditscores compared to  female customers .

![](Images/credit_score_by_gender.png)


ESTIMATED SALARY BY AGE

RESULT:

1.Middle aged individuals(34-40) have higher estimated salaries,while older adults (81-88) have lower estimated salaries.

![](Images/Estimated_salary_by_age.png)


BALANCE DISTRIBUTION BY GEOGRAPHY	

RESULT:France has the highest balance in total,followed closely by Germany.Spain has the lowest balance in total.

![](Images/Balance_distribution_by_geography.png)


BALANCE DISTRIBUTION BY AGE	

RESULT:customers with the highest balance are between (34-37) years while customwers with the lowest balance are between(80-88) years.

![](Images/balance_by_age.png)



ACTIVE MEMBER DISTRIBUTION BY GENDER

RESULT:

1.Male customers dominate both active and inactive segments.

2.Female customers makeup a significant proportion of both active and inactive segment.

![](Images/Active_member_distribution_by_gender.png)


CHURN RATE ANALYSIS

RESULT:

1.A significant minority of customers(20%) have exited the bank,indicating room for improvement in customer retention.

2.While 80% of customers remains active suggesting a strong customer base.

![](Images/Churn_analysis.png)	


CHURN RATE BY GENDER

RESULT:A higher percentage (11.4%) of female customers have exited the bank more than male customers(9%)

![](Images/churn_rate_by_gender.png)


CHURN RATE BY GEOGRAPHY	

RESULT::Germany has the highest number of churned customers,followed closely by France.Spain has the lowest number of churned customers.

![](Images/churn_rate_by_geography.png)


CHURN RATE BY CREDIT SCORE

RESULT:This is a notable trend of high creditscore customers exiting the bank.This needs to be investigated.

![](Images/churn_rate_by_credit_score.png)


CHURN RATE BY CREDIT CARD OWNED

RESULT:Slightly more exited customers have credit cards,and approximately 50% of exited customers have credit cards.

![](Images/churn_rate_by_credit_card_owned.png)


CHURN RATE BY BALANCE DISTRIBUTION

RESULT:A substantial number of customers(3616) with 0 account balance have exited the bank,while few customers with high account balances have exited the bank.

![](Images/churn_rate_by_balance.png)


CHURN RATE BY AGE GRADE

RESULT:Middle aged customers(34-38 years)have higher exit rates,while older customers(82-92 years) have significantly lower exit rates.

![](Images/churn_rate_by_age.png)


CUSTOMER SEGMENTATION ANALYSIS
     The Following insights were drawn from analyzing the data:-

1. France has the highest customer distribution,creditscore and balance,while Germany and Spain share similar values with Germany slightly higher than Spain.In contrast,France has the lowest credit score by average with Germany and Spain topping the charts.

2. Germany has the highest number of churned customers(814),followed closely by France(810).Spain has the lowest number of churned customers(413).

3. Male customers leads with the highest etsimated salary,balance,population and creditscore than female customers.

4. We have a higher percentage of churned female customers,although the difference is minimal.

5. Our analysis also suggests that we have a higher percentage of active and inactive male customers than female customers.

6. The greater population of our customer base is between ages (34 - 37 years),while ages 88-92 has the least population.

7. Highest demand for credit cards are from customers with (1-2years) tenure,on the other hand new customers(0 year) tenure have the lowest demand for credit cards.There is a decline in card ownership by long term customers(10 years).

8. Slightly more than half(51.5%)  of the entire population of customers own credit cards,but there is a relatively small difference between credit card owners and non card owners(48.5%).

9. Customers with (1-2 years) tenure have the highest  balance, number of products and credit scores.While it's the opposite for (0 and 10 years) customers.

10. Middle aged customers(34-38 years) have higher credit scores and estimated salaries while older adults (82-88) years have lower credit scores and estimated salaries.

11. A significant minority of customers(20%) have exited the bank,indicating room for improvement in customer retention,while 80% of customers remains active suggesting a strong customer base.

12. There is a notable trend of high credit score customers exiting the bank that needs to be investigated.

13. Middle aged customers(34-37) years have higher exit rate, while older customers(82-92) years have significantly lower exit rates.

14. A substantial amount of exited customers(3616) have 0 account balance while approximately 50% of exited customers have credit cards. 

 RECOMMENDATION

1. Germany and France have a high customer exit rate that requires urgent attention to keeep customers and grow revenue.

2. Germany and Spain have high average credit scores and can boost growth by offering premium services to high credit customers e.g higher interest rates and copying France's successful strategies and adapting.

3. Investigate reasons behind female customer's higher exist rates and develop initiatives that cater to both male and female financial needs.

4. Low account balances and credit scores among (0 and 10 years) customers may explain their low credit card demand.Further investigation is recommended to confirm this analysis

5. Apex bank should offer personalized banking services and exclusive benefits to customers aged 34-38 with high credit scores,salaries and balances to increase loyalty and retention.

6. Inactive Accounts: Many exited customers didn't utilize their accounts.Reasons behind inactive accounts should be investigated if lack of usage led to exit.

7. Credit Card Usage:Half of exited customers had credit cards indicating unmet needs or dissatifaction.Credit card usage patterns among exited customers should be analyzed.Determine if credit card issues led to exit.

8. There is a notable trend of high credit score customers exiting the bank and potential reasons could be :- better offers from competitors e.g lower interest rates,unmet expectations for premium services or recognition etc.To retain customers and increase growth, Apex bank should check what competitors offer, to prevent customers from switching to better ideas,offer special benefits to reward loyal customers, build trust and foster relationships with customers and  introduce online banking services if none.
    In conclusion, by addressing these issues Apex Bank can:Prevent churn, build customer loyalty,retain high value customers and maintain a strong customer base.  
