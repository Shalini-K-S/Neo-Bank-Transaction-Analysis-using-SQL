# Neo-Bank-Transaction-Analysis-using-SQL
## Table of Contents
- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Problem Analyzed](problem-analyzed)
- [Results/Findings](results/findings)

## Project Overview
Neo-Banks are a recent development in the financial sector; they are new banks that solely operate online.This case study focuses on metrics calculations, business growth, and data analysis to assist the company more accurately estimate and plan for the future.

## Data Sources
 The datasets used for this data analysis is "customer_nodes.csv" fact table,"customer_transactions.csv","regions.csv" , containing details about the transactions and region which are the dimensional table which are connected to nodes table through customer_id and region_id .

## Tools
Microsoft SQL
## Procedure
- The schema used are region,transaction and nodes
- Check the data for null and missing values
- Data Exploration Analysis
## Problem Analyzed 
-How many different nodes make up the Data Bank network?
- How many nodes are there in each region?
- How many customers are divided among the regions?
- Determine the total amount of transactions for each region name.
- How long does it take on an average to move clients to a new node?
-  What is the unique count and total amount for each transaction type?
-  What is the average number and size of past deposits across all customers?
-   For each month - how many Data Bank customers make more than 1 deposit and at least either 1 purchase or 1 withdrawal in a single month?
## Results/Findings
The analysis results are summarized as follows:

- The data bank network consists of 5 unique nodes.
- The Number of nodes is highest in Australia.
- There are about 22% of customers from Australia.
- The count and total transaction is highest for deposit type.
- On average each customers deposit 5 times and the deposit amount is 508.
- Around 115 customers does any kind transactions during the first month.
