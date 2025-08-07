# Nykaa---Heath-and-Wellness-Data-Analysis-EDA-
This project focuses on performing Exploratory Data Analysis (EDA) on Nykaa's product and sales dataset. The goal is to extract meaningful insights about customer behavior, product performance, and sales trends.
## Objective

To analyze Nykaa's Healthcare & Wellness segment using web-scraped product data and extract insights for business decisions such as pricing strategy, inventory planning, marketing focus, and product demand.

## Data Source

The dataset was created by web scraping Nykaa's Healthcare & Wellness section using Python libraries:
- `requests` for HTTP requests
- `BeautifulSoup` for HTML parsing
- `pandas` for data handling
- `re` for regex-based cleaning

## Dataset Features

Each product includes the following:
- Product Name
- Brand
- Category and Sub-category
- MRP and Discount Price
- Ratings
- Review Count
- Bestseller Status
- Gift Availability

## Key Analysis Performed

- Top brands by product count
- Highest-reviewed products
- Categories with most SKUs
- Sub-category distribution
- Price distribution analysis
- Gifted product trends
- Bestsellers ratio by sub-category
- Relationship between price and reviews

## Insights

- Most products are priced between ₹250–₹1000, indicating budget-conscious customer base
- Wellness, Sports Nutrition, and Health Supplements dominate in product count
- Sub-categories like Juice and Oil have the highest bestseller ratios
- Brands like Mamaearth, Oziva, Kapiva, and Fast&Up are top performers
- Affordable products receive more customer engagement and reviews
- High-end premium products exist but have fewer reviews

## Suggestions

- Focus marketing and promotions on mid-range products
- Increase visibility of high-performing sub-categories like Juice and Oil
- Strengthen partnerships with brands having strong review count and product presence
- Encourage customers to leave reviews to build trust in new products
- Promote combo gift kits in top health categories

## Tools Used

- Python (Jupyter Notebook)
- Pandas
- BeautifulSoup
- Matplotlib, Seaborn
- Regex for data cleaning
