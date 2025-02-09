# Crop and Fertilizer Recommendation System Using Machine Learning

This repository contains a Crop and Fertilizer Recommendation System built using Python and Machine Learning. The system utilizes Decision Tree Classifiers to provide recommendations for optimal crop and fertilizer choices based on soil and environmental parameters.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Overview

The Crop and Fertilizer Recommendation System is designed to assist farmers and agricultural experts by:
- Recommending the best crop based on soil nutrient levels and climatic conditions.
- Suggesting the most suitable fertilizer based on environmental parameters and soil characteristics.

Both systems include data exploration, visualization, preprocessing, model training, evaluation, and prediction using Decision Tree Classifiers.

## Features

- **Data Acquisition & Exploration:**  
  Load and inspect datasets, check for missing values, duplicates, and understand the data structure.

- **Data Visualization:**  
  Visualize distributions and relationships with histograms, scatter plots, boxplots, and heatmaps using Matplotlib and Seaborn.

- **Data Preprocessing:**  
  Encode categorical variables, scale numerical features, and prepare data for modeling.

- **Machine Learning:**  
  Train Decision Tree models for both crop and fertilizer recommendation and evaluate model performance using accuracy scores.

- **Prediction Functions:**  
  - `crop_rec`: Recommends the best crop based on input parameters (e.g., Nitrogen, Phosphorous, Potassium, temperature, humidity, pH, rainfall).
  - `recommend_fertilizer`: Suggests the optimal fertilizer based on parameters such as temperature, humidity, moisture, soil type, crop type, and nutrient levels.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- **Python:** Version 3.6 or later
- **Jupyter Notebook:** Installed for running the notebooks
- **Git:** Installed for cloning the repository

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sahilmate/Crop_Fertilizer_RS.git
   cd Crop_Fertilizer_RS
   ```

2. **Create and Activate a Virtual Environment (Optional but Recommended):**

   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install the Required Packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open and Run the Notebooks:**
   - **crop.ipynb:** Contains the code for the Crop Recommendation System.
   - **fertilizer.ipynb:** Contains the code for the Fertilizer Recommendation System.

3. **Datasets:**
   - Ensure that the datasets (`Crop_recommendation.csv` and `Fertilizer Prediction.csv`) are placed in the `dataset/` directory.

## Project Structure

```
Crop_Fertilizer_RS/
├── dataset/
│   ├── Crop_recommendation.csv
│   └── Fertilizer Prediction.csv
├── crop.ipynb
├── fertilizer.ipynb
├── requirements.txt
└── README.md
```

## Requirements

The project uses the following Python packages:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter

All dependencies are listed in the [`requirements.txt`](requirements.txt) file.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find a bug, please follow these steps:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -am 'Add new feature or fix bug'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request describing your changes.

## Acknowledgements

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
