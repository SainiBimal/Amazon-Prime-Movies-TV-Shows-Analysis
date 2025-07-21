## 🎞️ Amazon Prime Movies & TV Shows Analysis

This repository presents a comprehensive data analysis and visualization project of Amazon Prime's catalog of Movies and TV Shows using Python (Pandas, Seaborn, Matplotlib), with over 118,000+ records covering metadata like ratings, actors, directors, runtime, country of origin, and popularity scores.

-------------------------------------------

## 🌐 Overview

This project combines two datasets (titles.csv and credits.csv) into a unified data structure and performs:

Exploratory Data Analysis (EDA)

Aggregation by role (actor/director)

Country-wise and genre-wise breakdown

Correlation and distribution plots for popularity and ratings

------------------------------------------

## 🔹 Key Features & Insights


## 📊 Distribution Analysis

Movie vs Show Count: Movies dominate, but shows contribute significant viewership.

Release Year Trends: Peaks in production observed post-2010.

--------------------------------------------

## 🎓 Age Certification Analysis

Majority of titles fall under TV-MA, PG-13, and Not Rated

Pie chart visualization shows content skewed towards mature audiences


--------------------------------------------

## 👨‍🎨 Actor & Director Analysis

Top actors identified by TMDB popularity

Indian actors like Shah Rukh Khan, Rajinikanth, Amitabh Bachchan were among the top

Director filtering logic separates crew role as "DIRECTOR" for insights

-------------------------------------

## 📊 Rating Comparisons

Strong correlation (~0.6) between imdb_score and tmdb_score

Pair plots show visible linear trends between votes and popularity


--------------------------------------


## 📝 Dashboard Components (Jupyter Notebook)

Component

Description

Correlation Heatmap

Shows how strongly IMDb score, votes, TMDB score and popularity are linked

Pairplot

Scatter matrix for 6+ numeric fields with histograms

Pie Chart

Share of age certification labels

Bar Plot

Top 20 actors by TMDB popularity

Horizontal Line Plot

Alternative view of actor popularity


--------------------------------


## 📂 Files in This Repository

File

Description

Amazon.ipynb

Main notebook used for data analysis

titles.csv

Amazon Prime titles dataset

credits.csv

Amazon Prime cast & crew dataset

README.md

Project documentation


----------------------------------------


## 🚀 Technologies Used

Python (Pandas, NumPy): Data manipulation

Seaborn & Matplotlib: Data visualization

Google Colab: Environment for running the analysis

----------------------------------

## 💡 Summary & Future Scope

The data reveals Amazon Prime’s global content strategy, with U.S.-centric production and mature audience focus

Indian actors have high representation in global rankings

Strong correlation between IMDb & TMDB supports cross-platform reputation

---------------------------------


## 🌐 Future Enhancements:

Add genre-level breakdowns

Time series trendlines of new releases

NLP sentiment analysis of reviews (if available)

Include Power BI dashboard or Streamlit app


----------------------


## 🙌 Author

**BIMAL KUMAR SAINI**              
Data Analyst Intern                      
📧 bimalsaini333@gmail.com              
🔗 [LinkedIn][https://www.linkedin.com/in/bimalsaini333/] | [GitHub][https://github.com/SainiBimal]
