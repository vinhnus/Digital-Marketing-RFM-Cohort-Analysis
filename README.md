# Digital-Marketing-RFM-Cohort-Analysis

## Situation 
Company A sells fashion. They have stores in each country’s capital: UK (London); FR (Paris); IT (Milan); GER (Berlin). Their customers either buy online or in the store itself. 
At the same time, it maintains a website of individual product pages with write ups and images about the page. In some cases, the page might have gone up after the product was put up for sale. 
Management would like you – the data analyst – to use of this data and answer these questions: 
1. What is the impact of our website traffic on revenue? 
2. Which products get us pageviews and revenue?
3. What customer segments are there?

**Data Source**
| Source | Description |
| ----------- | ----------- |
| Customers & Transactions| Customer info and their transactions. These transactions are a mix of in-store and online transactions. |
| Traffic | Website traffic data for individual product pages (Duration: Jan to Dec 2020) |

## Objectives 
Evaluate the impact of online traffic on revenue using conversion rate

Identify which products drive the most traffic and the most profited.

Perform RFM analysis, Cohort analysis.

## Summary
1. What is the impact of our website traffic on revenue?

   Conversion rate gives us an overview of how much percentage of online users actually became our customers. From that give us a better view of the impact of online traffic affect our revenue

   Company A has Conversion rate highest of 0.35 in September and lowest of 0.01 February by day

   Conversion Rates by Month are unstable, they hit rock bottom in March and December around 0.05, but peaked in November 0.88

   **Conclusion:** From what the conversion rate implies our online traffic seemed to have little impact on our online revenue
2. Which products get us pageviews and revenue?
   This is the top 5 product which give us most pageviews and revenue

   |  Product | Revenue  | Pageviews  |
   |---|---|---|
   | g-dX-look0.897569041695992  |  7891430 | 17586966.0  |
   | nikzswear0.156690506174201  |  7626120 | 17586966.0  |
   |  nikf-info0.0504871333447614 | 7033800  | 17586966.0  |
   | niky-info0.291457801989401  | 6856104  | 14069572.8  |
   | nikw-gold0.879607833563163  |  6708024 | 14069572.8  |

3. What customer segments are there

   There are various ways to perform customer segmentation. But with this kind of data, I think the most suitable approach is using RFM segmentation.

   **RFM model** is a proven marketing strategy based on customer behavior segmentation. It groups customers based on their purchase history – how recently, with what Frequency, and what value they bought.

   RFM Metrics

   * Recency : It is the amount of time since the customers most recent transaction. It is measured in days.
   
   *  Frequency: Total number of transactions made by the customer.
   
   * Monetary : Total amount the customer has spent across all transactions.
  
   Despite the fact that company A has many stores located in various countries, I only perform customer segment on stores in Germany for demostrating purpose

   **There are 11 segments based on RFM analysis using KMeans**

3.3 Cohort Analysis

  The result is interesting. Customers who have purchased in January have very high retention rate then drop significantly the next few month until August then there is no new customers.
  
  Further investigate should be executed to gain more knowledge on why this happened. My guess is that because of COVID19 where store were forced to be shut down, limit approach to new customers.





