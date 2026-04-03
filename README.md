# **RETAIL PROFITABILITY & PERFORMANCE ANALYSIS USING POWER BI**

---

## **Table of Contents**

* Problem Statement
* Analysis Overview
* Data Source
* Data Processing
* Skills Demonstrated
* Insights
* Recommendation
* Conclusion

---

## **Problem Statement**

In today’s competitive retail environment, many businesses experience increasing sales without a corresponding growth in profit. While revenue continues to rise, profitability remains inconsistent due to hidden inefficiencies across products, regions, and operational costs.

Many organizations lack clear visibility into key profitability drivers such as product performance, discount impact, and cost distribution. This makes it difficult for decision-makers to understand what truly drives business success.

Without this insight, management faces challenges in:

* Identifying which products generate actual profit versus losses
* Understanding the impact of discounts on overall profitability
* Evaluating how shipping and operational costs affect margins
* Recognizing which regions contribute positively or negatively to profit

To address this challenge, **Power BI-driven analysis** is used to uncover hidden inefficiencies, evaluate profitability drivers, and generate actionable insights that improve decision-making and overall business performance.

---

## **Analysis Overview**

This project focuses on:

* Analyzing revenue, profit, and profit margin trends
* Identifying high-performing and loss-making products
* Evaluating the impact of discounts on profitability
* Assessing regional performance and cost distribution

The goal is to answer critical business questions that guide pricing strategy, cost optimization, and product portfolio decisions.

By leveraging Power BI for visualization and DAX for calculations, this project provides clear, data-driven insights to improve profitability and operational efficiency.

---

## **Data Source**

The dataset used for this analysis was sourced from a retail dataset on Kaggle and imported into Power BI.

Data preparation and initial cleaning were performed using power query before visualization.

---

##  **Data Processing**

### Data Transformation:

The following steps were carried out to prepare the dataset for analysis:

* Removing duplicate records
  *Screenshot*

* Handling missing/null values
  *Screenshot*

* Data standardization (formatting columns, correcting inconsistencies)
  *Screenshot*

* Creation of calculated measures using DAX (e.g., Profit Margin, Total Profit)
  *Screenshot*

---

##  **Skills Demonstrated**

* **Data Visualization:** Building interactive dashboards in Power BI
* **Data Transformation:** Cleaning and preparing data for analysis
* **DAX Calculations:** Creating measures such as Profit Margin and KPIs
* **Data Analysis:** Extracting meaningful insights from complex datasets
* **Critical Thinking & Problem-Solving:** Identifying inefficiencies and business risks

---

## **Insights**

---
# Page 1 Profit Overview Dashboard
*Screenshot*
![Profit Overview Dashboard](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/Profitabillity%20Overview%20Dashboard.png)
###  1. Does Revenue Growth Translate to Profit Growth?

*Screenshot*![Sales and Profit Over Time](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20and%20sales%20over%20time.png)

Sales show a consistent upward trend, but profit grows at a slower rate, with noticeable fluctuations in profit margin.

This indicates underlying inefficiencies affecting profitability.

**Business Implication:**
Revenue growth alone is not sufficient; focus must shift toward improving profit margins.

---

###  2. Which Regions Generate the Most Profit?

*Screenshot*![Profit by Region](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20by%20region.png)


The Central region generates the highest total profit, while several other regions contribute significantly less.

**Business Implication:**
Profit is concentrated in a few regions, increasing dependency risk and limiting balanced growth.

---

###  3. How Does Profit Margin Vary by Region?

*Screenshot*![Profit Margin by Region](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20margin%25%20by%20region.png)


Some regions maintain strong profit margins, while others lag behind despite generating revenue.

**Business Implication:**
Operational efficiency and pricing strategies differ across regions and need standardization.

---

### 4. Which Categories Drive Profit?

*Screenshot*![Profit by Category](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20by%20category.png)


Technology leads in total profit, followed by Office Supplies, while Furniture contributes the least.

**Business Implication:**
Category-level performance is uneven, and investment should favor high-return segments.

---
# Page 2 Profit Drivers Analysis Dashboard
*Screenshot*![Profit Drivers Dashboard](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/Profit%20Drivers.png)
### 5. How Do Discounts Affect Profitability?
*Screenshot*![Discount by Profit Relationship](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/discount%20vs%20profit%20relationship.png)


Higher discounts are associated with lower profit. Many products with heavy discounts fail to generate meaningful profit.
The scatter plot shows that most high-discount products fall below average profit levels, with only a few exceptions.

**Business Implication:**
Aggressive discounting generally leads to reduced profitability and should be controlled.

---

### 6. What Impact Do Shipping Costs Have on Profit?
*screenshot*![Shipping cost by profit](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/shipping%20cost%20by%20region.png)

Shipping costs are significantly high in certain regions, directly reducing overall profitability.

**Business Implication:**
Logistics and delivery costs are key drivers of margin reduction.

---

###  7. Which Products Generate the Most Profit?
*Screenshot*![profit by product](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20by%20product.png)

A small group of products contributes a large portion of total profit.

**Business Implication:**
The business relies heavily on a few high-performing products.

---

###  8. Which Products Have the Highest Profit Margins?
*Screenshot*![Profit Margin% by Product](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/profit%20margin%20by%20product.png)


Some products achieve high profit margins despite not having the highest sales volume.

**Business Implication:**
High-margin products present an opportunity for strategic scaling and promotion.

---


# Page 3 Actionable Insights and Opportunities 
*Screenshot*![Actional Insights Dashboard](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/Actionable%20Insights.png)

----

###  10. How Many Products Are Loss-Making?
*Screenshot*![Loss Making Products](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/Loss%20Making%20Products.png)


Over 300 products are identified as loss-making.

**Business Implication:**
A large portion of the product portfolio is destroying value and requires immediate attention. 

---

###  11. What Do Top vs Bottom Products Reveal?

*Screenshot*![10 bottom Products](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/10%20bottom%20products%20by%20profit.png)
*Screenshot*![10 top Products](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/10%20top%20products%20by%20Profit.png)


Top-performing products generate significantly higher profit compared to bottom-performing products, which consistently contribute minimal or negative profit.


**Business Implication:**
There is a wide performance gap, indicating the need to eliminate or improve underperforming products.

---

### 12. How Is Profit Distributed Across Sub-Categories?
*Screenshot*![Sub-category by Profit](https://github.com/OgaPrecious/Retail-Profitability-and-Performance-Analysis/blob/main/subcategory%20by%20profit.png)


Profit is unevenly distributed across sub-categories, with a few dominating while others contribute minimally.

**Business Implication:**
Sub-category optimization is essential to improve overall profitability.

---

#  **Recommendations**

* Optimize discount strategies by reducing excessive discounting on low-margin products
* Improve logistics efficiency by reviewing shipping costs in high-expense regions
* Identify and eliminate or reprice consistently loss-making products
* Invest more in high-performing categories like Technology
* Adjust regional strategies by reviewing pricing, logistics, and product mix
* Continuously monitor profit margin alongside revenue for better decision-making


---

## **Conclusion**

This project demonstrates how Power BI analytics can uncover critical insights into retail profitability beyond surface-level revenue metrics.

By analyzing profit drivers such as discounts, shipping costs, and product performance, businesses can:

* Make data-driven decisions
* Improve operational efficiency
* Optimize product and pricing strategies
* Increase overall profitability

---


## Contact
👤 Precious Oga
* 📧 Email: ogapreciousukamaka@gmail.com
* Linkedin: https://www.linkedin.com/in/precious-oga-18b808367
* Tiktok: https://www.tiktok.com/@ogapreciousdataanalyst
