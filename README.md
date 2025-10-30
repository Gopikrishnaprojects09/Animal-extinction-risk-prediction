# Predicting Extinction Risk of Endangered Species using Multimodal Machine Learning

## Overview

This project develops a multimodal machine learning model to predict the extinction risk of endangered species. Moving beyond simple species detection, the model combines different data types—images, sensor data, and conservation status—to provide a comprehensive and proactive tool for conservationists.

## Project Structure

- `data/`: Contains the raw data (`images.csv`, `BfRw Petrogale lateralis.csv`)
- `notebooks/`: Jupyter Notebook for data preparation and analysis (`data_preparation.ipynb`)

## Installation

Set up a Python environment and install dependencies:

```bash
pip install pandas numpy seaborn matplotlib geopy
```

## Usage

1. Place raw data files in the `data/` directory.
2. Open `notebooks/data_preparation.ipynb` in Jupyter Notebook (e.g., VS Code).
3. Run all cells to perform data loading, cleaning, feature engineering, and visualization.

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- geopy

## Results

This project successfully completed the crucial data preparation phase. The data_preparation.ipynb notebook demonstrates a robust pipeline that:

Cleans Raw Data: Irrelevant records, such as blank camera trap images and human sightings, were successfully identified and removed.

Engineers Key Features: New, predictive features were created from the raw data. This includes movement metrics (e.g., distance traveled, average speed) from the GPS data and population metrics (e.g., daily sighting counts) from the image data.

Visualizes Insights: The quality of the data and the engineered features are validated through clear visualizations, including a map of animal movement and time-series plots of activity.

Integrates Multimodal Data: The notebook concludes with the successful integration of all three data sources into a single, unified dataset, which is now ready for the machine learning model.
