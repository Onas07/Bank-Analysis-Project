 PROBLEM STATEMENT
"Apex Bank seeks to optimize services and retain customers by analyzing demographic and financial chacacteristics of its customers to inform effective decision making.



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

         Field	                 Description
0	CustomerId -          	 A unique identifier for each customer

1.  Surname   -           	   The customer's last name


2.	CreditScore -        	A numerical value representing the customer's the customer's credit score.


3.	Geography	 -           The country where the customer resides (France,Spain,Germany).


4.	Gender	-                The customer's gender (Male or Female)

5.	Age	    -                The customer's age

6.	Tenure	-                The number of years the customer has been with the bank

7.	Balance -             	The customer's account balance

8.	NumOfProducts	-        The number of bank products the customer uses e.g(savings account,credit card)

9.	HasCrCard	 -           Whether the customer has a credit card (1 = yes,0=no)

10.	IsActiveMember -      	Whether the customer is an active member (1 =yes,0=no)

11.	EstimatedSalary	        The estimated salary of the customer

12.	Exited               	Whether the customer has churned (1 = yes, 0 = no)

INSIGHTS

1-DEMOGRAPHIC ANALYSIS:

Distribution of customers based on gender,geography and age:


GEOGRAPHY DISTRIBUTION	       	

Geography  -  CustomerId	

France	   -   5013

Germany	   -   2508

Spain	    -  2476

RESULT:France has the highest customer distribution,Germany and Spain has similar values with Germany slightly higher.

![](Geography distribution of customers.png)


GENDER DISTRIBUTION	

Gender-	CustomerId

1-Female	4541

2-Male	5456

RESULT:Male customers have a higher percentage of population(55%) than female customers(45%).


![](Gender distribution of customers.png)


AGE DISTRIBUTION	

Age	-CustomerId

37	-478

38	- 477

35	- 474

36	-456

34-	447
...	...
92	- 2

82 -	1

83-	1

85-	1

88-	1


RESULT:The highest number of customers is between ages 34-37 years, while age 88-92 have the least population.

![](Age distribution of customers.png)


WHICH GEOGRAPHICAL LOCATION HAS THE HIGHEST CREDIT SCORE?	

Geography -  CreditScore	

France	 -    649.69

Germany	 -    651.48

Spain	  -   651.32

RESULT:Based on the above analysis,by average Germany and Spain have the highest credit scores, followed closely by France

![](Geography distribution of credit score.png)


WHICH GENDER HAS THE HIGHEST BALANCE?

Gender -	Balance

Female -	343,579,164.57

Male -	421,018,185.46

RESULT: The male gender has a higher account balance compared to the females.

![](Balance distribution of customers.png)


WHAT IS THE ESTIMATED SALARY BY GENDER AND GEOGRAPHY?		                  

Gender-	      Geography	 -          Estimated Salary

Female  -    	France	       -          225,034,644.94
             
              Germany       -      	    122,118,396.55
             
               Spain         -       	109,699,443.04

Male	   -      France	      -             275,779,717.12
                
        -         Germany      -       	131,475,024.69
                
         -        Spain	       -         136,514,723.55

RESULT:Male customers have higher estimated salaries than female customers in all geographical locations.

![](Estimated salary by gender and geography.png)


CUSTOMER ENGAGEMENT PATTERN

Relationship between customer's tenure and bank's products:

CREDIT CARD DISTRIBUTION

HasCrCard

Yes -   5149

No  -   4848

RESULT:From our analysis,slightly more than half of the customers have credit cards ,however there is a relatively small difference between credit card owners and non owners.


![](credit card distribution.png)


NUMBER OF PRODUCTS DISTRIBUTION BY TENURE	

Tenure	NumOfProducts

2	 -       1047

1	 -       1035

7	   -     1028

8	    -    1025

5	   -     1012

3	   -     1008

4	    -    989

9	   -     984

6	     -   966

10	   -     490

0	    -    413

RESULT:New customers (0years) have the lowest number of products(413),while customers with one and two years tenure own the highest number of products

![](relationship between tenure and number of products.png)


CREDIT CARD DISTRIBUTION BY TENURE	

Tenure	   HasCrCard

2	  -   1047

1	 -    1035

7	  -   1028

8	  -   1025

5	 -    1012

3	  -   1008

4	   -  989

9	   -  984

6	  -   966

10	  -   490

0	  -   413

RESULT:

1. Highest demand for credit card are from customers (1-2years):This suggests that new customers are more likely to apply for credit cards possibly due to initial financial needs,building credit history and attractive promotional offers

2. There is a decline in credit card ownership among long term customers:This could indicate-customer's loyalty and stability,reducing the need for new cards,changing financial priorities(e.g mortgage or family).


3. potential churn or dissatifcation with existing credit cards.


