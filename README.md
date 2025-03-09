# Formula-1-Monaco-Grand-Prix-Analysis
To analyze Formula 1 race data from the Monaco Grand Prix (2022–2024) using Python and the fastf1 library. The project focused on extracting actionable insights such as fastest lap times, average race pace, and driver-specific performance metrics. The goal was to demonstrate data manipulation, visualization, and domain-specific analytical skills.

## Features
- **Fastest Lap Analysis**: Identify drivers with the fastest single lap times each year.
- **Average Race Pace**: Calculate consistent lap times (excluding pit stops) for drivers.
- **Driver Comparison**: Track performance trends for Verstappen, Norris, and Leclerc.
- **Visualizations**: Generate plots to compare lap times and year-over-year performance.

  ## Tools & Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- FastF1 (F1 data API)

  ## Dataset
- **Source**: Official F1 timing data via `fastf1` (cached locally for efficiency).
- **Years**: 2022, 2023, 2024.
- **Tracks**: Monaco Circuit.

  ## Setup
1. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn fastf1
   import fastf1
   fastf1.Cache.enable_cache('path/to/cache/directory')

## Code Structure
- **Data Fetching**: Load race sessions and cache data.
- **Fastest Lap Extraction**: Use laps.pick_fastest() to identify top laps.
- **Average Pace Calculation**: Filter out pit laps and compute mean lap times.
- **Driver Analysis**: Compare Verstappen, Norris, and Leclerc using grouped data.
- **Visualization**: Plot trends in lap times and performance metrics.

  
