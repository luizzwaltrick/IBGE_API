# IBGE Name Frequency Analysis

This project collects and analyzes data from the **IBGE API** (Brazilian Institute of Geography and Statistics) to visualize the frequency of specific names over time. The data is exported to a CSV file, and two types of visualizations are created:
1. A **line chart** showing the frequency of names over time.
2. A **bar chart** comparing the total frequency of each name.

## Features
- Fetches data from the IBGE API for a list of names.
- Handles special characters in names (e.g., `João` vs. `joao`).
- Exports the collected data to a CSV file.
- Generates interactive visualizations using **Plotly Express** and **Seaborn**.

## Requirements
To run this project, you need the following Python libraries:
- `pandas`
- `requests`
- `plotly.express`
- `seaborn`
- `matplotlib`

You can install the required libraries using:
```bash
pip install pandas requests plotly seaborn matplotlib
