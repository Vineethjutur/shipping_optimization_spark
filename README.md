# 🚚 Shipping Optimization with Apache Spark

## 📌 Overview
This project solves the **Vehicle Routing Problem (VRP)** for optimizing delivery routes across U.S. cities.  
Using **Apache Spark** for big data processing, **Google OR-Tools** for optimization, and **MongoDB** for storage, we designed a pipeline to efficiently compute and visualize optimal delivery routes.  

This was implemented as a **Big Data final project at UMBC** (Spring 2025).

---

## 🛠️ Tech Stack
- **Big Data:** Apache Spark, Hadoop  
- **Optimization:** Google OR-Tools (VRP Solver)  
- **Databases:** MongoDB  
- **APIs & Data Sources:** Google Maps API, OpenStreetMap, U.S. Census Bureau  
- **Visualization:** Plotly, Matplotlib  
- **Languages:** Python  

---

## 📊 Dataset
- **City Coordinates:** U.S. cities with population data (U.S. Census).  
- **Distance Matrix:** Computed using Google Maps API and OpenStreetMap (20GB+ processed data).  
- **Synthetic Delivery Logs:** Generated to simulate large-scale shipping demand.  
- Due to file size, only **sample data** is shared in `data/sample/`.

---

## 🔎 Methodology
1. **Data Pipeline with Spark**  
   - Ingested city data, distance matrix, and delivery logs (20GB+).  
   - Preprocessed large-scale data using PySpark transformations.  

2. **Vehicle Routing Optimization**  
   - Implemented **VRP solver** with Google OR-Tools.  
   - Optimized routes from **Harrisburg, PA to 50+ U.S. cities**.  

3. **Database & Visualization**  
   - Stored results in **MongoDB collections** for reporting.  
   - Created interactive maps and dashboards using **Plotly**.  

---

## 📈 Results
- Optimized **top 10 delivery routes** by distance and cost.  
- Reduced **fuel cost and travel distance by ~18%** compared to naive routing.  
- Visualized delivery routes with **population overlays** for business insights.  

