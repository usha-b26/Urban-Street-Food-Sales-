🍜 Urban Street Food Vendor Survival Analysis
==============================================
📌 Project Overview

This project analyzes real-world street food vendor data to understand factors affecting vendor survival. Using Python, I performed data cleaning, exploratory data analysis (EDA), and built visualizations to uncover key business insights.

🎯 Objectives
Analyze vendor survival patterns
Identify impact of licensing, location, and revenue
Explore statistical relationships in the dataset

--🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn

--📂 Dataset
Real-world vendor dataset
Includes features like city, license status, revenue, zone, and survival status
🧹 Data Preprocessing
Handled missing values using median imputation
Standardized categorical variables
Cleaned and structured data for analysis

--📊 Analysis Performed
Used NumPy for computations (mean, median, filtering)
Applied Pandas groupby for aggregation
Evaluated survival rates by:
City
License status

--📈 Visualizations
Pie Chart → Survival distribution
Bar Plot → Impact of licensing
Count Plot → Zone-wise vendor analysis
Histogram → Revenue distribution
Heatmap → Feature correlations


--🔍 Key Insights
Licensed vendors show higher survival rates
Location significantly impacts vendor success
Revenue trends strongly influence survival outcomes

--🧠 Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Statistical Analysis

--🚀 How to Run
--pip install pandas numpy matplotlib seaborn
--python analysis.py**
--📎 Project Structure
--├── data/
--├── notebooks/
--├── images/
--├── analysis.py
--└── README.md
⭐ Conclusion


# Urban Street Food Vendor Survival Analysis

This repository contains the database schema and analytical framework for studying the survival rates of urban street food vendors. The dataset tracks vendor demographics, operational overheads, financial performance, regulatory compliance, and environmental factors across multiple cities to determine what drives long-term business viability.

## Database Setup

The project uses a MySQL database named `street_food_analysis`. Follow the instructions below to create the schema and import the dataset.

### Prerequisites
* MySQL Server (v8.0+ recommended) installed and running.
* Command Line Interface (CLI), Command Prompt, or Git Bash.

### Configuration Steps

1. **Log into your MySQL server:**
```bash
   mysql -u root -p
2.Create the target database:
Run the following commands inside the MySQL shell to initialize the database:
   CREATE DATABASE street_food_analysis;
   EXIT;
3.Import the dataset:
Navigate to the directory where your .sql file is saved and execute the import command:
   mysql -u root -p street_food_analysis < vendor_survival.sql





This project highlights how data analysis can be used to derive meaningful insights and support decision-making for small businesses.
