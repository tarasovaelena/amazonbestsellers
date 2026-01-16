# What Makes an Amazon Bestseller? #
### Analyzing 13 years of Amazon’s Top 50 Bestselling Books (2009–2022) ###
This project analyzes Amazon’s Top 50 Bestselling Books from 2009 to 2022 to identify common patterns in pricing, user ratings, review volume, genre distribution, and book title structure.
The analysis focuses on **describing long-term trends among bestsellers**, rather than predicting success, and aims to provide insights into how bestselling books tend to be positioned in the market.

## Key Questions Explored ##
* Have Amazon bestselling books become more expensive over time?
* Do Fiction and Non-Fiction books differ in user ratings?
* Which genre attracts a higher volume of user reviews?
* Is there a relationship between book price and user ratings?
* What is the typical length of a bestseller title?
* What words and themes commonly appear in bestseller titles?

## Dataset ##
* **Source**: [Amazon Top 50 Bestselling Books Dataset](https://www.kaggle.com/datasets/chriskachmar/amazon-top-50-bestselling-books-2009-2022)
* **Scope**: Annual Top 50 bestsellers from 2009–2022
* **Size**: 700 books
* **Notes**:
    * The dataset includes only bestsellers (not all published books).
    * The Price field reflects the value provided in the dataset and does not distinguish between formats (e.g., ebook vs paperback).

## Tech Stack ## 
* **Language & IDE**: Python 3.12, VS Code, Jupyter Notebook
* **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Plotly, Pandasql, Circlify, Scikit-Learn, Collections, Regex, NLTK, WordCloud

## Analysis & Methods ##
* Cleaned and standardized the dataset using **Pandas and SQL-style queries** to resolve inconsistencies.
* Performed **exploratory data analysis (EDA)** to examine trends in pricing, ratings, reviews, and genre distribution over time.
* Built static and interactive visualizations to highlight long-term patterns.
* Applied **NLP techniques (TF-IDF) and K-means clustering** to explore common language patterns in bestseller titles.

## Results & Insights ##
* Average bestseller prices fluctuated over time, with a noticeable increase beginning around 2020.
* Fiction and Non-Fiction books showed **similar average user ratings**, with only minor differences between genres.
* Fiction titles accumulated a higher total number of reviews across most years, despite Non-Fiction titles appearing more frequently in the Top 50.
* Bestseller titles often include **subtitles, series information, or descriptive phrases**, resulting in an average title length of over eight words.
* Title clustering revealed **recurring themes and language patterns among bestselling books**, highlighting how successful titles are commonly structured rather than what causes success.

## Limitations ##
* The analysis is limited to **Top 50 bestsellers** and does not represent the broader book market.
* Findings are **descriptive**, not causal.
* Price alone cannot be used to infer revenue without sales volume data.
* Title language patterns reflect commonalities among bestsellers, not guarantees of success.

## Interactive Notebook ##
For a step-by-step walkthrough of the analysis and visualizations, explore the project notebook on [Deepnote](https://deepnote.com/workspace/Elenas-projects-7e7c61a3-d0dd-45aa-9dc9-646f4826a5f0/project/What-Amazon-bestseller-is-made-of-f53d8d57-7938-4dd4-b5ac-5544ab6e6fcb/notebook/d858a5d5acda4d87ac74892065650de4)
