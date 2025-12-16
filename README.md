# IPL Dataset Analysis & Visualization

This repository contains a Python-based data analysis and visualization script that explores historical **Indian Premier League (IPL)** match data.

The analysis focuses on extracting insights related to team performance, season trends, toss decisions, and individual player achievements using data visualization techniques.

--------------------------------------------------------------------------------------
## Project Files
```text
  /ipl-dataset-analysis
    │
    ├── ipl_dataset_analysis.py # Main analysis & visualization script
    ├── ipl_dataset.csv # IPL match dataset
    └── README.md # Project documentation
```
----------------------------------------------------------------------------------------

## Analysis Covered

The script answers the following key analytical questions:

### Total Wins by Each Team
- Visualizes the total number of matches won by each IPL team
- Helps identify historically dominant teams

### Matches Played Per IPL Season
- Shows how the number of matches varies across seasons
- Useful for understanding league expansion and scheduling patterns

### Impact of Toss Decision on Match Outcome
- Analyzes whether choosing to **bat or field after winning the toss** affects match results
- Uses grouped and stacked visualizations for comparison

### Top 10 Player of the Match Award Winners
- Identifies players with the highest impact performances
- Highlights consistency and match-winning contributions

---

## Visualization Techniques Used

- Bar plots
- Count plots
- Stacked bar charts
- Grouped aggregations

Libraries used for visualization:
- **Matplotlib**
- **Seaborn**

---

## Tech Stack

- **Python**
- **Pandas** – data manipulation & aggregation
- **Matplotlib** – base visualizations
- **Seaborn** – enhanced statistical plots

---

## How to Run the Script

```bash
# Install required libraries
pip install pandas matplotlib seaborn
```

OR

```bash
# Run the requirements file
pip install -r requirements.txt
```

Then

```bash
# Run the analysis file
python ipl_dataset_analysis.py
```
