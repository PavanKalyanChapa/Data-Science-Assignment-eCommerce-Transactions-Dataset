# Data-Science-Assignment-eCommerce-Transactions-Dataset

# eCommerce Transactions Analysis

## Overview

This repository contains a comprehensive analysis of an eCommerce transactions dataset consisting of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The project involves performing exploratory data analysis (EDA), building a lookalike model, and conducting customer segmentation using clustering techniques. The goal is to derive actionable insights that can help improve business strategies.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Tasks](#tasks)
  - [Task 1: Exploratory Data Analysis (EDA)](#task-1-exploratory-data-analysis-eda)
  - [Task 2: Lookalike Model](#task-2-lookalike-model)
  - [Task 3: Customer Segmentation / Clustering](#task-3-customer-segmentation--clustering)
- [Business Insights](#business-insights)


## Installation

To run the code in this repository, you will need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
## Usage

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/ecommerce-transactions-analysis.git
   ```
2. Navigate to the project directory:
  ```bash
  Open In Editor
  Run
  Copy code
  cd ecommerce-transactions-analysis
  Open the Jupyter Notebook files to run the code:

  FirstName_LastName_EDA.ipynb for exploratory data analysis.
  FirstName_LastName_Lookalike.ipynb for the lookalike model.
  FirstName_LastName_Clustering.ipynb for customer segmentation.
  The output files will be generated in the same directory.
  ```

## Tasks
# Task 1: Exploratory Data Analysis (EDA)
Performed EDA on the provided dataset.
Derived actionable business insights from the analysis.
The EDA results are documented in FirstName_LastName_EDA.pdf.
# Task 2: Lookalike Model
Built a lookalike model that recommends similar customers based on their profile and transaction history.
The top 3 lookalikes for the first 20 customers are saved in FirstName_LastName_Lookalike.csv.
The model development is explained in FirstName_LastName_Lookalike.ipynb.
# Task 3: Customer Segmentation / Clustering
Performed customer segmentation using clustering techniques.
Calculated clustering metrics, including the Davies-Bouldin Index (DB Index).
The clustering results and metrics are documented in FirstName_LastName_Clustering.pdf.
The clustering code is available in FirstName_LastName_Clustering.ipynb.

## Business Insights
# 1. Top-Performing Products: 
P029, P079, and P048 lead in total sales generating $19,513.80, $17,946.91, and $17,905.20, respectively. These products significantly contribute to overall revenue and show strong preference from customers. Analyzing their categories and pricing strategies will let you understand what makes them perform well. Some possible activities that could further boost the sales of these products include marketing and advertising, while ensuring the most optimal stock availability, bundling them with different product items, and tracking trends brought about by the product in order to refine product mix to meet their demand. Considering to work hand-in-hand with suppliers to strike a favorable price on these products or provide the exclusive foodstuff deals can raise further competitive edge in the market.
# 2. Customer Distribution:
South America constituted the largest end market, claiming 59 customers; it was followed by Europe (50), and North America came in at 46, pointing to the imbalance at the regional level. The advocacy could be for South America, should there be concentration on specific marketing stratagems. Exploitation of localized means of interacting with the masses-key being inspiring the purchase with better deals-could certainly improve customer rapport. Also, feedback on preferences-from a South American customer's perspective-would serve to tune the product/service offerings needed. Regions with fewer customers, like North America and Asia, can launch marketing strategies geared towards product or service visibility. Instead of concentrating on what could reach the news, attention should then on understanding the regional needs, tackling any hesitations between browsing and buying, and simultaneously nurture the brand.
# 3. Seasonal Revenue Trends:
Income seems to reach its peak in July 2024, $71,366.39, while the month of December 2023 is the leanest, at a mere $3,769.52. This could imply that sales mid-year are far stronger, perhaps because of seasonal demand or sales events. In utilization of this trend, companies can promote marketing campaigns and have their inventory ready long before the peak business season to generate earnings. Moreover, it would be a good idea to take an in-depth study into the reasons for a December slump so that there can be ways to counter such a situation while giving better options for the future. The epitome of this BB would be the bundling of year-end discounting, festive promotions or loyalty programs to perk up sales
during anticipated slow months. Analyzing the behavior of the specific customer segment during such periods would serve to nurture optimized year-round revenue strategies.
# 4. Top Customers:
The highest-contributing sales figure for a customer is purported by C0141, with a total of $10,673.87, followed afterwards by C0054, which boasts $8,040.39. Here, such high value customers hold the key to a business's success. Building a loyalty program with exclusive benefits - such as conditional discounts or early access to new products - ensures continued dedication on part of these customers. By closely tracking their purchase habits, other areas emerge to address-whether it is cross-selling or upselling, respectively. Communication through personalized offers, along with special events, helps build strong relationships with the valuable customers. Through this approach, the company emphasizes the high-spend customers to maximize Customer Lifetime Value and ROI on marketing investments.
# 5. Underperforming Products:
Performances of Products P044 and P056 has been languishing, where sales have culminated at $244.66 for the former and $337.68 for the latter. Somewhat low sales statistics make a case for an impending deficit of either demand, pricing, or market positioning. Proper exploration into customer feedback and market trends reveals the root causes. Opportunities are open for downsizing the price, associating more well-performing products, and possibly dropping this line. Moreover, Inventory Hold Cost Analysis makes a better yardstick upon which a final decision can be taken regarding these products. Otherwise, marketing solutions like awareness creation or case demonstrations for trial promotions might work best for sagging sales.


