# Agribusiness Data Analysis

## Week 1: Data Collection, Exploration and Cleaning

This project focuses on collecting, exploring, cleaning, and analyzing agricultural datasets to understand patterns in crop production, agricultural trade, and cereal yield.

## Objective

The objective of this project is to:

* Collect relevant agricultural datasets
* Explore dataset structure and characteristics
* Identify missing values and duplicate records
* Analyze data types and data quality
* Create visualizations to identify agricultural trends
* Clean the datasets for further analysis

## Datasets

The project uses three datasets:

1. **Crop Production Dataset**

   * Contains information about crop production across Indian states and districts.
   * Includes fields such as State, District, Year, Season, Crop, Area, and Production.

2. **FAOSTAT Agricultural Trade Dataset**

   * Contains agricultural trade-related information from FAOSTAT.

3. **Cereal Yield Dataset**

   * Contains cereal yield data measured in kg/ha.
   * Source: World Bank / FAO.

## Analysis Performed

The following analysis was performed:

* Dataset shape and structure
* Missing value analysis
* Duplicate analysis
* Data type analysis
* Total crop production by year
* Top 10 crops by production
* Crop production by season
* Top 10 states by production
* Area vs Production analysis

## Data Cleaning

The crop production dataset was cleaned by:

* Removing rows with missing `Production` values
* Removing duplicate records
* Saving the cleaned dataset separately as `crop_cleaned.csv`

## Tools and Technologies

* Python
* Pandas
* Matplotlib
* Google Colab
* GitHub

## Project Files

* `crop.csv` – Original crop production dataset
* `crop_cleaned.csv` – Cleaned crop production dataset
* `faostat.csv` – FAOSTAT agricultural trade dataset
* `cereal_yield.csv` – Cereal yield dataset
* `week1_data_exploration.ipynb` – Google Colab/Jupyter Notebook containing the analysis
* `Week1_Agribusiness_Data_Analysis.docx` – Project report

## Conclusion

The project demonstrates the basic data analysis workflow in agribusiness, including data collection, exploration, cleaning, visualization, and interpretation. The cleaned datasets and analysis provide a foundation for further agricultural data analysis and predictive modeling.
