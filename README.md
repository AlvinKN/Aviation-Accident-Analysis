# Aviation Accident Analysis

## Summary
Phase 1 project analyzing U.S. aviation accidents (1948–2022) to improve safety by identifying high-risk states, weather conditions, and trends.

## Data Science Steps
1. Loaded and explored data from `Aviation_Accidents.csv` and `US_State_Abbreviations.csv`.
2. Cleaned and merged datasets, saved as `cleaned_aviation_data.csv`.
3. Analyzed for findings (e.g., California leads, 1982 peak, IMC fatalities) and recommendations.
4. Visualized in Jupyter Notebook (exported PNGs) and Tableau (dashboard).

## Repository Structure
- `data/`: Raw and cleaned CSV files.
  - `US_State_Abbreviations.csv`: State lookup table.
  - `Aviation_Accidents.csv`: Original accident data.
  - `cleaned_aviation_data.csv`: Processed data for analysis.
- `notebooks/`: Jupyter Notebook.
  - `project_notebook.ipynb`: Full project code and documentation.
- `images/`: Exported visualizations.
  - `top_states.png`: Top 5 states by accident count.
  - `fatal_by_year.png`: Fatal accidents over time.
  - `weather_impact.png`: Fatalities by weather condition.
- `tableau/`: Tableau dashboard.
  - `Aviation_Dashboard.twb`: Interactive dashboard file.

## Tableau Dashboard
- [Link to Tableau Public; https://public.tableau.com/views/Aviation-AnalysisDashboard/Aviation-AnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link] 

## Usage
- Open `notebooks/project_notebook.ipynb` in Jupyter to run the analysis.
- Use `data/cleaned_aviation_data.csv` in Tableau to recreate the dashboard.
