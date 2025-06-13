# Google Play Store Apps Exploratory Data Analysis (EDA)

This repository contains an in-depth Exploratory Data Analysis (EDA) of the Google Play Store Apps dataset. The analysis covers data cleaning, outlier handling, univariate, bivariate, and multivariate visualizations, as well as feature engineering ideas for further modeling.

## Dataset

The dataset contains information about over 2 million Android apps on the Google Play Store, including features such as:
- App name, category, and content rating
- Number of installs and ratings
- App size (in MB)
- Free/Paid status, price, and monetization details
- Developer info, website, and email
- Release date and more

## EDA Highlights

- **Data Cleaning:** Handled missing values, converted numeric columns, and standardized categorical data.
- **Outlier Detection & Removal:** Used the IQR method to remove extreme values from key numeric columns (e.g., Installs, Price).
- **Univariate Analysis:** Histograms and boxplots for main features like Rating, Installs, Size, and Price.
- **Bivariate/Multivariate Analysis:** 
  - Correlation heatmaps
  - Category-wise comparisons of free vs. paid apps
  - Relationship between price and installs
  - Outlier impact visualizations
- **Feature Engineering:** Suggestions for new useful features, such as "has_website", "has_email", app age, monetization type, and more.

## How to Use

1. Clone this repository or download the notebook and dataset.
2. Open the notebook (`Google_Playstore_Apps_EDA.ipynb`) in Jupyter or Kaggle.
3. Run the cells in order to reproduce the analysis and visualizations.
4. Use the feature engineering ideas as a starting point for your own machine learning models.

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
```

## Results & Insights

- Most apps are free and have low prices; only a few are high-priced outliers.
- Highly popular apps have millions of installs and ratings, but are outliers in the dataset.
- Strong correlation exists between different installs-related columns.
- App ratings are not strongly correlated with installs, size, or price.
- Outlier removal gives a clearer picture of true trends and distributions.

## License

This project is for educational and research purposes.

---

**Feel free to fork or use this EDA as a template for your own app analytics projects!**
