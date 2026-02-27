# Apziva Project 2: Term Deposit Marketing

The purpose of this project is to improve the efficiency of marketing campaigns for the term deposit product.

I implemented a two-stage Machine Learning solution to identify and target customers with the highest propensity to accept product offers. The first model identifies high-priority customers for the campaign by analyzing demographic and financial data. The second model predicts whether the identified group would accept the product offer.


## Files
### Exploratory Data Analysis
* **File:** `EDA.ipynb`

### Model 1
* **File:** `Modeling_1.ipynb`
* Predict the customers to make calls to, using features that are not related to the campaign

### Model 2
* **File:** `Modeling_2.ipynb`
* Predict whether the customer who received the campaign calls would decide to subscribe to the term deposit product

### Customer Segmentation
* **File:** `Customer_Segmentation.ipynb`
* Create clusters of customers who decided to accept the offer and subscribe to the product

### Tableau Dashboards

## Conclusion
The firm has invested about 2,831 hours on campaign calls to 40,000 customers, yielding a success rate of 7.24%.

The first model has achieved an accuracy of 60.4%. By identifying 16,426 high-priority leads and eliminating 23,574 low-probability prospects, the model successfully reclaimed 1,604 hours of previously wasted campaign time. For the high-priority leads, approximately 753.5 hours were spent on the initial call, with an additional 474.1 hours dedicated to follow-up conversions.

The second model was applied to the 16,426 high-priority leads to predict product offer acceptance. It demonstrated 84.5% accuracy in conversion prediction, successfully capturing 1,743 true positives.

My approach showed a significant improvement over the 7% baseline and optimized the campaign by eliminating over 1,600 hours of unproductive call time.
