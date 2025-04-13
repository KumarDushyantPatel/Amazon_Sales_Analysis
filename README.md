# Amazon_Sales_Analysis

 **Steps For making Power BI Dashboard**
 
1. Data Import & Cleaning
Loaded amazon.csv into Power BI
Cleaned data by removing null/invalid rows (e.g., blank categories, 0 pricing)
Updated column types: Prices (Decimal), Ratings & Review Count (Numeric)

2. Data Transformation
Added calculated column for discount percentage:
discount_percentage = (actual_price - discounted_price) / actual_price * 100

3. Dashboard Page 1: Overview
KPI Cards: Total Products, Avg Rating, Avg Discount, Total Reviews
Bar Chart: Top 10 Products by Rating Count
Donut Chart: Product Count by Category
Scatter Chart: Discount % vs Rating
Slicers: Category, Rating, Discount Percentage
Navigation: Button to Page 2

4. Dashboard Page 2: Detailed View
Table: Product-wise Summary (Price, Rating, Discount %)
Bar Chart: Avg Rating by Category
Bar Chart: Avg Discount % by Category
Scatter Chart: Discount % vs Rating (Bubble Size = Review Count)
Smart Slicers and Page Navigation

5. Design & Interactivity
Consistent color theme (Blue, Orange, White)
Aligned layout with Segoe UI font
Tooltips and titles activated for all visuals


**Steps for making Power Point Presentation** 
I developed a 9-slide PowerPoint presentation to effectively communicate the insights derived from the Power BI dashboard analyzing Amazon product data. Below is the structure of the presentation:

Slides 1–2: Title & Introduction
Introduced the project objectives and provided an overview of the analytical approach.

Slide 3: Key Performance Indicators (KPIs)
Presented key metrics such as Average Rating (4.10), Average Discount (0.48%), and Total Review Count (1.19K) to summarize overall product performance.

Slide 4: Category-wise Ratings
Displayed average customer ratings across different product categories to identify top-performing segments.

Slide 5: Top Products & Pricing Trends
Highlighted pricing patterns among top-rated products, focusing on actual versus discounted prices.

Slide 6: Product Distribution by Category
Illustrated the distribution of products across various categories to understand market composition.

Slide 7: Discount % vs Customer Ratings
Analyzed the relationship between discount percentages and customer ratings to assess the impact of pricing strategies on customer satisfaction.

Slide 8: Strategic Recommendations
Provided actionable insights based on the analysis, such as optimizing discount strategies and focusing on high-engagement categories.

Slide 9: Thank You 
Concluded the presentation.
