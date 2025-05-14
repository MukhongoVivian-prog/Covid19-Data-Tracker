# Covid 19 Data Tracker

## Project Overview

This project performs an exploratory data analysis (EDA) of COVID-19 data, focusing on trends and patterns across selected [continents/countries]. The analysis includes visualizing key metrics such as total cases, total deaths, daily new cases, vaccination progress, and examining correlations between numerical features. A Choropleth map is also generated to visualize the geographical distribution of total cases on the latest date.

## Data Source

The data used in this analysis is obtained from https://www.kaggle.com/datasets.

## Technologies Used

*   Python
*   Pandas
*   Matplotlib
*   Seaborn
*   Plotly Express
*   Google Colab / Jupyter Notebooks

## Setup and Installation

1.  **Clone the repository:**
   To clone this repository use git clone https://github.com/MukhongoVivian-prog/Covid19-Data-Tracker
2.  **Navigate to the project directory:**
   cd Covid19-Data-Tracker
3.  **Install necessary libraries:**
    If you are using a virtual environment (recommended):
    pip install pandas matplotlib seaborn plotly openpyxl # openpyxl is needed for read_excel
    If you are running in Google Colab, most of these are pre-installed. You might need to install `plotly`:
## Usage

1.  **Open the notebook:** Open the Jupyter Notebook file (`Covid19 Tracker.ipynb`) in your preferred environment (Google Colab, Jupyter Lab, Jupyter Notebook).
2.  **Run the cells:** Execute the notebook cells sequentially to perform the data loading, cleaning, analysis, and visualization steps.
3.  **Explore the visualizations:** Review the generated plots to understand the trends and patterns in the COVID-19 data for the selected [continents].

## Project Structure

*   `Covid19 Tracker.ipynb`: The main Jupyter Notebook containing the code for the analysis and visualizations.
*   `covid.csv`: The raw COVID-19 data file used in the analysis. (Update the file name if it's different or if you download it programmatically).
*   `README.md`: This file.

## Key Features

*   Data loading and initial inspection.
*   Handling missing data.
*   Time-series analysis of cases and deaths.
*   Calculation of daily new cases and death rates.
*   Comparison of vaccination progress.
*   Correlation analysis using a heatmap.
*   Choropleth map visualization of total cases by continent.

## Insights

Based on the analysis, some key insights include:

*   [Insight 1 - e.g., Total cases trends across continents]
*   [Insight 2 - e.g., Comparison of death trends]
*   [Insight 3 - e.g., Observed patterns in daily new cases]
*   [Insight 4 - e.g., Differences in vaccination rollout speed]
*   [Insight 5 - e.g., Percentage of population vaccinated comparison]

*Refer to the notebook for the specific insights derived from the data.*

## Anomalies and Observations

Potential anomalies and interesting patterns identified during the analysis include:

*   [Anomaly/Observation 1 - ., Data reporting discrepancies]
*   [Anomaly/Observation 2 - ., Impact of weekends/holidays]
*   [Anomaly/Observation 3 - , Changes in testing methods]
*   [Anomaly/Observation 4 - ., Differences in vaccination curve shapes]

*Refer to the notebook's "Anomalies" section for more details.*

## Future Enhancements

*   Include more detailed analysis of specific countries within the selected continents.
*   Incorporate additional data points (e.g., stringency index, demographics).
*   Build interactive dashboards using libraries like Dash or Streamlit.
*   Perform time-series forecasting on key metrics.
*   Analyze the impact of specific interventions or events.

## Contributing

If you would like to contribute to this project, please feel free to fork the repository and submit a pull request.

## License

This project is licensed under the [Choose a License, e.g., MIT License]. See the `LICENSE` file for details. (If you don't have a LICENSE file, you can state "No specific license applied" or consider adding one).

## Contact

VIVIAN MUKHONGO
(https://github.com/MukhongoVivian-prog)
