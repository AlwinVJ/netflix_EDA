# Netflix Exploratory Data Analysis

## Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset obtained from Kaggle. The primary objective is to understand the composition of Netflix's content library by analyzing content distribution, genre popularity, temporal growth, geographical distribution, and relationships among key variables.

The project follows a structured EDA workflow consisting of data cleaning, univariate analysis, bivariate analysis, and multivariate analysis. The findings provide business insights into Netflix's content acquisition strategy, audience segmentation, and global expansion.

---

## Dataset Information

**Dataset Name:** Netflix Movies and TV Shows

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/rohitgrewal/netflix-data

### Dataset Description

The dataset contains information about movies and TV shows available on Netflix, including:

- Content Type
- Title
- Director
- Cast
- Country
- Release Date
- Content Rating
- Duration
- Genre
- Description

---

## Project Objectives

The project aims to answer the following business questions:

1. What is the distribution of Movies versus TV Shows?
2. Which genres are most prevalent in Netflix's catalog?
3. How has Netflix's content library grown over time?
4. Which countries contribute the most content?
5. How do content ratings vary across genres?
6. Are certain genres concentrated in specific countries?
7. Which genres have increased or decreased over time?

---

## Project Structure

```
Netflix_EDA/
│
├── data/
│   ├── raw/
│   │   └── netflix_titles.csv
│   │
│   └── processed/
│       └── netflix_cleaned.csv
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Data_Preprocessing.ipynb
│   ├── 03_Univariate_EDA.ipynb
│   ├── 04_Bivariate_EDA.ipynb
│   └── 05_Multivariate_EDA.ipynb
│
├── reports/
│   ├── Final_EDA_Report.docx
│   ├── Univariate_EDA.pdf
│   ├── Bivariate_EDA.pdf
│   └── Multivariate_EDA.pdf
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Python Libraries

```python
pandas
numpy
matplotlib
seaborn
jupyter
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Data Preprocessing

The preprocessing stage involved preparing the dataset for analysis through the following steps:

- Loaded the dataset into Pandas.
- Inspected data types and dataset structure.
- Converted the `Release_Date` column into datetime format.
- Extracted the release year for temporal analysis.
- Verified missing values.
- Checked duplicate records.
- Processed multi-valued categorical columns such as Genre and Country.
- Created cleaned datasets for analysis.

---

## Exploratory Data Analysis

### Univariate Analysis

The following analyses were performed:

- Movies vs TV Shows Distribution
- Genre Distribution
- Content Growth by Release Year
- Country-wise Content Distribution

### Bivariate Analysis

The following relationships were explored:

- Genre vs Content Rating
- Genre vs Country

Heatmaps and percentage distributions were used to identify relationships between variables.

### Multivariate Analysis

The multivariate analysis examined:

- Genre Trends Across Release Years
- Growth of Top Genres
- Temporal Changes in Netflix's Content Portfolio

Heatmaps and trend charts were used to visualize genre evolution over time.

---

## Key Findings

### Content Distribution

- Movies account for approximately 69% of Netflix's catalog.
- TV Shows account for approximately 31%.

### Most Common Genres

- International Movies
- Dramas
- Comedies
- International TV Shows

### Content Growth

- Significant growth began in 2016.
- The highest content availability occurred between 2018 and 2020.
- International Movies consistently remained the dominant genre.

### Country Distribution

The largest contributors include:

- United States
- India
- United Kingdom
- Canada
- France

### Genre and Rating

- TV-MA and TV-14 dominate the majority of Netflix genres.
- Children's content primarily falls under G, PG, TV-Y, and TV-Y7 ratings.

### Genre Trends

- International Movies experienced the greatest growth.
- Dramas and Comedies showed consistent long-term expansion.
- International TV Shows grew rapidly after 2016.
- Netflix diversified its catalog across multiple genres simultaneously.

---

## Business Insights

The analysis indicates that Netflix follows a globally diversified content acquisition strategy.

Key observations include:

- Strong investment in international productions.
- Balanced growth across multiple genres.
- Expansion of serialized television content.
- Effective audience segmentation through content ratings.
- Wide geographical distribution of content production.

---

## Repository Contents

- Cleaned Dataset
- Data Cleaning Notebook
- Univariate EDA Notebook
- Bivariate EDA Notebook
- Multivariate EDA Notebook
- Final EDA Report
- Visualizations
- Requirements File

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/netflix-eda.git
```

### Navigate to the Project

```bash
cd netflix-eda
```

### Create a Virtual Environment

Using Conda:

```bash
conda create -n netflix_eda python=3.12
conda activate netflix_eda
```

Or using venv:

```bash
python -m venv venv
```

Activate the environment.

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in the following order:

1. Data Cleaning
2. Data Preprocessing
3. Univariate EDA
4. Bivariate EDA
5. Multivariate EDA

---

## Future Improvements

Potential extensions of this project include:

- Interactive Dashboard using Tableau or Power BI
- Predictive Analytics
- Recommendation System Development
- Genre Classification Models
- Sentiment Analysis using Movie Descriptions
- Machine Learning-based Content Popularity Prediction

---

## Author

**Alwin V J**

Artificial Intelligence and Machine Learning Enthusiast

---

## License

This project is intended for educational and portfolio purposes only.

The dataset belongs to its original creators and is available through Kaggle.