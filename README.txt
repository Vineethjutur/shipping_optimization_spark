# Shipping Optimization Project (Data 603)

This project implements a distance-based optimization approach for a shipping problem using Apache Spark, Google Maps API, and Python.

## Project Objective

To determine the most efficient delivery routes across multiple US cities, minimizing travel distance. The starting location is Harrisburg, PA, and the project utilizes the Google Distance Matrix API to calculate pairwise distances.

## Key Components

- SparkSession Initialization: Used for distributed computing across city pairs.
- Google Maps Distance Matrix API: Retrieves travel distances in both kilometers and miles between 20 major US cities.
- Distance Matrix Creation: All city-to-city combinations are generated and stored.
- Data Processing: Distances are saved and analyzed for optimization.

## Technologies Used

- Python (use version 3.10)
- Apache Spark
- Google Maps Distance Matrix API
- Pandas
- Java version 11
- ThreadPoolExecutor (concurrent.futures)

## File Descriptions

- ~/CSV files/uscities.csv : Input file to be downloaded and give the correct path where required.
- ~/CSV files/delivery_logs.csv : Input file to be downloaded and give the correct path where required.
- Data_603_Project_Implementation_Final.ipynb: Jupyter notebook containing the implementation and logic.
- distance_matrix_long.csv: Output file storing pairwise distances between cities.

## Conclusion

This project successfully demonstrates the use of big data tools like Apache Spark and API integration to tackle logistics optimization problems. Future work can extend this to include route optimization (e.g., TSP) and real-time constraints.

## How to Run

1. Install required packages: pandas, requests, pyspark
2. Set up your Google Maps API key in the notebook.
3. Execute all cells to compute and store distances between cities.
