# Customer-Classification
Classification Project on Telemarketing Effectiveness in Banking Institutions
Haryo Prabowo

Presentation can be found [here](https://github.com/hprabowo076/Customer-Classification/blob/main/Telemarketing%20Effectiveness%20for%20Banking%20Institutions.pdf)

Original Python Notebook can be found [here](https://colab.research.google.com/github/hprabowo076/Customer-Classification/blob/main/Telemarketing%20Effectiveness%20on%20Converting%20Bank's%20Client%20into%20a%20Term%20Deposit%20Subscriber.ipynb)

# Introduction

This is a dataset related to the direct marketing campaigns of a Portuguese banking institution. Source: https://www.kaggle.com/prakharrathi25/banking-dataset-marketing-targets

Telephonic marketing (telemarketing) campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

The data is related to the direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed by the customer or not.

The classification goal is to predict if the client will subscribe to a term deposit.

In this notebook, the objective is to:
- Classify which type of customers that will subscribe to the bank's term deposit because of the telemarketing. 
- Knowing what factors for a telemarketing campaign to be successful
- Building classification model to predict whether a client will subscribe to a term deposit when contacted by telephone 

Hopefully, the results from our investigation can produce useful insights in knowing the effectiveness of telemarketing on converting customers.
The details can be found on the notebook in this repo


# Overall summary
* Roughly one-tenth of the clients that’s contacted by telemarketer actually subscribes to the bank’ term deposit (~11.7% conversion rate).
* Client’s age is the most important factor to predict whether they will be persuaded by the telemarketing or not, with 30-50 years old being the most group willing to subscribe.
* Campaign frequency and the duration of the call are also important for the effectiveness of telemarketing campaign.

# Business Recommendation
*   If the investment is too big for the conversion rate, explore other direct marketing approach.
*   Target potential group that are more willing to buy the product.
*   Make clients engaged when cold calling (e.g.. small talks) so they are more willing to buy the product
