#  Netflix Movie Data Analysis — Python | EDA & Visualization

This project explores a dataset of 9,800+ Netflix movies to uncover trends in genres, popularity, ratings, and release years. The goal is to apply Exploratory Data Analysis (EDA) techniques to help understand content patterns and generate business insights that can support data-driven decisions in a media or entertainment environment.

🔍 Project Objectives

Based on the dataset provided, the analysis focuses on answering key business questions:
✔ What is the most frequent movie genre on Netflix?
✔ Which movie has the highest vote average?
✔ Which movie is the most popular, and what is its genre?
✔ Which movie has the lowest popularity score?
✔ Which year has the highest number of movies released?

These questions simulate real industry scenarios where analytics teams help optimize content strategy and customer engagement.


Netflix movie data analysis pro…

🛠 Technologies & Libraries Used

Python

Pandas, NumPy (data cleaning, preprocessing, transformation)

Matplotlib, Seaborn (data visualization)

Jupyter Notebook / Google Colab

📁 Dataset Overview

Contains 9,837 movie entries

Includes attributes for genres, popularity scores, vote averages, release dates, and more

Required cleaning steps:

Handling missing values

Removing unnecessary columns

Converting release dates to datetime format

Extracting the release year

Splitting multi-genre fields

Categorizing vote averages

📈 Key Insights from the Analysis
🎬 1. Most Frequent Movie Genre

Drama emerges as the most released genre on Netflix, dominating overall content distribution.

⭐ 2. Highest Vote Average

Identified the top-rated movie using the vote_average metric.

🚀 3. Most Popular Movie

Spider-Man: No Way Home is the most popular movie with significantly high popularity scores.
Genre: Action / Adventure / Sci-Fi

🐌 4. Lowest Popularity Movie

Titles from niche genres such as Music, Drama, History, War, Sci-Fi appear among the lowest-popularity list.

📅 5. Year with the Most Releases

2020 recorded the highest number of movie releases in the dataset.


Netflix movie data analysis pro…

📊 Visualizations

The analysis includes:

Genre distribution bar charts

Popularity trend plots

Vote average distributions

Year-wise release count charts

Multi-variable comparisons for deeper insights

These visualizations help better understand content trends and support storytelling with data.

🧹 Data Cleaning & Feature Engineering

Key preprocessing steps include:

Dropping duplicate and irrelevant columns

Extracting release_year

Splitting genre into lists

Creating new features such as:

Vote_Average_Category (popular, average, below avg, not popular)

🧠 Outcome

This project demonstrates your ability to:

Perform end-to-end EDA

Clean, transform, and analyze large datasets

Build meaningful visualizations

Derive actionable insights

Apply analytics thinking to real business questions

📌 How to Run
pip install pandas numpy matplotlib seaborn
python netflix_analysis.ipynb
