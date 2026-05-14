# NBA Game Outcome Analysis

DS 150 Capstone — Spring 2026

Analyzing whether home court advantage, rest days, and 
star player availability predict NBA game outcomes 
across 5 seasons (2021-22 to 2025-26).

## Findings
- Home teams win 55.3% vs 44.7% away (10.6 point gap)
- Back-to-back games win 44.7% vs 52.6% rested (7.9 point gap)  
- Wolves win 69.7% with Gobert vs 50.0% without (19.7 point swing)
- Mavericks compounding effect: 62.1% best case vs 28.6% worst case

## Stack
Python, Pandas, Matplotlib, nba_api

## Files
- nba_analysis.ipynb — main notebook
- data/ — raw and cleaned CSVs
- visualizations/ — final charts

## How to run
1. Clone repo
2. pip install nba_api pandas matplotlib  
3. Open nba_analysis.ipynb in VS Code or Jupyter
4. Run all cells top to bottom