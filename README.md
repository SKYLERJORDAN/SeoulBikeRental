# Seoul Bike Rental Data Analysis

This project focuses on analyzing bike rental data from Seoul, South Korea. The dataset contains information about the number of rented bikes, along with various weather conditions and other factors that may influence bike rental behavior.

## Dataset

The dataset used in this analysis is stored in the `SeoulBikeData.csv` file. It includes the following columns:

- Date
- Rented Bike Count
- Hour
- Temperature(°C)
- Humidity(%)
- Wind speed (m/s)
- Visibility (10m)
- Dew point temperature(°C)
- Solar Radiation (MJ/m2)
- Rainfall(mm)
- Snowfall (cm)
- Seasons
- Holiday
- Functioning Day

## Analysis

The analysis is performed using a Jupyter Notebook (`SeoulBikeData.ipynb`), which contains the following steps:

1. Importing the necessary libraries (pandas)
2. Loading the dataset from the CSV file
3. Exploring the dataset's shape, checking for null values, and examining data types
4. Counting the number of occurrences of each combination of Seasons and Holiday

## Tableau Graphs

To visualize the insights gained from the analysis, Tableau graphs have been created and can be accessed through the following link:

[Seoul Bike Rental Tableau Graphs](https://public.tableau.com/app/profile/skyler.jordan5373/viz/SeoulBikeRental_16983598436080/SeoulBikeRental)

These graphs provide a visual representation of the bike rental patterns and trends in Seoul, allowing for a better understanding of the factors influencing bike rental behavior.

## Requirements

To run the Jupyter Notebook and reproduce the analysis, the following requirements must be met:

- Python 3.x
- pandas library

## Usage

1. Clone the repository to your local machine
2. Install the required libraries using `pip install -r requirements.txt`
3. Open the `SeoulBikeData.ipynb` notebook using Jupyter Notebook or JupyterLab
4. Run the notebook cells to execute the analysis

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The dataset used in this analysis is sourced from [Seoul Bike Sharing Demand Data Set](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand) on the UCI Machine Learning Repository.
