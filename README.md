# SBI_Customer_Segmentation
This project focuses on segmenting customers based on their credit card usage and spending behavior using clustering techniques to identify distinct customer profiles. K-means Clustering algorithm was employed and evaluated, yielding the most effective segmentation, revealing actionable insights into customer segments based on spending patterns, credit utilization, and purchase types. These segments support targeted marketing strategies, enhance customer satisfaction, and inform tailored product offerings for improved financial solutions.

# 1. Background
In a competitive banking landscape, understanding customer behavior is crucial for the State Bank of India (SBI). Clustering techniques for customer segmentation allow SBI to personalize marketing efforts and categorize customers based on spending behavior and demographics. This targeted approach enhances risk management, optimizes resource allocation, and supports product development. By leveraging insights from segmentation, SBI can improve customer retention and cross-selling opportunities, ultimately delivering a more tailored banking experience and driving growth.

# 2. Project Objectives
The primary goal is to leverage data-driven customer segmentation to guide strategic decisions in personalized marketing, credit management, and customer retention.

# 3. Technical Stacks
- **Scripting**: Python
- **Frameworks**: Pandas, Numpy, Matplotlib, Seaborn, SkLearn
- **Data Source**: CSV containing SBI credit card transactions.

# 4. Data Understanding
The Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.
- <b> CUSTID :</b> Identification of Credit Card holder (Categorical)<br>
- <b>BALANCE :</b> Balance amount left in their account to make purchases<br>
- <b>BALANCEFREQUENCY :</b> How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)<br>
- <b>PURCHASES :</b> Amount of purchases made from account<br>
- <b>ONEOFFPURCHASES :</b> Maximum purchase amount done in one-go<br>
- <b>INSTALLMENTSPURCHASES :</b> Amount of purchase done in installment<br>
- <b>CASHADVANCE :</b> Cash in advance given by the user<br>
- <b>PURCHASESFREQUENCY :</b> How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)<br>
- <b>ONEOFFPURCHASESFREQUENCY :</b> How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)<br>
- <b>PURCHASESINSTALLMENTSFREQUENCY :</b> How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)<br>
- <b>CASHADVANCEFREQUENCY :</b> How frequently the cash in advance being paid<br>
- <b>CASHADVANCETRX :</b> Number of Transactions made with "Cash in Advanced"<br>
- <b>PURCHASESTRX :</b> Numbe of purchase transactions made<br>
- <b>CREDITLIMIT :</b> Limit of Credit Card for user<br>
- <b>PAYMENTS :</b> Amount of Payment done by user<br>
- <b>MINIMUM_PAYMENTS :</b> Minimum amount of payments made by user<br>
- <b>PRCFULLPAYMENT :</b> Percent of full payment paid by user<br>
- <b>TENURE :</b> Tenure of credit card service for user<br>

# 5. Data Preprocessing
- **Remove Empty Columns and Rows**: Identify and remove any empty columns and rows.
- **Remove Duplicate**s: Deduplication of data to avoid redundancy.
- **Rename Columns**: Ensure appropriate names are used for better analysis.
- **Handle null values**: Replaced null values with statistical measure (Mean).7
- **Outlier Detection**: Detected and removed outliers from columns that distort the clustering process.
- **Feature Scaling**: Standardized values to ensure all features are on the same scale, which is important for distance-based algorithms like KMeans.
- **Feature Selection**: Selected features that are meaningful to the analysis and avoided redundant or highly correlated features that could lead to bias.
