# Netflix-Data-Analysis
Exploratory data analysis project on a  Netflix catalogue dataset. This project explores and analyzes the Netflix content catalogue to uncover trends and patterns across different dimensions using Python, pandas, and Plotly.
<hr>

🔗 | [Live Interactive Visualizations (GitHub Pages)](https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/)
<hr>

## ⊹ | Technology Used<br>
⋆ **Language**&nbsp;&nbsp;<br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)<br>
⋆ **IDE** <br>
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)<br>
⋆ **Libraries**
* Pandas : Data manipulation and analysis.
* Plotly : Interactive graphing library for data visualization.
* TextBlob : Simple NLP library for processing textual data, including sentiment analysis.<br>

## ⊹ | Dataset
⋆ **Source**: [Kaggle: Netflix Movies And TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download) <br>
⋆ **Entries**: ~8,800+ <br>
⋆ **Fields**: show id, type, title, director, cast, country, date added, release year, rating, duration, listed in, description

## ⊹ | Analytical Objectives<br>
⋆ Understand the distribution of content ratings throughout the Netflix catalogue<br>
⋆ Finding out the 5 most frequently featured directors on Netflix <br>
⋆ Finding out the 5 most frequently featured actors on Netflix <br>
⋆ Examine the distribution of content types over the years to identify trends in Netflix's content offerings by release year.<br>
⋆ Finding out the 5 most represented countries on Netflix <br>
⋆ Perform sentiment analysis on content descriptions to gain insights into the emotional tone of Netflix’s offerings.<br>

## ⊹ | Key Findings<br>
⁺ TV-MA content constitutes the largest share among all content ratings on Netflix. <br>
⁺ Rajiv Chilaka is the most frequently featured director on Netflix with a total content count of 22. <br>
⁺ Anupam Kher is the most frequently featured actor on Netflix with a content count of 43. <br>
⁺ From 2015 to 2020, there has been a significant increase in Movies available on Netflix. <br>
⁺ The United States leads in content contribution to Netflix compared to other countries. <br>
⁺ The sentiment analysis of descriptions shows that most content carries a positive tone, with the highest positivity observed in 2019.<br>

## ⊹ | How to Explore the Charts
The interactive charts are hosted via GitHub Pages. View them directly here: <br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/contenttype.html" target="_blank">Chart 1: Distribution of Content Ratings on Netflix</a> <br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/topdirectors.html" target="_blank">Chart 2: Top 5 Directors on Netflix</a> <br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/topactors.html" target="_blank">Chart 3: Top 5 Actors on Netflix</a> <br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/contenttrend.html" target="_blank">Chart 4: Trends in type of content featured on Netflix by year</a><br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/topcountries.html" target="_blank">Chart 5: Top 5 movie-producing Countries on Netflix</a><br>
✦ <a href="https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/sentiment.html" target="_blank">Chart 6: Sentiment Analysis of Content by Release Year</a> <br>
<br>
Or browse all charts from the **[Index Page](https://itsnehakv.github.io/Netflix-Catalogue-Data-Analysis/)**

## ⊹ | How to run
1. **Clone this repo**<br>
  ```bash
  git clone https://github.com/yourusername/your-repo-name.git
```

2. **Install dependencies**<br>
```bash
pip install -r requirements.txt
```
3. **Run the notebook**<br>
```bash
jupyter notebook Netflix Data Analysis.ipynb
