# Funnel Conversion Analysis

## Overview
This project analyzes user behavior across different stages of the funnel — from viewing a product to making a purchase.  
The objective is to understand conversion rates at each stage, identify where the largest drop-offs occur, and provide actionable insights for optimization.  

The funnel stages in this project are:  
**View → Click → Add to Cart → Purchase**

---

## Key Steps
1. **Stage Definition**  
   Clearly define funnel stages based on user interactions.

2. **Data Aggregation**  
   Collect and summarize user activities at each stage.

3. **Conversion Ratio Calculation**  
   Calculate the percentage of users who move from one stage to the next.

4. **Drop-off Identification**  
   Identify significant user losses between stages to detect bottlenecks.

5. **Visualization**  
   Build funnel charts and bar plots to visualize conversion and drop-off.

---

## Insights
- From a total of **76,594,780 views (100%)**,  
  - **79% (60,133,580)** converted into clicks.  
  - Conversion dropped sharply at the **Add to Cart stage** with only **15% (11,149,410)**.  
  - Finally, only **1% (1,115,934)** of total views resulted in purchases.  

This indicates a **critical drop-off between the Click and Add to Cart stages**, which is the key area for optimization.

---

## Conclusion
The funnel conversion shows that while user engagement from view to click is strong, the transition from **click to add_to_cart** is significantly weak. This bottleneck suggests possible friction in the user journey that prevents customers from adding products to their cart.

---

## Recommendations
- **Improve Add-to-Cart Experience**  
  Simplify the process, reduce unnecessary steps, and enhance site performance.  

- **Optimize Product & Pricing Strategy**  
  Ensure products shown after clicks meet user expectations and remain competitive.  

- **Introduce Targeted Promotions**  
  Offer discounts, vouchers, or free shipping to motivate users to add items to their cart.  

- **Leverage Personalized Retargeting**  
  Reach out to users who clicked but did not proceed, using tailored ads or email campaigns.  

---

## Visualization Example
Below is a sample visualization of the funnel conversion:

![Funnel Conversion Chart](funnel_chart.png)

---

## Tech Stack
- **Python** (pandas, numpy)  
- **Matplotlib & Seaborn** (for visualization)  
- **Jupyter Notebook** (for analysis and reporting)

---
