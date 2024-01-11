## Customer Segmentation for SBI Life Insurance
# Overview

This project focuses on customer segmentation using clustering models to provide targeted product and service recommendations for SBI Life Insurance. The objective is to analyze the usage behavior of approximately 9000 active credit card holders over the last 6 months. The segmentation will assist in tailoring financial offerings such as saving plans, loans, wealth management, etc., based on distinct customer groups.

# Objective

Develop a customer segmentation model that identifies target customer groups for SBI Life Insurance. Utilize clustering algorithms to categorize customers based on their credit card usage behavior, and provide personalized recommendations for financial products and services.

# Data Description

The dataset comprises customer-level information with 18 behavioral variables. The following attributes are included in the dataset:

* CUSTID: Identification of Credit Card holder (Categorical)
* BALANCE: Balance amount left in their account to make purchases
* BALANCEFREQUENCY: Frequency of balance updates (score between 0 and 1)
* PURCHASES: Amount of purchases made from the account
* ONEOFFPURCHASES: Maximum purchase amount done in one-go
* INSTALLMENTSPURCHASES: Amount of purchase done in installments
* CASHADVANCE: Cash in advance given by the user
* PURCHASESFREQUENCY: Frequency of purchases (score between 0 and 1)
* ONEOFFPURCHASESFREQUENCY: Frequency of one-go purchases (score between 0 and 1)
* PURCHASESINSTALLMENTSFREQUENCY: Frequency of purchases in installments (score between 0 and 1)
* CASHADVANCEFREQUENCY: Frequency of cash in advance being paid
* CASHADVANCETRX: Number of transactions made with "Cash in Advanced"
* PURCHASESTRX: Number of purchase transactions made
* CREDITLIMIT: Limit of Credit Card for the user
* PAYMENTS: Amount of payment done by the user
* MINIMUM_PAYMENTS: Minimum amount of payments made by the user
* PRCFULLPAYMENT: Percent of full payment paid by the user
* TENURE: Tenure of credit card service for the user
