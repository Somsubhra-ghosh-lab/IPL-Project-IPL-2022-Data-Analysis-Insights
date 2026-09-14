# IPL 2022 Data Analysis & Insights

An exploratory data analysis (EDA) project on IPL 2022 match data using
Python. The project explores match outcomes, team performance, batting
performance, bowling performance, toss decisions, and other match-level
statistics through data analysis and visualization.

## 📌 Project Overview

This project analyzes the IPL 2022 dataset containing **74 matches and
20 columns**. The analysis is performed using Python and focuses on
understanding patterns and insights from match and player statistics.

The notebook covers:

-   Dataset inspection and structure
-   Data types and basic information
-   Missing-value analysis
-   Team-wise match-winning analysis
-   Top run-scorer analysis
-   Bowling performance analysis
-   Match outcome analysis
-   Data visualization using charts

## 🛠️ Technologies Used

-   **Python**
-   **Pandas** --- data loading, cleaning, manipulation, and analysis
-   **NumPy** --- numerical operations
-   **Matplotlib** --- data visualization
-   **Seaborn** --- statistical visualization
-   **Jupyter Notebook** --- development and analysis environment

## 📂 Dataset

The dataset contains **74 IPL 2022 matches** with **20 columns**
describing match-level information.

Important columns include:

-   `match_id`
-   `date`
-   `venue`
-   `team1`
-   `team2`
-   `stage`
-   `toss_winner`
-   `toss_decision`
-   `first_ings_score`
-   `first_ings_wkts`
-   `second_ings_score`
-   `second_ings_wkts`
-   `match_winner`
-   `won_by`
-   `margin`
-   `player_of_the_match`
-   `top_scorer`
-   `highscore`
-   `best_bowling`
-   `best_bowling_figure`

The notebook's missing-value check shows **0 null values across all
columns**.

## 🔍 Analysis Performed

### 1. Basic Data Exploration

The project begins by loading the IPL dataset and examining:

-   Number of rows and columns
-   Column names
-   Data types
-   Dataset structure
-   Missing values
-   Sample records

### 2. Team Performance

The analysis investigates which teams won the most matches during the
IPL 2022 season.

### 3. Batting Analysis

The project examines top scorers and high individual scores recorded in
the matches.

The notebook identifies **Jos Buttler** as the leading scorer in the
analyzed data, with **651 runs**, followed by **Quinton de Kock** with
**377 runs**.

### 4. Bowling Analysis

Bowling performances are analyzed using the best bowling information
recorded for each match.

Examples of leading bowlers in the notebook's analysis include:

-   Yuzvendra Chahal
-   Kuldeep Yadav
-   Rashid Khan
-   Jasprit Bumrah
-   Avesh Khan

### 5. Match & Toss Analysis

The dataset also contains information about:

-   Toss winner
-   Toss decision (`Bat` / `Field`)
-   First-innings score
-   Second-innings score
-   Wickets lost
-   Winning margin
-   Match stage

These fields can be used to understand match-level patterns and
outcomes.

## 📊 Visualizations

The notebook uses **Matplotlib** and **Seaborn** to create
visualizations for the analysis, including bar charts for team and
player performance.

## 📁 Project Structure

``` text
IPL-2022-Data-Analysis/
│
├── IPL_project.ipynb
├── IPL.csv
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

``` bash
git clone <your-repository-url>
cd IPL-2022-Data-Analysis
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Start Jupyter Notebook

``` bash
jupyter notebook
```

Open `IPL_project.ipynb` and run the cells.

## 🎯 Key Skills Demonstrated

This project demonstrates practical experience with:

-   Exploratory Data Analysis (EDA)
-   DataFrame operations with Pandas
-   Numerical analysis with NumPy
-   Data visualization
-   Categorical data analysis
-   Sports data analytics
-   Extracting insights from structured datasets
-   Presenting analytical findings visually

## 📌 Future Improvements

The project can be extended by adding:

-   Interactive dashboards using **Power BI**, **Tableau**, or
    **Plotly**
-   More detailed player-level performance analysis
-   Team win-percentage analysis
-   Toss decision vs. match-result analysis
-   Venue-wise performance analysis
-   Correlation analysis between innings scores and match outcomes
-   Predictive modeling for match outcomes
-   More advanced statistical analysis

## 👨‍💻 Author

**Somsubhra Ghosh**

------------------------------------------------------------------------

⭐ If you found this project useful, consider giving the repository a
star!
