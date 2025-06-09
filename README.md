# 📊 Netflix Exploratory Data Analysis (EDA)

This project presents a comprehensive Exploratory Data Analysis (EDA) on a cleaned Netflix dataset using Python. The goal is to extract meaningful insights from the data through visual and statistical exploration.

---

## 📁 Dataset

The dataset (`netflix_cleaned.csv`) contains information about Netflix titles including:
- Title
- Type (Movie or TV Show)
- Director, Cast, Country
- Date added to Netflix
- Release year
- Duration
- Rating, Genre (Category)
- Description

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🔍 Exploratory Data Analysis Steps

1. **Data Loading & Cleaning**
   - Checked for missing values and data types
   - Explored unique values and distributions

2. **Univariate Analysis**
   - Count of movies vs TV shows
   - Top content-producing countries
   - Year-wise and month-wise content addition
   - Duration analysis for movies

3. **Bivariate & Multivariate Analysis**
   - Content type vs rating
   - Correlation heatmap for numerical features
   - Scatterplots, boxplots, and histograms

4. **Visualizations**
   - Histograms, bar plots, pairplots, heatmaps
   - Used `sns.pairplot()` and `sns.heatmap()` for deeper insights

5. **Insights & Summary**
   - Most content is movies
   - US dominates content production
   - Majority of content added between 2017–2021
   - Popular ratings: TV-MA, TV-14, and PG

---

## 📑 Project Deliverables

- `netflix_eda.ipynb` - Jupyter Notebook with code, plots, and observations
- `netflix_eda.pdf` - Clean PDF report summarizing the analysis
- (Optional) `netflix_cleaned.csv` - Source data used in this project

---

## 📌 Key Findings

- Netflix has a higher volume of movies than TV shows.
- The US is the leading contributor of Netflix content.
- A significant amount of content was added post-2016.
- The dataset reveals seasonal patterns in content release.
- Ratings like TV-MA and TV-14 are the most common.

---

## 📈 Sample Visualizations

![content type distribution](https://via.placeholder.com/600x200?text=Bar+Chart+Placeholder)
![duration distribution](https://via.placeholder.com/600x200?text=Histogram+Placeholder)

(*Replace with actual images or Colab screenshots*)

---

## ✅ Conclusion

This EDA gives valuable insights into Netflix’s content strategy and trends over the years. The analysis can help identify viewer preferences, content addition patterns, and popular formats.

---

## 🚀 How to Run

1. Clone this repo or download the notebook.
2. Open `netflix_eda.ipynb` in [Google Colab](https://colab.research.google.com).
3. Upload `netflix_cleaned.csv` when prompted.
4. Run the cells to explore!

---

## 🧑‍💻 Author

**Your Name**  
GitHub: [@your-username](https://github.com/your-username)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
