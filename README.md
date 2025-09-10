# Airbnb Listings Analytics Dashboard

Data Source: https://mavenanalytics.io/data-playground/airbnb-listings-reviews

# Project Overview

This project explores Airbnb listings data to uncover insights into pricing, amenities, host performance, and customer reviews across different regions. The analysis integrates Python for preprocessing and advanced exploration, Power BI for interactive visualizations, and DAX/Power Query for business logic and transformations.
The final deliverable is an interactive dashboard designed to provide stakeholders with a clear understanding of what drives listing performance and guest satisfaction.
________________________________________
# Objectives

  1.	Identify the distribution of listings across cities, property types, and host categories.
   
  2.	Analyze the impact of amenities, host status, and review scores on listing prices.
	
  3.	Build measures to track trends in reviews, hosts, and pricing over time.
	
  4.	Create KPIs such as value score, superhost count, and % listings with top amenities.
	
  5.	Enhance data usability by handling JSON reviews, geolocation lookups, and categorization of key attributes.
________________________________________
# Data Preparation & Transformation

  Python (Pandas, Geopy, JSON Handling)
  
  •	Extracted Listing ID and amenities into a structured dataset.
  
  •	Parsed review data stored in JSON format into a normalized DataFrame for analysis.
  
  •	Used Geopy to convert latitude and longitude into city, state, and country details.
  
  •	Identified and aggregated the Top 10 amenities across listings.
  
  •	Exported transformed data into CSV for downstream Power BI integration.

# Power Query (M Language)

  •	Cleaned and standardized columns such as amenities, host type, property category.
  
  •	Created categorical bins for Accommodates (2–20) into ranges like “2–4”, “5–8”, etc.
________________________________________

# Dashboard Design & Features

  Key Visuals:
  
  •	Total Listings by Property Category – “Where Are Guests Staying?”
  
  •	Top Listings by Price Segment – “High-Value Homes by Budget Range”
  
  •	Top Listings by Host Category – “Standout Hosts and Their Listings”
  
  •	Host Trends Over Time – “How Hosting Has Evolved”
  
  •	Review Trends (Count, Rating, Hosts) – “Guest Voices Over Time”
  
  •	City Insights Across Features – compare price, amenities, and reviews across cities.
  
  •	Factors Affecting Price – interactive scatterplots with relative categorical features as parameters.

# Enhancements:

  •	Parameter-driven matrices to track % of listings meeting key KPIs (e.g., % with top amenities, % superhosts).
  
  •	Parameter-driven matrices to dynamically switch between metrics like Price, Reviews, and Value Score.
________________________________________
# Key Findings

  1.	Amenities Drive Price: Listings with premium amenities (Wi-Fi, Pool, Parking) commanded significantly higher prices.
  	
  2.	Superhosts Outperform: Superhosts not only had more listings but also higher average ratings and occupancy rates.
  	
  3.	Location Matters: Central city listings had higher prices but lower value scores compared to suburban options.
  	
  4.	Review Influence: Properties with ≥4.5 ratings attracted more bookings and achieved price premiums.
  	
  5.	Capacity Segmentation: Accommodates range directly correlated with pricing tiers — larger groups led to higher listing costs.
  	
  6.	Value Score Insights: Some mid-priced properties offered better “value” compared to premium listings, balancing reviews and price.
  	
________________________________________
# Conclusion
  This project demonstrates the end-to-end analytics workflow — from data acquisition, transformation, and enrichment (Python & Power Query) to business-ready KPIs and visual storytelling in Power BI.
  It highlights technical depth (JSON parsing, geolocation, DAX modeling) and storytelling ability (dashboard narratives, trend analysis, and actionable findings).
  The final dashboard provides a 360° view of Airbnb performance, empowering hosts, investors, and stakeholders to identify what drives listing success.
