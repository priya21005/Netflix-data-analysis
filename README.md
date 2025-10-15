📂 Dataset

The dataset (CSV format) contains detailed information about Netflix titles, including:

Title, Type (Movie/TV Show)

Director, Cast

Country, Release Year

Rating, Duration, and Genre (listed_in)

Date Added

🛠️ Tools & Libraries Used

Python

NumPy – numerical computation

Pandas – data cleaning and manipulation

Matplotlib & Seaborn – data visualization

📊 Key Steps in Analysis

Data Loading & Inspection
Loaded dataset using Pandas and reviewed structure using .head() and .info().

Data Cleaning

Checked for missing/null values

Handled duplicates

Standardized column names and formats

Exploratory Analysis

Count of Movies vs. TV Shows

Top genres on Netflix

Trend of content added over years

Distribution of ratings

Most frequent countries producing Netflix content

Visualizations
Used Matplotlib and Seaborn to create bar charts, heatmaps, and trend plots for better insights.

💡 Insights

Netflix hosts more movies than TV shows.

Most content comes from the United States and India.

TV-MA and TV-14 are the most common ratings.

A significant increase in content was observed after 2015, reflecting Netflix’s global expansion.

🚀 How to Run

Clone the repository

git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis


Install required libraries

pip install pandas numpy matplotlib seaborn


Open the notebook

jupyter notebook Netflix_data_analysis.ipynb


Run all cells sequentially.

📈 Future Enhancements

Perform sentiment analysis on movie descriptions.

Add dashboard visualization using Power BI or Tableau.

Integrate IMDb ratings for richer insights.
