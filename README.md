## TechNestIntern-Data-Analytics

 # Customer-Segmentation-Using-Clustering

This project focuses on performing Customer Segmentation using unsupervised machine learning techniques, specifically K-Means Clustering, to identify distinct groups of customers based on their behaviors and attributes. This approach is widely used in marketing analytics to personalize customer experiences and improve business strategies.

### Project Objective

To analyze customer data and group individuals into meaningful segments based on their annual income and spending behavior. These insights can help businesses:

•	Develop targeted marketing strategies

•	Enhance customer engagement

•	Increase conversion rates

•	Identify potential growth opportunities

### Methodology

**1.Data Preprocessing**

   •	Handling missing values
  
   •	Data formatting and exploration

**2.Exploratory Data Analysis (EDA)**

  •	Distribution plots
  •	Correlation heatmaps
  •	Cluster-wise visualizations

**3.Feature Scaling**

 •	StandardScaler to normalize features

**4.Clustering**

  •	K-Means algorithm
  •	Elbow Method and Silhouette Score to determine optimal cluster count

**5.Visualization**

  •	2D and 3D cluster plots using PCA for dimensionality reduction

### Key Insights

 •	Identified 5 unique customer segments with varied income and spending behaviors.

 •	Discovered a segment of low-income but high-spending customers—ideal for promotional targeting.

 •	Found high-income but low-spending individuals—potentially underserved customers.

 •	These segments help design personalized marketing strategies and improve customer lifetime value (CLV).

 # ⚡ Electric Vehicle Analysis Dashboard

A comprehensive Business Intelligence (BI) dashboard that visualizes and analyzes electric vehicle (EV) adoption trends across various manufacturers, models, and regions.

## 📌 Project Overview

This dashboard offers insights into electric vehicle usage, market share by vehicle make and model, eligibility for Clean Air Vehicle programs, and overall growth trends from 2011 to 2023.

## 🧩 Key Features

- 📊 Total Vehicles Analyzed: **150.48K**
- 🔋 Battery Electric Vehicles (BEVs): **117K (78%)**
- ⚙️ Plug-in Hybrid Electric Vehicles (PHEVs): **34K (22%)**
- 📈 EV Growth Trend: Significant increase, peaking at **37K** in a single year
- 🚘 **Top Makes**: Tesla, Nissan, Chevrolet, Ford, BMW
- 🏆 **Top Models**: Model Y (29K), Model 3 (28K), LEAF, Bolt, ID.4, Mustang Mach-E
- 🌎 EV distribution visualized on an interactive map
- ✅ CAFV (Clean Alternative Fuel Vehicle) Eligibility:
  - Eligible: 46.32%
  - Not Eligible / Clean Alt. Fuel: remainder

## 📍 Tools Used

- **Power BI** *(or Tableau/Excel – update as per your tech stack)*
- DAX (Data Analysis Expressions)
- Interactive filters: City, Utility Company, Vehicle Type

## 📈 Visualizations Included

- Pie charts (CAFV eligibility, EV type)
- Line chart (year-wise growth trend)
- Tree map (top models)
- Bar charts (make-wise vehicle count)
- Geo map (top vehicles by state)

## 🧠 Insights & Use Cases

- Identify EV adoption patterns across regions
- Assess which vehicle makes/models lead the market
- Understand vehicle eligibility under green initiatives
- Assist policymakers, environmental researchers, and utility companies with EV planning and infrastructure

# 🛍️ Exploratory Data Analysis (EDA) on Retail Sales Dataset
📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset to uncover insights about sales performance, trends, patterns, and seasonality. Using powerful data analysis and visualization tools in Python, the aim is to assist business decision-making and strategy development.

📊 Objectives

Analyze overall sales trends over time

Identify seasonality in monthly sales

Understand category-wise and region-wise performance

Highlight actionable insights using data visualizations

🧰 Tools & Technologies

Python

Pandas – data manipulation

NumPy – numerical calculations

Matplotlib & Seaborn – data visualization

📁 Dataset Summary

The dataset contains detailed retail transaction records including:

Order Date

Sales

Category & Sub-Category

Region, State, and City

Quantity, Profit, Discount

📈 Key Analyses & Visualizations

✔️ Yearly Sales Trend Shows a clear upward trend in total sales over the years.

✔️ Monthly Sales Trend Identifies sales fluctuations and key peak months.

✔️ Seasonality Highlights months with consistently high or low average sales (e.g., February and December are strong months).

✔️ Category-wise Sales Office Supplies lead in total sales, followed by Technology and Furniture.

✔️ Region-wise Sales The West region is the top performer, while the South region shows growth potential.

📌 Insights

High-performing periods: November, December, and February

Underperforming months: Mid-year (April–August)

Strategic Focus:

Boost marketing during mid-year dips

Regional growth campaigns in the South

Promote high-revenue categories more aggressively

# 🐦 Twitter-Sentiment-Analysis-using-SVM

This project analyzes the sentiments of tweets using Natural Language Processing (NLP) and a Support Vector Machine (SVM) classifier. It classifies tweets into Positive, Negative, or Neutral categories. The model is trained on labeled tweet data and visualized through graphs and word clouds.

## 📌 Project Objective

To build a machine learning model that accurately predicts the sentiment of a tweet. This helps in analyzing public opinion, tracking brand sentiment, and monitoring customer feedback in real time.

## 🔧 Technologies & Libraries Used

 - Python

 - Pandas – for data manipulation

 - NumPy – for numerical computations

 - Matplotlib / WordCloud – for visualization

 - Scikit-learn – for machine learning (SVM, TF-IDF, etc.)

 - NLTK – for natural language processing tasks


## 🔍 Key Steps in the Notebook

1. **Data Loading**  
   Load the Twitter dataset into a Pandas DataFrame.

2. **Text Preprocessing**  
   - Lowercasing  
   - Removing punctuation, stopwords, and special characters  
   - Tokenization and lemmatization

3. **Feature Engineering**  
   - Convert cleaned text into numerical vectors using **TF-IDF**

4. **Model Training**  
   - Train an **SVM classifier** on the processed data
   - Split data into training and testing sets

5. **Evaluation**  
   - Use accuracy, precision, recall, and F1-score
   - Confusion matrix for visual performance analysis

6. **Visualization**  
   - Pie chart or bar chart of sentiment distribution
   - Confusion matrix heatmap


