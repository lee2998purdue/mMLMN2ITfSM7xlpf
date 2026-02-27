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
[Dashboard Link](https://public.tableau.com/views/ApzivaProject2-TermDeposit/EducationHousingbalanceanalyses-dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusion
The firm has invested about 2,831 hours on campaign calls to 40,000 customers, yielding a success rate of 7.24%.

The first model has achieved an accuracy of 60.4%. By identifying 16,426 high-priority leads and eliminating 23,574 low-probability prospects, the model successfully reclaimed 1,604 hours of previously wasted campaign time. For the high-priority leads, approximately 753.5 hours were spent on the initial call, with an additional 474.1 hours dedicated to follow-up conversions.
The feature importance plot indicated that balance and age were the key features for the first model.

The second model was applied to the 16,426 high-priority leads to predict product offer acceptance. It demonstrated 84.5% accuracy in conversion prediction, successfully capturing 1,743 true positives.
The feature importance plot indicated that duration, balance, day, and age were the key features for the second model.

My approach showed a significant improvement over the 7% baseline and optimized the campaign by eliminating over 1,600 hours of unproductive call time.

The subscribers (customers who accepted the product offer) were segmented into 5 different clusters.

**Cluster 1**
*   **Key Traits:** Average age of 33.15 years, Moderate Balance (751.23), Shortest average call duration (285.27 seconds), Predominantly single, management roles, tertiary education

**Cluster 2**
*   **Key Traits:** Average age of 55.88 years, Moderate balance (777.95), Moderate call duration (562.22 seconds), Predominantly retired, married, secondary education

**Cluster 3**
*   **Key Traits:** Average age of 41.22 years, Lower balance (631.58), Long average call duration (849.82 seconds), highest campaign contact count (5.56), Predominantly married, management roles, secondary education

**Cluster 4**
*   **Key Traits:** Average age of 35.14 years, Lowest average balance (379.88), Most likely to have housing loans, Longest average call duration (888.06 seconds), Predominantly single, blue-collar workers, secondary education

**Cluster 5**
*   **Key Traits:** Average age of 39.09 years, Average balance of 0.00, Moderate call duration (682.15 seconds), Predominantly married, management roles, secondary education
