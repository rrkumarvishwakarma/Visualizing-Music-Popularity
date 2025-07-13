# Spotify Data Analysis

This project performs exploratory data analysis, visualization, and basic statistical computations on a Spotify dataset. It demonstrates various data analysis techniques using Python libraries like pandas, matplotlib, seaborn, and scipy.

## Features

- Dataset overview: structure, summary statistics, and sample records  
- Visualizations:
  - Pair plots
  - Histograms
  - Line plots (Popularity over time)
  - Pie chart (Popularity by genre)
  - Bar chart (Top artists by popularity)
  - Correlation heatmap
  - Box plots for duration
- Descriptive statistics:
  - Central tendency (mean, median, mode)
  - Spread (range, IQR, standard deviation, variance)
  - Distribution shape (skewness and kurtosis)
- Group-wise analysis:
  - Popularity by genre and key
  - Mean comparison using bar plots
- Probability-based insights:
  - Probability of popularity exceeding a threshold
  - Probability of duration increasing over time

## File Structure

- `code.py` – Main analysis and visualization script  
- `Spotify.csv` – Input dataset (not included, place it in the same directory)

## Getting Started

1. **Install dependencies**

   Make sure you have Python 3 installed. Then run:

   ```
   pip install pandas matplotlib seaborn scipy
   ```

2. **Place your dataset**

   Ensure that your `Spotify.csv` file is in the same directory as `code.py`.

3. **Run the code**

   ```
   python code.py
   ```

   The script will generate various visualizations and print statistics to the console.

## Requirements

- Python 3.6+
- pandas
- matplotlib
- seaborn
- scipy
- numpy

## Notes

- Make sure the dataset contains the required columns like:
  `track_popularity`, `playlist_genre`, `track_album_release_date`, `duration_ms`, etc.
- You can modify the path in `pd.read_csv()` if your CSV file is in a different location.

## Acknowledgements

- Dataset source: Spotify / Kaggle  
- Libraries used: pandas, matplotlib, seaborn, scipy, numpy
