# NASA OMNI2 Dataset Analysis

This project aims to find the correlations between solar wind parameters and geomagnetic activity on the Earth using statistical analysis and ML techniques, including Linear Regression and Classification (Naive Bayes, LDA and Logistic Regression) with Python. The analysis and modeling are documented in a single Jupyter notebook. 

## Project Structure

```bash
NASA-OMNI2-Analysis/
│
├── README.md
├── requirements.txt
├── notebook/
│ └── OMNI2-Analysis.ipynb
├── data/
│ ├── raw/
│ ├── processed/
│ └── interim/
├── reports/
│ ├── figures/
│ └── analysis-report.pdf
└── LICENSE
```

## Notebook Overview

### OMNI2-Analysis.ipynb
This notebook includes the entire workflow of the project:
- **Data Preprocessing**: Loading, cleaning, and transforming the Bitcoin historical data.
- **Exploratory Data Analysis**: Visualizing data distributions, trends, and correlations.
- **Model Training and Evaluation**: Splitting the data, training machine learning models, and evaluating their performance.
- **Results Visualization**: Visualizing model predictions and key metrics.

## Installation

To run the notebook, you'll need to install the necessary Python packages. Use the following command to install the required packages:

```sh
pip install -r requirements.txt
```

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/NASA-OMNI2-Analysis.git
   ```
   
2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```
   
3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/NASA_OMNI2_Analysis.ipynb
   ```
4. View the Analysis Report: Open analysis-report.pdf located in the reports/ directory for detailed insights from the project analysis.

5. Explore Visualizations: Navigate to the figures/ directory within reports/ to view plotted figures generated during data exploration and analysis

## Data

The data used in this project is stored in the data/ directory:

* raw/: Contains the original, unprocessed data.
* processed/: Contains the processed data ready for analysis.
* interim/: Contains any intermediate data files created during processing.

## Reports

The reports/ directory contains the final analysis report and associated figures for the project.

* analysis-report.pdf: This PDF document provides a comprehensive analysis of the NASA OMNI2 dataset, including methodologies, findings, and conclusions.
* figures/: This directory stores visualizations and plots generated during exploratory data analysis and model evaluation.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