4. New customers(oyears) tenure have the lowest demand for credit cards:This is expected as new customers may not yet have explored various credit card options,or may have not established credit history,or maybe cautious in applying for credit cards


![](credit card by tenure.png)



COUNT OF ACTIVE MEMBERS

IsActiveMember

Yes   - 5149

No   -  4848

RESULT:The number of active members(5149) is slightly higher than non active members(4848).The difference is approximately 301

![](percentage of active members.png)


ACTIVE MEMBER DISTRIBUTION BY TENURE	

Tenure	- IsActiveMember

2	  -   1047

1	  -   1035

7	  -   1028

8	  -   1025

5	  -   1012

3	  -   1008

4	  -   989

9	   -  984

6	  -   966

10	  -   490

0	   -  413

RESULT:

1. Active members are primarily concentrated in 1-2 years tenure range(1047 and 1035) respectively.

2. Members with 7years of tenure (1028),are almost as numerous as those with 1-2 years tenure.

3. Members with 10years are significantly fewer(490).

4. New members account for the smallest proportion(413).


![](active member by tenure.png)


BALANCE DISTRIBUTION BY TENURE	

Tenure	    Balance

1	-       81304822.67

2 -      	80527928.54

8	-       79885013.21

3	-      78225722.99

7 -     	77667080.19

5 -     	77361612.23

9 -    	  75337543.31

4 -     	73244740.73

6 -      	71828419.11

10	-       36224476.96

0 -     	32989990.09

RESULT:

1.Customers with 1-2 years tenure have the highest account balance.

2. Customers between(3-9) years tenure have relatively high balances.

3.Customers with 0 and 10 years have the lowest account balance.   

    Longer tenure customers tend to acquire more wealth and hold more products,however the relationship is not entirely linear because customers with 10 years tenure have surprisingly low balances.

![](balance distribution over time.png)


FINANCIAL PERFORMANCE ANALYSIS

CREDIT SCORE DISTRIBUTION BY AGE GRADE	

Age	 CreditScore

38 -	313702

37 -	311550

35 -	304474

36 -	298749

34 -	290837

...	...

84 -	945

85 -	787

82 -	700

83	- 678

88 -	51

RESULT:

1.Middle aged individuals(34-38) have higher credit scores,while older adults (82-88) have lower credit scores.

2.Credit score peak around mid-life(34-38) and decline with age.



![](credit score distribution.png)




CREDIT SCORE BY GEOGRAPHY	

Geography    -	CreditScore

France	  -       3256899

Germany   -        1633923

Spain	   -       161268

RESULT:France has the highest creditscore among the three locations,Germany and Spain share similar values,with Germany slightly higher.

![](credit score by geography.png)


CREDIT SCORE BY GENDER	

Gender	- CreditScore

Male -	3547887

Female -	2955615

RESULT:Male customers have higher percentage of creditscores(54.6%),compared to the female customers(45.4%) .

![](credit score by gender.png)


ESTIMATED SALARY BY AGE

Age	- EstimatedSalary

37 -	  47,111,581.96

40 - 	47,103,438.57

38 -   	46,233,241.66

35  - 	45,997,974.90

34  -	45,053,137.92
...	...

81	 - 227,455.83

82 - 	182,055.36

85 - 	116,537.96

83	- 92,934.41

88	 -52,952.24

RESULT:

Middle aged individuals(34-40) have high estimated salaries,while older adults (81-88) have lower estimated 
salaries.

Middle adults in their productive years tend to have higher earning potential,unlike older adults who are likely retired or semi retired.

![](Estimated salary by age.png)



BALANCE DISTRIBUTION BY GEOGRAPHY	

Geography	 - Balance

France	    -  311,332,479.49

Germany	   -    300,261,511.95

Spain	     -  153,003,358.59

RESULT:France has the highest balance in total,followed closely by Germany.Spain has the lowest balance in total.

![](Balance distribution by geography.png)


BALANCE DISTRIBUTION BY AGE	

Age -	Balance

37 - 	38,266,130.63

35  -	36,692,532.78

38  -	35,905,029.90

33	  - 33,790,452.49

40  - 	33,275,087.69

...	...

81	-  122,029.15

80  -	0.00

82  -	0.00

85	 - 0.00

88  - 	0.00

RESULT:The customer with the highest balance is 37 years old

![](balance by age.png)



ACTIVE MEMBER DISTRIBUTION BY GENDER

IsActiveMember-   	No	  -Yes

Gender		

Female	      -    2259	-  2282

Male	     -      2589	-    2867

RESULT:

1.Male customers dominate both active(55.7%) and inactive(53.4%) segments.

2.Female customers makeup a significant proportion of both active and inactive segment.


![](Active member distribution by gender.png)


CHURN RATE ANALYSIS

Exited

No    - 7960

