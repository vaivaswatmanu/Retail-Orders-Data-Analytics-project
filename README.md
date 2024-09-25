# **Retail Orders Data Analytics Project**

## **Project Description**

This project aims to analyze retail sales data from a Kaggle dataset to uncover valuable insights about product performance, revenue generation, and regional sales patterns. The analysis is conducted using Python for data manipulation and SQL for complex queries, and the results are visualized using Matplotlib and Seaborn to provide business insights.

### **Key Features:**
1. **Top 10 Revenue-Generating Products**: Identifying the products generating the most revenue.
2. **Top 5 Highest Selling Products in Each Region**: Analyzing the top-selling products by region.
3. **Month-over-Month Sales Growth Comparison (2022 vs. 2023)**: Comparing sales growth over months between the two years.
4. **Category-wise Monthly Sales Trends**: Identifying which months had the highest sales in each category.
5. **Sub-Category Sales Growth**: Identifying the sub-category that experienced the highest growth in 2023 compared to 2022.

The project demonstrates how to manipulate data using **Pandas**, store and query data in **MySQL**, and create insightful visualizations with **Matplotlib** and **Seaborn**.

---

## **Dataset**
The dataset used for this analysis is sourced from Kaggle's [Retail Orders Dataset](https://www.kaggle.com/datasets/ankitbansal06/retail-orders). The dataset includes details such as order dates, product categories, sales price, discount percentage, and cost price.

---

## **Project Workflow**

1. **Data Extraction**:
   - The data was downloaded using the Kaggle API and extracted from a zip file.

2. **Data Cleaning**:
   - Null values were handled, and data types were formatted correctly.
   - Columns were renamed for easier manipulation.
   
3. **Data Manipulation**:
   - New columns such as profit were derived, and unnecessary columns were dropped.

4. **Database Integration**:
   - The cleaned data was stored in a MySQL database, and SQL queries were used to generate key insights.

5. **Data Visualization**:
   - Insights were visualized using Matplotlib and Seaborn.

---

## **How to Run the Project**

### **1. Prerequisites:**

Make sure you have the following installed:
- Python (v3.7 or later)
- MySQL
- Python Libraries:
    - Pandas
    - Matplotlib
    - Seaborn
    - SQLAlchemy
    - Kaggle API
    - Zipfile

### **2. Kaggle API Setup**

To access the dataset using the Kaggle API:

1. Install the Kaggle package:
    ```bash
    pip install kaggle
    ```

2. Obtain your Kaggle API key from your Kaggle account (Profile -> Account -> Create API Token).

3. Place the `kaggle.json` file in the `.kaggle/` directory.

4. Run the following code to download the dataset:
    ```python
    !kaggle datasets download ankitbansal06/retail-orders -f orders.csv
    ```

---

### **3. Running the Python Script**

The Python script performs the following steps:
1. Downloads the dataset from Kaggle.
2. Reads the dataset into a Pandas DataFrame.
3. Cleans and processes the data.
4. Stores the data in a MySQL database.
5. Runs SQL queries to extract insights.
6. Visualizes the results.

You can run the main script using:
```bash
python data_analytics.py




