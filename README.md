# etl-to-dashboard-python-powerbi
This project demonstrates a complete workflow from ETL (Extract, Transform, Load) using Python to interactive dashboard creation with Power BI. It showcases how raw data is collected, processed, and visualized to deliver actionable business insights. The project highlights automation, data modeling, and business intelligence best practices.
# ETL to Dashboard: Python & Power BI
This project demonstrates a full-stack data pipeline that extracts, transforms, and loads data using Python, followed by interactive dashboarding using Power BI. It is designed to bridge the gap between raw data and meaningful business insights, focusing on automation, data quality, and visualization.
# 🎯 Objectives
1. Build an automated ETL pipeline using Python.

2. Clean, transform, and load data into a structured format (CSV, database, or Excel).

3. Connect Power BI to the processed data source.

4. Design dashboards to deliver actionable business insights.

5. Demonstrate an end-to-end Data Engineering to BI workflow.
# 💻  Tech Stack
| Tool/Tech       | Purpose                             |
|-----------------|-------------------------------------|
| **Python**      | Data extraction, transformation     |
| **Pandas**      | Data wrangling and analysis         |
| **Power BI**    | Visualization and reporting         |
| **Jupyter**     | Exploratory data analysis (optional)|
| **CSV/Excel**   | Final data export format            |
| **Scheduler**   | (Optional) Automate ETL execution   |

# 📁 Project Structure
```text
etl-to-dashboard-python-powerbi/
├── data/                  # Raw and cleaned data files
├── python/                # ETL scripts in Python
├── powerbi/               # .pbix file and screenshots
├── notebooks/             # Jupyter notebooks
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```
# 🚀 How to Run
## 1. Clone the Repository
```bash
git clone https://github.com/Mahpara810/etl-to-dashboard-python-powerbi.git
cd etl-to-dashboard-python-powerbi
```
## 2. Install Python Dependencies
```bash
pip install -r requirements.txt
```
## 3. Data Source


The dataset used in this project is publicly available on Kaggle:  
[New York Airbnb Open Data 2024](https://www.kaggle.com/datasets/vrindakallu/new-york-dataset)
## 4. Run the ETL Notebook

• Open the Jupyter Notebook located at:  
  `notebooks/New York Airbnb Open Data 2024.ipynb`

• Update any file paths or data source URLs inside the notebook as needed.

• Run all cells to perform the ETL process (data cleaning, transformation, and export).

• After execution, verify that the cleaned and transformed data files are saved in the `<data_folder>/` or `<output_folder>/`.

# 5. Open Power BI Dashboard
• Open the .pbix file in the powerbi/ folder.

• Ensure the data source is correctly linked (e.g., local Excel/CSV or database).

• Refresh the dashboard to load the latest data.

## 6. Explore the Dashboards!
• Explore and analyze the visualized data insights to uncover trends, patterns, and key metrics.

# ✨ Features
End-to-end ETL + BI pipeline

🧹 Data cleaning and formatting

📊 Professional Power BI dashboards

⏱️ Easily extendable for scheduling and automation

🧪 Ideal for demonstrating Data Engineering + BI skills

# 🧠 Business Problem
• How many total listings are available?

• What are the most common types of rooms?

• Which neighbourhood groups have the highest number of listings?

• What is the average price across different neighbourhood groups?

• What are the most common property types in specific areas?

• How do listings vary by region in price and rating?

• Who are the top hosts by number of listings?

• What are the price and rating averages per host?

• Are there hosts with high ratings and high revenue? 

# 📊 Dashboard
![image1](https://github.com/user-attachments/assets/4a6a7926-5642-4273-98d8-8d04f57ef626)

![image2](https://github.com/user-attachments/assets/47eb4c7d-05d7-42f6-8461-4689afd30c10)

![image3](https://github.com/user-attachments/assets/e2032b39-8795-43ae-9d20-6a18397a84c0)

![image](https://github.com/user-attachments/assets/b9be1112-faf6-4880-a061-db28f8f334f9)

![image5](https://github.com/user-attachments/assets/13b8dc7d-b1a8-474a-8376-d229f07eb87e)





# ✅  Use Cases
This project framework can be adapted for:

• Sales & Revenue Analysis

• Marketing Campaign Performance

• Financial Forecasting

• Customer Behavior Analysis

• Supply Chain Monitoring
# 📚 Resources and References
## 📄 New York Airbnb Open Data 2024

**Source:** [New York Airbnb Open Data 2024](https://www.kaggle.com/datasets/vrindakallu/new-york-dataset)  
This dataset captures every Airbnb listing in New York City as of **January 5, 2024**. It’s published by Vrinda Kallu and contains the following key attributes:  

- **Listing identifiers:**  
  - `id`, `name`, `host_id`, `host_name`  
- **Location details:**  
  - `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude`  
- **Listing characteristics:**  
  - `room_type`, `price`, `minimum_nights`  
- **Review metrics:**  
  - `number_of_reviews`, `last_review`, `reviews_per_month`  
- **Host activity & availability:**  
  - `calculated_host_listings_count`, `availability_365`  

Use this data for market‐analysis, pricing‐trend modeling, neighbourhood‐level comparisons, or machine‐learning experiments.
## 📘 Additional Learning Resources (if applicable)

- **ETL with Python**  
  - Real Python tutorial: “[Building an ETL Pipeline in Python](https://realpython.com/python-etl-pipeline/)”  
  - Towards Data Science article: “[Designing ETL Pipelines with Pandas](https://towardsdatascience.com/designing-etl-pipelines-with-pandas-4f9ce64b56ef)”

- **Data Cleaning & Transformation**  
  - Kaggle micro-course: “[Data Cleaning](https://www.kaggle.com/learn/data-cleaning)”  
  - Official Pandas guide: “[Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)”

- **Power BI**  
  - Microsoft Docs: “[Get started with Power BI Desktop](https://docs.microsoft.com/power-bi/fundamentals/desktop-getting-started)”  
  - Guy in a Cube YouTube channel: “[Power BI Tutorials](https://www.youtube.com/c/GuyinaCube)”

- **Data Visualization**  
  - Matplotlib tutorial: “[Matplotlib: Visualization with Python](https://matplotlib.org/stable/tutorials/index.html)”  
  - Seaborn documentation: “[Seaborn: Statistical Data Visualization](https://seaborn.pydata.org/)”

- **Machine Learning & Modeling (optional)**  
  - Scikit-learn user guide: “[Supervised Learning](https://scikit-learn.org/stable/supervised_learning.html)”  
  - IBM Developer: “[Customer Churn Prediction with Python](https://developer.ibm.com/articles/customer-churn-python/)”


# 🤝 Contribution
Contributions are welcome! Fork the repo, make changes, and submit a pull request. Please include clear comments and explanations for any new features.
# 📝 License
This project is licensed under the [MIT License](LICENSE).






