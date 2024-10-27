# SBI_Customer_Segmentation
This project focuses on segmenting customers based on their credit card usage and spending behavior using clustering techniques to identify distinct customer profiles. K-means Clustering algorithm was employed and evaluated, yielding the most effective segmentation, revealing actionable insights into customer segments based on spending patterns, credit utilization, and purchase types. These segments support targeted marketing strategies, enhance customer satisfaction, and inform tailored product offerings for improved financial solutions.

## Background
In a competitive banking landscape, understanding customer behavior is crucial for the State Bank of India (SBI). Clustering techniques for customer segmentation allow SBI to personalize marketing efforts and categorize customers based on spending behavior and demographics. This targeted approach enhances risk management, optimizes resource allocation, and supports product development. By leveraging insights from segmentation, SBI can improve customer retention and cross-selling opportunities, ultimately delivering a more tailored banking experience and driving growth.

## Project Objectives
The primary goal is to leverage data-driven customer segmentation to guide strategic decisions in personalized marketing, credit management, and customer retention.

## Technical Stacks
- **Scripting**: Python
- **Frameworks**: Pandas, Numpy, Matplotlib, Seaborn, SkLearn
- **Data Source**: CSV containing SBI credit card transactions.

## Data Understanding
The Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.
- <b>CustID :</b> Identification of Credit Card holder (Categorical)<br>
- <b>Balance :</b> Balance amount left in their account to make purchases<br>
- <b>BalanceFrequency :</b> How frequently the Balance is updated, score between 0 and 1.<br>
- <b>Purchases :</b> Amount of purchases made from account<br>
- <b>OneOffPurchases :</b> Maximum purchase amount done in one-go<br>
- <b>InstallmentPurchases :</b> Amount of purchase done in installment<br>
- <b>CashAdvance :</b> Cash in advance given by the user<br>
- <b>PurchaseFrequency :</b> How frequently the Purchases are being made, score between 0 and 1.<br>
- <b>OneOffPurchaseFrequency :</b> How frequently Purchases are happening in one-go.<br>
- <b>PuchasesInstallmentFrequency :</b> How frequently purchases in installments are being done.<br>
- <b>CashAdvanceFrequency :</b> How frequently the cash in advance being paid<br>
- <b>CashAdvanceTRX :</b> Number of Transactions made with "Cash in Advanced"<br>
- <b>PurchasesTRX :</b> Numbe of purchase transactions made<br>
- <b>CreditLimit :</b> Limit of Credit Card for user<br>
- <b>Payments :</b> Amount of Payment done by user<br>
- <b>MinimumPayments :</b> Minimum amount of payments made by user<br>
- <b>PRCFullPayments :</b> Percent of full payment paid by user<br>
- <b>Tenure :</b> Tenure of credit card service for user<br>

## Data Preprocessing
- **Remove Empty Columns and Rows**: Identify and remove any empty columns and rows.
- **Remove Duplicate**s: Deduplication of data to avoid redundancy.
- **Rename Columns**: Ensure appropriate names are used for better analysis.
- **Handle null values**: Replaced null values with statistical measure (Mean).
- **Outlier Detection**: Detected and removed outliers from columns that distort the clustering process.
- **Feature Scaling**: Standardized values to ensure all features are on the same scale.
- **Feature Selection**: Selected features that are meaningful to the analysis and avoided highly correlated features that could lead to bias.

## Dimensionality Reduction
Applying Principal Component Analysis (PCA) can reduce the dataset’s dimensions while retaining the main information, making the clustering process more efficient.

![image](https://github.com/user-attachments/assets/8032af52-af19-48ff-b067-f5b55b2f4e71)

![image](https://github.com/user-attachments/assets/43f0343c-6a4c-487e-a69a-bc07ce5389ed)




