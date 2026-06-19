# Netflix Data Exploration and Visualization

## Project Overview

Netflix is one of the world's leading streaming platforms with over 220 million subscribers globally. This project analyzes Netflix's content library to identify patterns in content production, release trends, country-wise content distribution, and audience preferences.

The objective is to generate business insights that can help Netflix decide:
- What type of content to produce
- Which countries to focus on
- How to expand its content strategy globally

---

## Business Problem

Analyze Netflix's content catalog and generate data-driven insights to help Netflix:

- Decide which type of movies and TV shows to produce
- Understand content preferences across countries
- Identify growth opportunities in international markets
- Optimize content acquisition and production strategies

---

## Dataset Information

Source: Netflix Movies and TV Shows Dataset

Features:

| Column | Description |
|----------|-------------|
| show_id | Unique identifier |
| type | Movie or TV Show |
| title | Title of content |
| director | Director name |
| cast | Actors involved |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Release year |
| rating | Content rating |
| duration | Movie duration / TV seasons |
| listed_in | Genre |
| description | Content summary |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Preprocessing

Performed the following preprocessing steps:

- Missing value handling
- Duplicate removal
- Date conversion
- Data type correction
- Unnesting:
  - Director
  - Cast
  - Country
  - Genre

---

## Exploratory Data Analysis

### Univariate Analysis

- Movies vs TV Shows
- Release Year Distribution
- Content Ratings
- Duration Analysis
- Genre Distribution

### Bivariate Analysis

- Content Type vs Country
- Release Year vs Content Type
- Rating vs Content Type
- Country vs Genre

### Trend Analysis

- Growth of Netflix content over time
- Movie production trends
- TV Show production trends
- Country-wise content contribution

---

## Key Insights

### Content Type

- Movies account for the majority of Netflix content.
- TV Shows have grown significantly in recent years.

### Country Analysis

- United States contributes the highest amount of content.
- India is among the top content-producing countries.

### Release Trends

- Most content was added after 2015.
- Netflix aggressively expanded its catalog between 2016–2020.

### Genre Analysis

- Drama and International Movies dominate the platform.
- International content has experienced rapid growth.

### Ratings Analysis

- TV-MA and TV-14 are the most common ratings.
- Netflix primarily targets mature and young-adult audiences.

---

## Business Recommendations

### 1. Increase International Content

Invest more in high-performing regions such as:
- India
- South Korea
- Japan

### 2. Expand TV Show Production

TV Shows demonstrate strong growth and encourage subscriber retention.

### 3. Focus on Popular Genres

Prioritize:
- Drama
- Comedy
- International Content
- Crime & Thriller

### 4. Regional Content Strategy

Develop country-specific content based on local audience preferences.

### 5. Continue Investment in Mature Audience Segments

TV-MA and TV-14 content show strong demand globally.

---

## Project Structure

```
Netflix-Data-Exploration/
│
├── Dataset/
│   └── netflix.csv
│
├── Notebook/
│   └── Netflix_EDA.ipynb
│
├── Images/
│   ├── Content_Distribution.png
│   ├── Release_Trend.png
│   └── Country_Analysis.png
│
└── README.md
```

---

## Results

The analysis provides actionable recommendations that can help Netflix optimize content production, improve audience engagement, and expand into high-growth international markets.

---

## Author

Vaishnavi Kothur
