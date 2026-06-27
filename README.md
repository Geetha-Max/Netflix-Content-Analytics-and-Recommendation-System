# Netflix Content Analytics and Recommendation System

## Project Overview

This project analyzes Netflix's content library using Data Analytics techniques and builds a Content-Based Recommendation System using Machine Learning concepts.

The project includes data cleaning, exploratory data analysis (EDA), data visualization, and an AI-powered recommendation engine that suggests similar titles based on content descriptions and genres.

---

## Objectives

- Analyze Netflix content trends and patterns.
- Perform data cleaning and preprocessing.
- Visualize key insights from the dataset.
- Build a recommendation system for similar content.
- Apply concepts learned during a Data Analytics internship.

---

## Dataset Information

Dataset: Netflix Titles Dataset

- Total Records: 8,807
- Total Features: 12

### Features

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / VS Code

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure and data types
- Handled missing values
- Removed records with missing date information
- Filled missing categorical values with appropriate labels
- Checked for duplicate records
- Converted date_added to datetime format
- Created additional features such as year_added and month_added

---

## Exploratory Data Analysis

The following analyses were performed:

### 1. Movies vs TV Shows
- Movies account for approximately 69.6% of Netflix content.
- TV Shows account for approximately 30.4%.

### 2. Top Content-Producing Countries
- United States is the largest contributor.
- India is the second-largest contributor.

### 3. Content Growth Analysis
- Significant growth observed after 2015.
- Peak content additions occurred in 2019.

### 4. Genre Analysis
- Drama-based content is the most common category.
- International content has a strong presence.

### 5. Rating Analysis
- TV-MA and TV-14 dominate the platform.
- Netflix primarily targets mature and teenage audiences.

### 6. Release Year Analysis
- Most content was released after 2015.
- The platform contains both modern and classic titles.

### 7. Director Analysis
- Content is distributed across a diverse set of directors.
- No single director dominates the platform.

---

## Recommendation System

A Content-Based Recommendation System was developed using:

### TF-IDF Vectorization
Converts text data into numerical feature vectors.

### Cosine Similarity
Measures similarity between Netflix titles based on:

- Genre
- Description

### Example

Input:

```python
recommend("Narcos")
```

Output:

```text
Narcos: Mexico
El Chapo
El Cartel 2
Ganglands
Miss Dynamite
```

---

## Key Insights

- Movies dominate Netflix's content library.
- The United States contributes the highest number of titles.
- Netflix experienced rapid content expansion between 2015 and 2019.
- Drama and International Movies are among the most popular genres.
- Mature audience content forms a significant portion of the catalog.
- Recommendation systems can effectively suggest similar content using text analysis.

---

## Future Enhancements

- Deploy the recommendation system as a web application.
- Add user-based recommendation features.
- Integrate sentiment analysis on content descriptions.
- Use advanced NLP models for improved recommendations.

---

## Project Structure

```text
Netflix-Content-Analytics-and-Recommendation-System
│
├── netflix_titles.csv
├── netflix_analysis.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Author

**Geetha K**

Third-Year Information Technology Student

Project developed as part of Data Analytics Internship Learning.
