The goal of this project will be to carry out an exploratory data analysis in search of insights that can help with business strategies for Olist, a marketplace manager. Therefore, please note that our analysis will not focus on the marketplaces themselves, but in strategies for the growth of Olist, the manager of these marketplaces.

Because of that and also due to the database structure (we have 96477 orders and 93357 customers ID) i.e. practically one order per user, it won't be interesting to do user-level analyses, using concepts such as RFM (recency, frequency and monetary value) Therefore our analysis will be centered on the profile of sales in diferent states, categories, and through time.

The main questions to be answered throughout this project (summarized) are:

  * What are the states with the best cost-benefit of investments?

  * What are the best categories to search for new customers (promote new marketplaces)?

  * How are sales trends across states and categories, and how can we use this as strategies?


We will work with an ecommerce public dataset. The dataset has information of ~100k orders from 2016 to 2018 made at multiple marketplaces in Brazil by customers of Olist.


The project will be divided into three parts:

1) Loading Data and Initial Treatment
we are working with a database that consists of 9 tables. So, first of all we are going to look at what information has the most potential for our analysis in each table, and put it together in a single dataframe.Still in this step, we will perform a quick treatment to keep only requests with relevant status and treat missing values

2) Exploratory Analysis
In this section we will explore our data in order to answer the following questions:

* Which categories have the greatest potential to generate revenue?

* The most indicated categories for marketing actions

* Should the strategies be thought of at the national or state level?

* How the number of sellers and the freight price influence a state's sales?

* What are the main differences between sales in different states and how can we use this as a strategy?

* Is the distribution of vouchers a good strategy considering the scenario presented?



3) Temporal Analysis

In this section we will explore our data with a temporal bias, in order to answer the following questions:

* How are the sales growth/falling trends (nationally and statewide)?

* How are the sales growth/falling trends in each category?

* What kind of strategies can we establish from this trend analysis?


