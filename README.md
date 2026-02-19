# Pizza_Data_Visualisation
The analysis of pizza orders and revenue of a pizza vendor with recommendations for future focus

Comprehensive Analysis of Pizza Outlet Sales Data

Introduction
Pizza! The ultimate comfort food that's loved by people all around the world. Originating from Italy, pizza is a savory dish made from a circular flatbread topped with a variety of ingredients such as cheese, tomato sauce, meats, vegetables, and herbs. With its crispy crust, gooey cheese, and flavorful toppings, pizza is a culinary delight that's hard to resist.
Pizza is one of the most popular foods globally, with a rich history and diverse variations. From classic combinations like margherita and pepperoni to more adventurous options like Hawaiian and BBQ chicken, pizza offers endless possibilities for customization. In this analysis, we explore the most popular pizza types, favorite toppings, and flavor combinations that make pizza a beloved dish around the world.
This study analyzes transactional data from a pizza outlet, combining order details, menu information, and pricing to uncover sales patterns, customer preferences, and operational insights. The findings provide evidence-based recommendations for producers and policy makers to optimize menu offerings, pricing strategies, and operational efficiency.

Key Findings

1. Menu Diversity
The outlet offers over 30 distinct pizza types, spanning categories such as Classic, Supreme, Veggie, and Specialty. However, sales are highly concentrated: a handful of pizzas account for the majority of revenue, while several menu items show minimal traction.

Interpretation: The menu is broad, but customer demand follows the Pareto principle — ~20% of pizzas generate ~80% of sales.

 Figure 1: Bar chart of Top 5 Bestselling Pizzas (by Quantity and Revenue)
 

<img src="Pizza_Data\top_5 sales_by quantity.png" alt = "top_5 Sales" width = "60%" height= "40%">






2. Pricing and Revenue
Average pizza price: mid-range, reflecting affordability for mass-market customers.


<img src="Pizza_Data\top_5 sales_by revenue.png" alt = "top_5 Sales" width = "60%" height= "40%">







Revenue distribution: right-skewed, with most orders modest but a few large orders driving overall revenue.  
- Percentiles:  
  - 25th percentile: low-value orders  
  - Median: typical family-size purchase  
  - 90th percentile: large group orders significantly boosting revenue.  

Interpretation: While most customers buy standard pizzas, occasional bulk purchases (e.g., parties, events) are critical revenue drivers.

  Figure 2: Histogram of Revenue Distribution with KDE curve 



 <img src="Pizza_Data\sales distribution.png" alt = " Sales distribution" width = "60%" height= "40%">






3. Sales Trends
Monthly sales: Seasonal peaks observed, particularly during festive months (December) and summer gatherings.  
Daily sales: Highest on weekends, especially Fridays and Saturdays.  
- Hourly sales: Peak demand during evening hours (6–9 PM), aligning with dinner time.  

Sales are strongly tied to social occasions and leisure time, suggesting opportunities for targeted promotions.



 Figure 3: Line chart of Monthly Sales Trend




<img src="Pizza_Data\monthl sales.png" alt = "monthly Sales" width = "60%" height= "40%">






4. Category and Size Preferences
- Category dominance: Classic pizzas consistently outperform other categories.  
- Size preference: large pizzas are most popular, reflecting group consumption patterns.  
Interpretation: Customers prioritize familiar flavors and value-for-money sizes.


 Figure 4: Heatmap of Sales 
<img src="Pizza_Data\boxplot_by_revenue.png" alt = "scatter Sales" width = "60%" height= "40%">








 5. Underperforming Pizzas
Several niche or specialty pizzas show low sales volume and revenue. These items contribute little to overall performance and may dilute operational efficiency.
Menu optimization is needed to reduce waste and focus on high-demand items.

 Figure 5: Bar chart of Lowest Selling Pizzas



<img src="Pizza_Data\lowest_selling_pizzas.png" alt = "top_5 Sales" width = "60%" height= "40%">



Predictions
Seasonality will persist: Expect spikes during holidays and weekends.  
- Customer preference stability: Classic pizzas will remain dominant unless new flavors are aggressively marketed.  
-Growth opportunity: Bundling and promotions during off-peak months can smooth demand.  
-Digital ordering impact: As online platforms expand; evening and weekend peaks may intensify.


Figure 5: Pie chart of Sales Percentage by Pizza Category


<img src="Pizza_Data\sales percentage by pizza category.png" alt = "percentage Sales" width = "60%" height= "40%">



Recommendations
For Producers (Outlet Managers)
1. Menu Optimization  
   - Retain and promote top 5 bestselling pizzas.  
   - Rebrand or remove consistently underperforming items.  
   - Introduce seasonal specials to capture holiday demand.
2. Pricing Strategy
   - Maintain mid-range pricing but explore bundle deals (family packs, party combos).  
   - Offer loyalty discounts during off-peak months.

3. Operational Efficiency 
   - Increase staffing and inventory during peak hours (evenings, weekends).  
   - Streamline supply chain for high-demand categories to reduce stockouts.

For Policy Makers (Franchise Owners / Industry Regulators)
1. Data-Driven Decision Making
   - Encourage outlets to adopt sales analytics dashboards for real-time monitoring.  
   - Standardize reporting across franchises to identify regional trends.

2. Consumer Health & Diversity
   - Promote balanced menu offerings (e.g., more veggie options).  
   - Incentivize innovation in underperforming categories to diversify consumer choices.

3. Economic Strategy
   - Recognize the role of pizza outlets in local economies (employment, supply chains).  
   - Support small outlets with training in data analytics and digital marketing.
  



link to the tools and code used for this data analysis can be accessed tbhrough this link: https://github.com/iamskola/Pizza_Data_Visualisation

Conclusion
This analysis reveals that pizza sales are concentrated, seasonal, and socially driven. By focusing on bestselling items, optimizing pricing, and aligning operations with demand cycles, producers can maximize profitability. Policy makers, meanwhile, can foster industry resilience by promoting data-driven practices and menu diversification.  
Ultimately, the findings underscore the importance of analytics in food service management - turning raw sales data into actionable insights that benefit both businesses and consumers.
