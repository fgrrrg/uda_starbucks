# Starbucks rewards app data analytics
Data science capstone project

## Installation
The project should run using Jupyter Notebook, rather light on libraries used, but pandas, numpy, sklearn, matplotlib, and json are necessary.

## Description
The files contain a synthetic dataset of the Starbucks Rewards program, containing information about the different offers they offer, the customer demographics and the transactions made.
The customers receive different kind of offers such as "Buy one get one free", discount, and informational which doesn't have any monetary value.
The transcript table contains the information about the customer receiving, viewing, completing an offer and in general all the transactions they made.

I will analyse the cusomer base, the rewards, and the driving factors behind an offer being successful or not.
I will try to find which offers work best, and which demografic groups are the most responsive to offers. I consider the success of an offer is that 
the customer will make a transaction after receiving AND viewing an offer, therefore we can imply that the offer had an impact on the purchasing decision.
From business perspective, getting a better understading of the response rates of different offers will help to tailor the different discounts to the customer base, which leads to higher revenues.
Getting more information about the customers who take up on offers will help to streamline the channels the offers are advertised, allowing cost-cutting and better response rates. 

## Challenges
The data requires a lot  of data wrangling to make it suitable for classification models. The transcript table doesn't immediately indicate whether an offer was successful or not.

The Jupyter Notebook contains all the code for the analysis.

## Conclusion
The most important factors accordding to the models are the membership length, the channel Starbucks promote the offer and the income category of the customers.
Going forward, it could be beneficial to analyse the transcript table more, and derive additional features or create differernt groups from the data.
Using different classification techniques and spent additional time fine-tuning variables using grid search or similar methods.

Read the blog post here: https://medium.com/@fgergo/unveiling-the-dynamics-of-starbucks-rewards-app-usage-0c6ae7c03626

The source of the data is Udacity and Starbucks. For the data wrangling I used methods described in: https://towardsdatascience.com/using-starbucks-app-user-data-to-predict-effective-offers-20b799f3a6d5
