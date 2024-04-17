# Bundesliga Football Match Analysis Using PySpark

## Project Description

This project focuses on the processing and analysis of Bundesliga football match data from 2000 to 2015 using Apache Spark. The Jupyter notebook employed in this project executes several key operations: data loading, cleaning, transformation, and detailed statistical analysis, leading up to the ranking and presentation of team performances over the seasons.

## Overview of Notebook Operations

### Loading Required Libraries and Data
- **Installation of PySpark**: Set up the PySpark environment necessary for the data processing.
- **Initialization of Spark Session**: Start a session to enable data manipulation and analysis.
- **Data Loading**: Load the dataset from a CSV file containing detailed records of football matches.

### Data Preprocessing
- **Renaming Columns**: Improve clarity, e.g., renaming `FTHG` to `HomeTeamGoals`.
- **Dropping Unused Columns**: Remove columns like `FTHG`, `FTAG`, and `FTR` that are no longer necessary after initial transformations.
- **Creating Binary Columns**: New columns such as `HomeTeamWin`, `AwayTeamWin`, and `GameTie` to represent match outcomes in binary form.

### Data Analysis
- **Data Filtering**: Focus the analysis on Bundesliga matches between the years 2000 and 2015.
- **Data Aggregation**: Compute totals of wins, losses, ties, and goals for each team, considering both home and away statistics.
- **Merging Statistics**: Combine home and away data to create a complete statistical overview per team per season.
- **Calculating Additional Metrics**: Derive metrics like goal differentials and win percentages.
- **Ranking Teams**: Apply ranking to teams based on performance metrics for each season.

### Final Data Presentation
- **Top-ranked Teams**: Filter and display the team with the highest performance ranking per season.

## Contributing

Interested in contributing? Great! Here’s how you can help:

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/YourAmazingFeature).
3. Commit your changes (git commit -am 'Add some YourAmazingFeature').
4. Push to the branch (git push origin feature/YourAmazingFeature).
5. Open a Pull Request.
