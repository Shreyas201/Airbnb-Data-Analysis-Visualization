# Airbnb Data Analysis & Visualization

## 📌 Project Overview
This project explores Airbnb listing data of Seattle (USA) combined with calendar data to derive insights into pricing trends, revenue growth, and bedroom-based pricing variations, helping hosts optimize their pricing strategies and enabling travelers to make informed decisions.

## 📂 Dataset Details
The project utilizes two primary datasets:

### 1️⃣ Listing Data
Contains 92 columns with detailed information about Airbnb properties.
Key columns of interest:
- Zipcodes – Geographic location of the listings.
- Price – The listed price per night.
- Number of Bedrooms – Total bedrooms per listing.
- Date – The date of listing.
### 2️⃣ Calendar Data
Provides daily availability and pricing details for each listing.
Key columns:
- Listing ID – Unique identifier for each property.
- Available – Whether the listing is available for booking.
- Price – The price for that specific date.
- Date – The corresponding calendar date.
- To analyze long-term trends, I combined these datasets by joining the data on the Listing ID, allowing us to track the pricing trends across time and geography.

## 🖥️ Tableau Dashboard & Visualizations
I designed an interactive dashboard with five key visualizations to provide a comprehensive market overview.

### 📊 1. Price by Zipcode – Bar Graph
Purpose: Identify price variations across different zip codes within Seattle.
Insights:
- Certain zip codes have significantly higher average prices.
- Some regions have a mix of low and high-priced listings, indicating diverse property types.
### 🗺️ 2. Price by Zipcode – Area Map
Purpose: Provide a geographical perspective on Airbnb prices within Seattle.
Insights:
- High-demand tourist areas have higher listing prices.
- Less dense areas tend to have lower prices.
### 📈 3. Revenue Growth for 2016
Purpose: Track how Airbnb’s revenue changed throughout 2016.
Insights:
- Revenue spikes during peak travel seasons (summer break, holidays).
- A slow revenue growth is observed towards the year-end, possibly due to seasonality.
### 💰 4. Average Price per Bedroom
Purpose: Compare the average price per night based on the number of bedrooms.
Insights:
- One-bedroom apartments have moderate pricing, while two-bedroom properties show a higher price jump.
- Luxury listings with 4+ bedrooms command premium pricing, often 2x or 3x the price of smaller listings.
### 🏡 5. Distinct Count of Bedroom Listings
Purpose: Understand the distribution of Airbnb properties based on bedroom count.
Insights:
- One-bedroom listings dominate the market.
- Larger properties (4+ bedrooms) are fewer, suggesting they are premium or for group stays.

## 📢 Key Findings & Insights
### 1. Price Distribution & High-Priced Areas
- Prices vary significantly by zip code, with certain areas commanding much higher rates.
- High-priced listings are concentrated in prime tourist areas and downtown regions.
###  2. Revenue Trends & Seasonal Impact
- High Growth (Jan to Apr): The revenue growth from January to April shows a sharp increase, likely driven by early-year demand, including post-holiday bookings and winter travel trends.
- Steady and Surge Growth (Apr to Dec): From April to November, growth stabilizes with a steady increase, followed by a significant holiday season surge in December, reflecting increased bookings during the summer and holiday periods.
### 3. Bedroom Pricing Strategy
- Two-bedroom listings see the highest demand (reflected in both count & pricing).
- Larger properties (4+ bedrooms) are high-value, but their supply is limited.
### 4. Market Demand
- There are clear pricing patterns based on seasonality and bedroom count.
- Properties located closer to the sea tend to have higher prices, indicating that proximity to the coast significantly influences rental rates.

## 🚀 Tools & Techniques Used
- Tableau: For visualizations and dashboard design.
- Excel: Data cleaning and preparation before importing into Tableau.
- Data Blending & Joins: Combined Listings & Calendar datasets based on Listing ID

## 📌 Future Enhancements
- Add predictive analytics to forecast Airbnb pricing trends using machine learning.
- Incorporate customer reviews to analyze price-to-rating correlations.
- Include competitive analysis with hotels & alternative short-term rentals.

## 📌 Conclusion
By understanding pricing trends, revenue growth, and seasonal impacts, Airbnb hosts can optimize their listings for higher earnings. Travelers can also benefit by identifying the most cost-effective times and locations to book stays, based on data-driven insights.

## Reference:
- Dataset: -
https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset?resource=download#:~:text=more_vert-,Airbnb%20Listings%202016%20Dataset,-Dataset%20of%202016
- This project was guided by a comprehensive tutorial on YouTube, which can be found at: -
https://www.youtube.com/watch?v=zOR0-nygfDE
