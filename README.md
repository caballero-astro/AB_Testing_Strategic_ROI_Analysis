# A/B Testing: Strategic Growth Optimization and Market Prioritization

## Business Context:
**The Company & Stage**: A mid-stage E-commerce Scale-Up operates a cross-border digital marketplace across seven global markets. Having successfully moved past the initial "Customer Acquisition" phase, the company is now focused on Unit Economics and Profitability.

**The Challenge**: The company currently manages a fixed quarterly investment budget but lacks a data-driven methodology to allocate these funds across diverse international markets. Management observed inconsistent results from recent campaigns and realized that "growth at any cost" is no longer a viable strategy for long-term sustainability.

**The Intervention (A/B Test)**: To find a lever for growth, the company deployed and A/B test, with a Dynamic Checkout & Pricing Optimization (B-Version B) experiment across all regions. This test was designed to observe changes in user spending behavior and transaction value. The test was performed in the 7 countries with company operations. All users are registered. From registration we have user information on their location and age (mandatory registration fields). User sex is an optional registration field, and therefore remains unspecified for some users. In this A/B test, conversion is the purchase of items by the user. The test also keeps track of purchase amounts, allowing us to evaluate the success of B-Version in terms of revenue.

**Analysis Mandate**
The company has commissioned an analysis of the experimental data with the mandate to **deliver an investment strategy that maximizes revenue and growth potential across all markets**, providing a clear roadmap for where the next fiscal cycle's budget will yield the highest impact. The company has a number of promotional actions it can use to increase user base (bring in more registrations) or encourage more spending from already registered users.

## Analysis Approach
Based on the mandate and data, the analysis focuses on:

1. Examine the overall success of website's B-Version to proposes whether it's ready for immediate rollout or not, and in which markets.
2. If B-Version is ready for rollout, conduct a ROI analysis on appropriate user segments to propose targeted investment strategies.

##  Key Features:
* **Unified A/B Pipeline:** A modular Python class/function to handle complex grouping, Z-testing, and revenue uplift calculations in one pass.
* **SIP (Strategic Investment Priority) Score:** A custom metric weighting revenue growth against Cost Per Incremental Conversion (CPIC).
* **4D Segment Opportunity Map:** A high-impact visualization plotting Growth (Uplift %) vs. Scale (Baseline Revenue) vs. Reach (Total Users).

##  Methodology:
1.  **IDA/EDA:** Validating data integrity and identifying global trends.
2.  **Statistical Inference:** Two-proportion Z-tests for conversion significance.
3.  **Strategic Ranking:** Using the SIP Framework to prioritize marketing spend across 7 global markets.

##  Key Insights:
* **Global success:** The B-Version was widely successful globally, with significant conversion lift across all countries and major user categories.
* **High-resolution segment analysis required:** Results among a category like device type used can change significantly if combined with another, like user age. The full user profile was required to reach safer conclusions.
* **Conversion != Revenue:** Found that the B-Version's conversion lift is not fully correlated with revenue uplift, leading to revenue uplift analysis to confirm B-Version finanical success .
* **High-Yield markets:** Identified Pakistan and India as a "High-Efficiency" market where low CPIC and high revenue uplift created the highest SIP Score.
* **Segment investment opportunities:** Demonstrate how to identified user segments in a country for prioritizing different types of investments in promotional actions.

##  Tech Stack:
* **Python:** Pandas, NumPy, Statsmodels
* **Visualization:** Seaborn, Matplotlib (Custom Multi-axis Dashboards)
* **Environment:** Jupyter Notebook

## Contents:
* AB_Test_Data.csv (Data)
* AB_Testing_WebpageVersion_Conversion-EDA-Final (IDA/EDA notebook)
* AB_Testing_WebpageVersion_Conversion-Analysis (Strategic Investment Data Analysis)
* README.md (This file)
* LICENSE (MIT Licence for this repo)
* gitignore file

## Data origin:
* The dataset is a modified version of data from Kaggle.com
* Original data: https://www.kaggle.com/datasets/aadbutt/ab-testing
