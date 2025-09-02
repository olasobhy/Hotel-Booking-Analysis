# Hotel-Booking-Analysis
##  Project Overview
This project analyzes hotel revenue historical data for the years **2018, 2019, and 2020**.  
The main goal is to consolidate the data, clean it, and prepare it for further analysis and visualization.

---

##  Data Preparation Steps
1. **Data Consolidation**  
   - Combined the yearly datasets (**2018, 2019, 2020**) into one dataset using **append**.

2. **Merging Additional Data**  
   - Merged the dataset with:
     - **meal_cost** (to include meal pricing information).  
     - **market_segment** (to include market segmentation details).

3. **Feature Engineering**  
   - Added new calculated columns:
     - `Total_nights` → total number of nights per booking.  
     - `Total_revenue` → total revenue generated per booking.
     - `Total_guests` → total guests per booking (adults + children + babies).  
     - `Quarter` → extracted from `arrival_date_month` to analyze seasonal trends.


4. **Data Cleaning**  
   - Removed **Null / missing values** to ensure data quality.

---
