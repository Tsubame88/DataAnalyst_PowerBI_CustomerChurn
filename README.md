## Introduction 

This project analyzes customer churn for Databel, a fictitious telecom company, using a dataset provided by DataCamp. 

Utilizing Power BI, I examined key factors influencing customer churn to identify actionable insights for improving customer retention. 
This analysis aims to uncover trends and patterns in customer behavior, helping Databel to develop effective strategies to reduce churn rates and enhance overall customer satisfaction.

## Objective 
1. Analyze the reasons why the customers are churning
2. Provide recommendations to Databel 
____
### What is churn ?

### How to calculate churn rate 

              Churn Rate = [Nb of Churn Customers] /[Nb of Customers]

### Investigate why customers churn 
    1. Visualize the % churner by reason in which the 2 factors that have the most impact on churn rate come from competitor 
    2. Visualize the churns by churn categories :  Almost half (44.82%)of customers churning are related to the churn category "Competitor"
    3. Create a map to investigate the churn rate by state :  CA is the state that has the highest churn rate of 63.24% 

### Over view 

1. Present the important KPI : the churn rate over 51 states is quite high of 26.86 %
1. 
2. ~45% reasons why customers churn is related to the categories "competitor" . This could rase a question that "is Databell competitive enough ?"
3. The churn rate in Caliofornia is abnormaly high at 63.24%
BUt we dont have yet a clear explannation for this high churn rate

### Analysing Demograhic 
1. Churn rate for Seniors citizens is  38.46% higher than the average churn rate around 10%. This might be good idea to analyse the customer age in general
2. The age bracket of 45 (45~49 ) has the highest number of customers and in general the churn rate inscreas as the age increases 
       
### Inspecting group 
The Databell offers group contract to customers from the same household. The advantage of the customer is discounted rate while its a great way for Databel to grow its customer base.
Analyse if the customers who are part of group have a lower phone bill and if it impacted on the churn rate.
The groups from 2 persons have significantly lower average monthly charge than the person not in group contract.

### Inspecting the contract type 
There are many kind of contract "One Year" "Two Year" "Month-to-Month". WE can gather "One Year" contract and "Two Year" contract into one. By this way we can observe the different between yearly contract and monthly contract .
+ The persons who are in monthly contract have hight churn rate of 46.29%
+ The person who are in yearly contract have low churn rate of 6.62%

**Recommand to Databel**: to stop customer from churning we can propose them to use yearly contract.

### Exploring the payment method 
There are 3 types of payments and "Paper check" has the smallest of customers only 371 persons 5.55% of total 

### Inspecting the Unlimited Data Plan 

    **Unlimited Data Plan** : Indicate if the customer has free unlimited download capacity with "Yes" or "NO". This premium is reflected in the amount of monthly charge.

It appears that customers who are on unlimited plan are more likely to churn 32.11% compare to 16.10% of those who are not .

Let's see if it is related to a certain amount of mobile data(GB) being used 

CHurn rate for people on an unlimited plan who consume less than 5 GB of data is 34.71%.
Its quite high. 
**Recommand to Databal** : Contact customers who are on Unlimited Plan but use less than 5G and propose them to downgrade their plan. This will increase customers satisfaction and stop customer from churning.

### Inspecting International call 
Databel curious about the behavior of customers who call internationally and if paying for an international plan influences their loyalty 

**Intl Plan**: indicates if the customer has a premium plan to call internationally for free with "yes" or "no". This premium is reflected in the amount of monthly charge. 

Focus on the state that has the highest churn rate California, We can see that the churn rate of persons who actived international call but dont have Intl Plan is 72 %. These person can be potential clients for the new promotion of the Intl Plan. 

Also, I discoverd that in general, the churn rate for customers who have Intl Plan but dont but don't active the call is sky-high of 71.19 %.

**Recommand to Databel**: Contact customers who are on Intl Plan but dont have international call and propose they to downgrade their plan. This will increase customer satisfaction and stop customer from churning.
For California, navigate the promotion of Intl Plan to the customers churned and already active International call.

### III- Creating a cohesive story 

1. Overview Page.
2. Age Ggoup Page  
From the age of 60 the churn rate increase. other graph tell us that moving cuqtomer in yearly contract could greatly reduce the churn rate.
3. Payment and contract
The churn rate of these customers is 53.90% ,quite high. It is clear that the ones who call customer service often is the ones who churn more than average.

The average number of Customer Service calls of those who have Monthly contract and pay by Direct Debit is 1.47. This is high. 
Databel should definitely investigate what's going on here. Maybe there was a problem with the payment method that need to be looked into. 

4. Extra charges
The persons who don't use Unlimited Plan and use more than 10 GB have to pay average extra charges of 31.19 $

6. Insight
7. 
The line chart discribes the Avg number of customer service calls by churn label Yes/No by State.  
We can see that those make service calls have the higher churn rate compare to those don't make in each state.

However, 
We observe that CA is the state that has the highest churn rate but also has lowest number of customer service calls 


