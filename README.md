# Zomato Restaurant Market Analysis

This project explores strategic insights from Zomato restaurant data across India, with a focus on customer satisfaction, pricing, menu variety, and regional performance. The goal is to identify what makes a restaurant successful on the platform and provide actionable recommendations for business decision-makers.

---

## Project Objectives

- Identify drivers of high customer ratings  
- Analyze pricing strategy vs. customer sentiment  
- Compare performance between Delhi-NCR and other regions  
- Highlight top-performing localities for potential expansion  
- Understand the ideal number of cuisines per restaurant  

---

## Key Business Insights

- Mid-range pricing correlates with higher customer satisfaction  
- Customer vote counts are strong trust indicators  
- Offering 3–5 cuisines tends to maximize rating potential  
- Weighted locality scoring helps guide expansion strategy  

---

## Tools & Technologies

- **Language & Stack**: Python (Pandas, Matplotlib, JSON, Requests)  
- **Notebook Environment**: Jupyter Notebook  
- **Data Source**: Kaggle + Zomato API  
- **Visualizations**: Bar, Pie, Line, Bubble, and Scatter charts  

---

## Dataset Details

- **Source**: [Zomato Restaurants Dataset on Kaggle](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)  
- **Additional Info**: Raw restaurant data fetched via [Zomato API](https://developers.zomato.com/documentation)

**Key Columns Included:**
- `Restaurant Id`: Unique ID for each restaurant  
- `Restaurant Name`, `Address`, `City`, `Locality`  
- `Longitude`, `Latitude`: Geolocation data  
- `Cuisines`: Comma-separated cuisine list  
- `Average Cost for Two`: Local currency  
- `Has Table Booking`, `Has Online Delivery`, `Price Range`  
- `Aggregate Rating`, `Rating Color`, `Rating Text`, `Votes`  
- `Country Code`, `Currency`

The final structured data was saved to a `CSV` file and used for all downstream analysis.

---

## Repository Structure

- `notebooks/`: Full analysis and visualizations
- `data/`: Clean dataset