Yes  -  2037

RESULT:

1.A significant minority of customers(20%) have exited the bank,indicating room for improvement in customer retention.

2.While 80% of customers remains active suggesting a strong customer base.


![](Churn analysis.png)	



CHURN RATE BY GENDER

Gender	   -    Exited	

Female	 - No  - 3402
     
        -  Yes - 1139

Male	   - No  - 4558
        
        
       - Yes - 898

RESULT:Female customers(1139) have exited the bank more than male customers(898)

![](churn rate by gender.png)


CHURN RATE BY GEOGRAPHY	

Geography	   -    Exited	

France	    No	 -        4203
           
            Yes -	       810

Germany     No	  -       1694
            
            Yes      - 	   814

Spain	       No	     -   2063
           
            Yes	     -    413


RESULT::Germany has the highest number of churned customers(814),followed closely by France(810).Spain has the lowest number of churned customers(413).


![](churn rate by geography.png)


CHURN RATE BY CREDIT SCORE

CreditScore   -  Exited		
850	    -          233

678  	  -        63

655	    -      54

705	   -       53

667	    -      53
...	...
441	    -      1

440	     -     1

423	    -      1

424	     -     1

358	     -     1

RESULT:This is a notable trend of high creditscore customers exiting the bank.This needs to be investigated.

![](churn rate by credit score.png)


CHURN RATE BY CREDIT CARD OWNED

HasCrCard	  -    Exited

Yes	   -     5149

No	  -      4848

RESULT:Slightly more exited customers have credit cards,and approximately 50% of exited customers have credit cards


![](churn rate by credit card owned.png)


CHURN RATE BY BALANCE DISTRIBUTION

Balance    -  	  Exited

0.00	    -        3616


130,170.82   -     2


105,473.74	 -    2


128,793.63	 -    1


132,217.45	  -   1
...	...


107,106.33	  -   1


107,104.50	 -    1


107,073.27	  -   1


107,065.31	 -    1


250,898.09	 -    1


RESULT:A substantial number of customers(3616) with 0 account balance have exited the bank,while few customers with high account balances have exited the bank.


![](churn rate by balance.png)



CHURN RATE BY AGE GRADE

Age	   -    Exited	

37	   -     478

38	   -     477

35	   -     474

36    -      456

34	   -     447
...	...

92	  -      2


82	    -    1

83	   -     1

85	   -     1

88	    -    1


RESULT:Middle aged customers(34-38 years)have higher exit rates,while older customers(82-92 years) have 

significantly lower exit rates.


![](churn rate by age.png)



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

9. Customers with (1-2 years) tenure has the highest account balances, number of products and credit scores.While it's the opposite for (0 and 10 years) customers.

10. Middle aged customers(34-38 years) have higher credit scores and estimated salaries while older adults (82-88) years have lower credit scores and estimated salaries.

11. A significant minority of customers(20%) have exited the bank,indicating room for improvement in customer retention,while 80% of customers remains active suggesting a strong customer base.

12. There is a notable trend of high credit score customers exiting the bank that needs to be investigated.

13. Middle aged customers(34-37) years have higher exit rate, while older customers(82-92) years have significantly lower exit rates.

14. A substantial amount of exited customers(3616) have 0 account balance while approximately 50% of exited customers have credit cards. 

 RECOMMENDATION

1. Germany and France has a high customer exit rate that requires urgent attention to keeep customers and grow revenue.

2. Germany and Spain have high average credit scores and can boost growth by offering premium services to high credit customers e.g higher interest rates and copying France's successful strategies and adapting.

3. Investigate reasons behind female customer's high exist rates and develop initiatives that cater to both male and female financial needs.

4. Low account balances and credit scores among (0 and 10 years) customers may explain their low credit card demand.Further investigation is recommended to confirm this analysis

5. Apex bank should offer persoalized banking services and exclusive benefits to customers aged 34-38 with high credit scores,salaries and balances to increase loyalty and retention.

6. Inactive Accounts: Many exited customers didn't utilize their accounts.Reasons behind inactive accounts should be investigated if lack of usage led to exit.

7. Credit Card Usage:Half of exited customers had credit cards indicating unmet needs or dissatifaction.Credit card usage patterns among exited customers should be analyzed.Determine if credit card issues led to exit.

8. There is a notable trend of high credit score customers exiting the bank and potential reasons could be :- better offers from competitors e.g lower interest rates,unmet expectations for premium services or recognition etc.To retain customers and increase growth, Apex bank should check what competitors offer, to prevent customers from switching to better ideas,offer special benefits to reward loyal customers, build trust and foster relationships with customers and  introduce online banking services if none.

    In conclusion, by addressing these issues Apex Bank can:Prevent churn, build customer loyalty,retain high value customers and maintain a strong customer base.  
