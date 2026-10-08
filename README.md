# Python Data Analysis Case Studies

A collection of small applied Python projects focused on practical data preparation, exploratory analysis, public-data processing and reproducible analytical workflows.

The projects were reorganised as portfolio case studies using public or sample datasets. They are intended to demonstrate how Python can be used to turn raw data into structured findings rather than to reproduce classroom exercises.

## Case studies

### 1. [Used Volkswagen Market Analysis — Latvia](01_used_car_market_analysis/used_car_market_analysis.ipynb)

Historical public vehicle-listing data are cleaned and analysed to explore asking-price distributions, model frequency, fuel-type differences and the relationship between vehicle year and price.

**Skills:** `pandas` · data cleaning · public web-data capture · descriptive statistics · visualization

### 2. [Bike Rental Demand Analysis](02_bike_rental_demand_analysis/bike_rental_demand_analysis.ipynb)

Bike-sharing demand is examined across time of day, seasons, working-day status, temperature and humidity.

**Skills:** `pandas` · datetime processing · groupby · pivot tables · exploratory analysis · visualization

### 3. [Latvia Temperature Patterns — Public Weather Data](03_latvia_weather_analysis/latvia_temperature_analysis.ipynb)

Public Latvian temperature data are used to study daily temperature changes and spatial variation during a ten-day period in November 2023.

**Skills:** public data · aggregation · time-series analysis · spatial coordinates · visualization

## Repository structure

```text
python-data-analysis-case-studies/
├── README.md
├── requirements.txt
├── data/
│   ├── README.md
│   ├── volkswagen_listings_snapshot.csv
│   ├── bike_sharing_sample.csv
│   ├── latvia_temperature_daily_summary.csv
│   └── latvia_temperature_location_sample.csv
├── 01_used_car_market_analysis/
│   ├── README.md
│   └── used_car_market_analysis.ipynb
├── 02_bike_rental_demand_analysis/
│   ├── README.md
│   └── bike_rental_demand_analysis.ipynb
└── 03_latvia_weather_analysis/
    ├── README.md
    └── latvia_temperature_analysis.ipynb
```

## How to run

1. Clone the repository.
2. Install dependencies with `pip install -r requirements.txt`.
3. Open any notebook from its project folder and run the cells from top to bottom.

The notebooks use relative paths to the compact data snapshots stored in `data/`.

## Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Portfolio context

These case studies use public or sample datasets and contain no employer, client or confidential information. The vehicle-listing project uses a historical static snapshot rather than live scraping so that the published analysis remains reproducible and does not depend on changes to an external website.
