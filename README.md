Boston Airbnb Analysis
Project Overview

This project analyzes the Boston Airbnb dataset to explore seasonal pricing, availability, and listing quality. The goal is to help travelers identify affordable, high-quality stays across neighborhoods and seasons.

Business Questions

  How do prices and availability vary by season and weekends?

  Which neighborhoods offer the best value and accessibility?

  Which areas provide affordable, high-rated “scenic” stays?


Dataset

  listings.csv – Listing details (price, location, room type, review scores)

  calendar.csv – Daily availability and pricing

  reviews.csv – Guest reviews (not used in analysis)

Data Cleaning & Processing

   Converted price fields to numeric

  Extracted month, day, season from dates

  Created flags for weekend vs weekday and availability

  Filtered high-quality listings (review score ≥ 90)

Key Findings

   Summer and Fall have the highest prices; Winter has more availability

  Weekends are generally more expensive than weekdays

  Central neighborhoods with high listing density offer better booking flexibility

  Scenic, high-quality stays are more affordable in Winter and Spring

Optional Price Prediction

   Built a linear regression model using bedrooms, bathrooms, property, and room type

   Model explains ~42% of price variance, indicating location and seasonality are major factors

Visualizations

  Seasonal pricing and availability charts

  Weekend vs weekday comparisons

  Neighborhood density and scenic stay affordability

Tools

  Python, Pandas, NumPy, Matplotlib, Scikit-learn

 
