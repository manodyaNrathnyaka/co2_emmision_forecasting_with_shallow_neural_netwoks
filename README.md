# CO2 Emission Forecasting with Shallow Neural Networks

## Project Overview
This project focuses on analyzing and forecasting CO2 emissions across different countries using shallow neural networks. The analysis includes data processing, visualization, and predictive modeling of carbon dioxide emissions trends.

## Data Processing
The project processes CO2 emission data with the following steps:

1. Data Collection and Cleaning
   - Uses CSV data source for CO2 emissions by country
   - Handles missing values and data type conversions
   - Removes unnecessary columns (Code, Calling Code)

2. Feature Engineering
   - Processes numerical columns including:
     - Population (2022)
     - Area
     - % of World
     - Density (km²)
   - Converts percentage values to proper numeric format
   - Handles missing values using median imputation

3. Data Transformation
   - Pivots data to create time series format
   - Focuses on specific countries:
     - India
     - China
     - Singapore
     - United States
     - Brazil
     - Argentina

## Dependencies
The project requires the following Python libraries upto now:

- pandas
- matplotlib
- pandas_datareader
- numpy (implicit)

## Project Structure


co2_emmision_forecasting_with_shallow_neural_netwoks/
├── 01)dataprocessing.ipynb     # Data processing and analysis notebook
├── dataset/                    # Data directory
│   └── CO2_filtered_emmision.csv  # Processed dataset
└── README.md                  # Project documentation
```

## Data Sources
- Main dataset: "CO2 emission by countries.csv"
- Processed output: "CO2_filtered_emmision.csv"

## Visualizations
The project includes visualizations such as:
- Missing value analysis through pie charts
- Time series analysis of CO2 emissions by country

## Future Work
- Implementation of shallow neural networks for forecasting
- Additional feature engineering
- Model evaluation and validation
- Comparative analysis between countries

## Getting Started
1. Clone this repository
2. Install required dependencies
3. Run the Jupyter notebooks in sequence

## License
[Add your chosen license here]

## Author
manodyaNrathnyaka

---
Note: This project is part of BSc. AI research work focusing on environmental data analysis and forecasting.