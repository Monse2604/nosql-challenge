# NoSQL Challenge Solution

This repository contains the complete solution for the NoSQL Challenge. The solution is divided into two Jupyter Notebook files that handle the setup and analysis required to solve the challenge.

## Files

1. **`NoSQL_setup_starter.ipynb`**
   - This file contains the setup process for connecting to the MongoDB database.
   - It includes:
     - Installing necessary libraries (`pymongo`, etc.).
     - Setting up the connection to the MongoDB database (`uk_food`) and importing the dataset.
     - Verifying the successful setup by checking the database and collection structure.

2. **`NoSQL_analysis_starter.ipynb`**
   - This file contains the exploratory analysis and queries performed on the `establishments` collection.
   - Key sections:
     - **Querying specific establishments**:
       - Finding establishments based on hygiene score, rating value, and geographic proximity.
     - **Data transformations**:
       - Converting `RatingValue` and coordinates (`latitude` and `longitude`) to appropriate data types.
     - **Aggregations**:
       - Counting establishments grouped by Local Authority with specific conditions.
     - Results are converted to Pandas DataFrames for easier analysis and visualization.
