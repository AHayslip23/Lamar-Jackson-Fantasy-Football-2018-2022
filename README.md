# Lamar Jackson Fantasy Football 2018–2022

A game-by-game analysis of Lamar Jackson's fantasy football production from 2018 to 2022. It explores his passing and rushing stats and builds a multiple regression model to predict his fantasy points.

## Repository Contents

| File | Description |
|---|---|
| `Lamar Jackson Fantasy Football Analysis.ipynb` | Full analysis: season-by-season EDA, correlations and regression models (74 charts) |

## Commit History

### `80227f6`: Upload of the analysis notebook (2025-12-14)
- **Season-by-season EDA:**
  - 2018 and 2022 have small sample sizes
  - his 2019 MVP season stands out: 22–32 pass attempts per game, a very high completion percentage, about 80 rushing yards per game, and close to 30 fantasy points per game
- **Correlations with completion percentage and fantasy points:**
  - passing yards vs. completion percentage: −6%, no linear relationship
  - completions vs. completion percentage: 1%, no relationship
  - completions vs. fantasy points: 25.2%
  - passing yards vs. fantasy points: 32.3%, the strongest single-stat relationship
- **Multiple regression:**
  - built a model that predicts Jackson's fantasy points per game
  - predicted specific games, e.g. 16.50, 18.58 and 30.84 points
  - the model's fit was 96.2%

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook
