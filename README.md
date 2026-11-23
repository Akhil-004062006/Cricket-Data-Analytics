# Cricket Data Analytics

## Project Overview

This project focuses on analyzing T20 cricket match data using Python. It processes cricket datasets stored in CSV and JSON formats to identify player performance, team statistics, batting records and bowling performance.

The project uses data analysis and visualization techniques to generate meaningful insights from cricket match data.

## Features

- **Data Loading:** Reads cricket datasets from CSV and JSON files.
- **Data Cleaning:** Removes duplicate records, handles missing numeric values and prepares data for analysis.
- **Batting Analysis:** Calculates total runs, strike rate, average runs, fours and sixes.
- **Player Performance:** Identifies top run scorers and players with the best strike rates.
- **Consistency Analysis:** Calculates a consistency index using the standard deviation of player runs.
- **Power Factor:** Calculates a batting power measure using the number of fours and sixes.
- **Team Analysis:** Compares team batting performance and total runs.
- **Match Analysis:** Analyzes team wins, matches played at different grounds and matches by year.
- **Bowling Analysis:** Calculates total wickets and bowling economy when compatible bowling data is available.
- **Data Visualization:** Generates bar charts, line graphs and heatmaps.
- **Result Export:** Saves analysis results as CSV files and generates a text report.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- JSON

## Project Structure

```text
Cricket-Performance-Analysis/
│
├── datasets/
│   ├── dim_match_summary.csv
│   ├── fact_bating_summary.csv
│   ├── fact_bowling_summary.csv
│   ├── dim_players.csv
│   └── other_data.json
│
├── output/
│   ├── batting_analysis.csv
│   ├── team_batting_analysis.csv
│   ├── team_wins.csv
│   ├── bowling_analysis.csv
│   └── cricket_analysis_report.txt
│
├── cricket_analysis.ipynb
│
└── README.md
```

*The output folder and files are generated when the notebook runs. The actual datasets may vary.*

## Dataset Information

The project supports CSV and JSON datasets.

### 1. Match Summary Dataset

Contains match-level information such as:

- Team 1
- Team 2
- Winning team
- Winning margin
- Ground
- Match date
- Match ID

### 2. Batting Summary Dataset

Contains batting information such as:

- Batsman name
- Runs scored
- Balls faced
- Fours
- Sixes
- Strike rate
- Batting position
- Match ID

### 3. Bowling Summary Dataset

When available, the bowling dataset is used to analyze:

- Bowler name
- Wickets
- Runs conceded
- Overs
- Maidens
- Match ID

The notebook identifies compatible datasets using their column names.

## Output

The project generates the following results:

- Top 10 run scorers.
- Top 10 players by strike rate.
- Players with the most sixes.
- Team batting performance comparison.
- Team win statistics.
- Matches by ground and year.
- Top wicket takers.
- Bowling economy comparison.
- Player performance heatmap.

Analysis results are saved in the `output` directory.

## Conclusion

This project demonstrates how Python-based data analysis can be used to explore cricket statistics, compare player performances and understand team results. It combines data preprocessing, statistical calculations and visualization to present cricket performance insights in an understandable format.

---

**Project Category:** Data Analysis

**Programming Language:** Python
