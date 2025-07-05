# E-COMMERCE-DATA-ANALYSIS (Interactive Dashboard using Python)

## PROJECT OBJECTIVE
● Objective: Predict the number of furniture items sold (sold) based on product
attributes such as productTitle, originalPrice, price, and tagText.
## DATA-SET-USED
 - <a href="https://drive.google.com/file/d/1EwYcFTnjwuZTpdfd2uaKjNVDLPmRsSMD/view?usp=sharing">Data-Set</a>

## QUESTIONS(KPIs)

- How many products are currently listed?
- What is the total number of units sold across all products?
- What is the average selling price of products?
- What is the total revenue? (price × units sold)
- Which product has the highest number of units sold?
- Which product has generated the highest revenue?
- What percentage of products are currently discounted (i.e., originalPrice > price)?
- Do discounted products sell more on average than non-discounted ones?
- Which marketing tag (e.g., “Free Shipping”) appears the most?
-  How many products have not been sold even once?
- Dashboard Intrection - https://github.com/Rashid-tech-cpu/Data--Analysis-Dashboard/blob/main/E%20commmerce%20dashboard%20(1).ipynb

## PROCESS
 - Import pandas, matplotlib, seaborn.[Uploading E commmerce dashboard.ipynb…]()

 - Load the CSV file using pd.read_csv().
 - Remove $ and convert price and originalPrice to float.
 - Fill missing tagText with "No Tag" and handle missing prices.
 - plot charts by using matplotlib and seaborn.

   ## DASHBOARD
- ![download](https://github.com/user-attachments/assets/c712e27f-6237-4896-81b9-c976b6b0c4be)

## KEY INSIGHTS

📊 OVERALL PERFORMANCE:
   • Total Products: 200
   • Products with Sales: 147 (73.5%)
   • Total Revenue: $1,603,565.25
   • Average Revenue per Product: $8017.83

💰 PRICING INSIGHTS:
   • Average Price: $209.41
   • Median Price: $205.55

🏆 TOP PERFORMING CATEGORY:
   • Seating: $657,029.17 revenue

🚚 SHIPPING INSIGHTS:
   • Free shipping: 78.0% of products, 5,943 total sales
   • Low shipping: 13.5% of products, 980 total sales
   • Other shipping: 8.5% of products, 502 total sales

💵 PRICE RANGE INSIGHTS:
   • Best performing range: $201-300
   • Total sales in this range: 2,109

 ## RECOMMENDATIONS
 
   - Focus inventory on Seating category
   - Optimize pricing in $$201-300 range
   - Consider promoting products with low/no sales

