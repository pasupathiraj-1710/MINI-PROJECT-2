# MINI-PROJECT-2
Luxury Housing Sales Analysis - Bengaluru

# Luxury Housing Sales Analysis  

## Overview  
This project analyzes **luxury housing sales data** in Bangalore using an end-to-end pipeline of **Python (data preprocessing), SQL (data warehousing), and Power BI (dashboarding)**.  
It delivers insights into **market trends, builder performance, amenity impact, booking conversions, and buyer preferences** to support data-driven decision-making.  


##  Workflow  

### 1. Data Cleaning & Feature Engineering (Python)  
- Cleaned 100k+ raw records for consistency.  
- Handled missing values (`Amenity_Score`, `Booking_Status`).  
- Normalized categorical fields (`Builder`, `Micro_Market`).  
- Engineered features:  
  - `Price_per_Sqft`  
  - `Quarter_Number`  
  - `Booking_Flag`  
- Exported cleaned dataset for SQL integration.  

### 2. Data Warehousing (SQL)  
- Created SQL schema for housing dataset.  
- Loaded processed data via **SQLAlchemy**.  
- Ran validation queries for row counts, booking status distribution, and builder-level averages.  

### 3. Visualization & Insights (Power BI)  
- Connected Power BI to SQL warehouse.  
- Developed interactive visuals:  
  - Filters by **Builder, Quarter, Micro-Market**  
  - **Geo maps** for housing clusters  
  - **Builder rankings, amenity impact, booking conversions**  

##  Key Business Insights  
- **Quarterly Trends**: Demand varies strongly across micro-markets; some remain consistently high.  
- **Builder Dominance**: Top builders capture majority of revenue, highlighting brand trust.  
- **Amenities Matter**: Higher amenity scores correlate with higher booking conversions.  
- **Configuration Demand**: 3BHK units dominate sales volume; 4BHK drives revenue.  
- **Sales Channels**: Direct builder sales outperform broker-driven deals.  
- **Buyer Preference**: Ready-to-move properties attract more bookings than under-construction ones.  
- **Geographical Hotspots**: Whitefield, Sarjapur Road, and North Bangalore are leading clusters.  


