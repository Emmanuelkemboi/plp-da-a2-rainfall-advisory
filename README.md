# Rainfall Analysis and Planting Advisory

## Project Overview

This project analyses monthly rainfall data across five Kenyan counties using Python and NumPy. It cleans invalid Machakos rainfall entries, calculates rainfall statistics, identifies wettest months and dry months, and recommends two-month planting windows.

## Project Files

- `rainfall_analysis.ipynb` – Jupyter Notebook containing data cleaning, analysis and planting recommendations.
- `rainfall_summary.csv` – Summary of rainfall statistics for all five counties.
- `requirements.txt` – Required Python libraries.

## How to Run

1. Clone or download this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open `rainfall_analysis.ipynb` in VS Code or Jupyter Notebook.
4. Select a Python kernel and run all cells from top to bottom.

## Planting Advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April–May as their recommended planting window based on consecutive rainfall totals.
- Machakos has November–December as its recommended planting window.
- These recommendations are based on historical rainfall data and should be considered alongside current weather forecasts and local agricultural conditions.

## Data Quality

The Machakos dataset contained two invalid readings, which were replaced with the rounded mean of the ten valid observations (68 mm).

## Technologies Used

- Python
- NumPy
- Jupyter Notebook
- CSV module