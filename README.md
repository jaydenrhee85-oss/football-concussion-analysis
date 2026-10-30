# Football Concussion Risk Analysis
An independent research project by Braylon Oglesby that looks at which situations in football are linked to the highest concussion risk. It uses published NFL concussion data from 1996–2001 and 2002–2007 (Casson et al., 2010, *Sports Health*).
## Main finding
Passing plays have the most concussions in total. Per play, though, a kickoff is about 3.6 to 3.8 times as likely to cause a concussion as a passing play, and 3.4 to 5.1 times as likely as a running play. This was true in both time periods.
## Files
| File | What it is |
| --- | --- |
| `Untitled0_fixed_v2 (1).ipynb` | The full analysis: data cleaning, graphs, chi-square tests, rate ratios, correlation, and an interactive risk calculator |
| `annual_summary.csv` | Overall totals for each period (concussions, games, days missed) |
| `position_data.csv` | Concussions by player position |
| `play_type_data.csv` | Concussions by type of play |
| `activity_data.csv` | Concussions by what the player was doing |
| `play_risk_data.csv` | Concussions and number of plays run, used for risk per play |
## How to run it
1. Open the notebook in [Google Colab](https://colab.research.google.com/) (File → Upload notebook).
2. Upload the 5 CSV files using the folder icon on the left.
3. Click Runtime → Run all.
Tools used: Python, pandas, Matplotlib, SciPy, and ipywidgets.
## Data source
Casson, Ira R., et al. "Twelve Years of National Football League Concussion Data." *Sports Health*, vol. 2, no. 6, 2010, pp. 471–83, https://doi.org/10.1177/1941738110383963.
