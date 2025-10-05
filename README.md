Airbnb Data Analysis Project
Project Overview

This project analyzes Airbnb listings data to uncover insights that help hosts optimize pricing, improve guest satisfaction, and understand market trends.
The notebook performs data cleaning, exploratory data analysis (EDA), visualization, and draws key recommendations.

📂 Files in Repository

Airbnb_Open_Data.xlsx → Raw dataset

airbnb_analysis_notebook.ipynb → Jupyter Notebook with analysis and visualizations

plots/ → Generated visualizations (price distribution, neighborhood insights, etc.)

top_hosts_by_listings.csv → Export of top hosts with the highest number of listings

🔍 Analysis Performed

Data Cleaning

Converted price and service fee columns into numeric format

Handled missing values and irrelevant columns

Exploratory Data Analysis (EDA)

Distribution of property and room types

Top neighborhoods by number of listings

Average price trends by neighborhood and room type

Host analysis: most active hosts and identity verification

Correlation analysis (price vs reviews, price vs service fee)

Visualizations

Price distribution histogram

Scatter plot: price vs number of reviews

Scatter plot: price vs service fee

Bar chart: top neighborhoods

Heatmap of correlations

Key Insights

Certain neighborhoods dominate listing volume

Verified hosts generally attract more reviews

Service fee is strongly correlated with price

Some outliers in price distribution significantly skew averages

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/airbnb-analysis.git
cd airbnb-analysis


Install dependencies (if not already available):

pip install pandas matplotlib seaborn openpyxl


Run the notebook:

Open in Jupyter Notebook or Google Colab

Upload Airbnb_Open_Data.xlsx when prompted

📊 Results & Recommendations

Hosts in high-demand neighborhoods can set premium prices.

Verified hosts with strong review counts tend to attract more bookings.

Outlier detection is important to avoid misleading averages.

Data-driven strategies can improve both pricing models and guest experience.

📜 License

This project is for educational purposes only and uses publicly available Airbnb dataset.
