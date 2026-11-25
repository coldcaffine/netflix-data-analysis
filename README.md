# Netflix Data Analysis

Data analysis internship project for **Auspify Technologies** (Data Analysis Using Python), done with Python, Pandas, Matplotlib and Seaborn on the Netflix Movies and TV Shows dataset.

**Author:** Aditi Dharme

## Tasks Completed

| Task | Notebook | What I did |
|------|----------|------------|
| 1. Data Cleaning & Preparation | `task1_cleaning.ipynb` | Removed duplicates, handled missing values, standardized Type, Country and Rating, exported `netflix_cleaned.csv` |
| 2. Content Type Analysis | `task2_content_type.ipynb` | Counted Movies vs TV Shows and made bar and pie charts |
| 3. Country-Wise Analysis | `task3_country_analysis.ipynb` | Split multi-country entries, ranked the top 10 content-producing countries |
| 4. Trend Analysis by Release Year | `task4_release_year_trends.ipynb` | Plotted yearly releases, found the peak and growth/decline patterns |

## Key Findings

- **Content type:** Movies make up about 69.7% of the catalog and TV Shows about 30.3%.
- **Countries:** The United States leads with 3,684 titles, followed by India (1,046) and the United Kingdom (805).
- **Trend:** Releases were low until about 2010, grew quickly after 2013, peaked around 2018 and then dropped. The dataset only runs to 2021, so the last years are incomplete.

## Screenshots

![Movies vs TV Shows](images/task2_pie.png)
![Top 10 Countries](images/task3_countries.png)
![Release Year Trend](images/task4_trend.png)

## Tools Used

Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook, VS Code

## How to Run

1. Clone this repo.
2. Install the libraries: `pip install pandas matplotlib seaborn ipykernel`
3. Open any notebook in VS Code or Jupyter and run all cells. Task 1 creates `netflix_cleaned.csv`, which the other tasks use. Update the file path in the `read_csv` line if your folder is different.

#Auspify #AuspifyTechnologies #AuspifyInternship #AuspifyProjects
