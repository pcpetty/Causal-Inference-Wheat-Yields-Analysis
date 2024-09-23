# Causal-Inference-Wheat-Yields-Analysis

This repository contains an analysis of the impact of cover crops on wheat yields using causal inference techniques in R. The project aims to determine whether cover crops have a significant effect on wheat crop yields and to showcase the use of causal inference methodologies.

## Project Overview

### Objective
The primary objective of this project is to use causal inference techniques to analyze the relationship between the use of cover crops and the resulting wheat yields. By employing statistical models, we aim to estimate the causal effect of cover crops on crop production outcomes.

### Key Skills Demonstrated
- **Causal Inference**: Application of statistical techniques to infer causality between variables.
- **Data Cleaning and Preparation**: Handling missing data, feature engineering, and data transformation.
- **Data Visualization**: Creating plots and graphs to visually communicate findings.
- **Statistical Modeling in R**: Using R for regression analysis and other statistical models.

## Repository Structure

Causal-Inference-Wheat-Yields-Analysis/ ├── data/ # Folder containing raw and processed data files ├── scripts/ # Folder containing R scripts for data processing and analysis ├── figures/ # Folder containing figures and visualizations generated from the analysis ├── docs/ # Additional documentation and resources ├── Causal-Inference-Cover-Crops-Wheat-Yields.Rmd # RMarkdown file with full analysis ├── README.md # Project documentation (this file) └── requirements.txt # List of R packages required for the analysis

## Data

The dataset used in this project includes features such as soil quality, cover crop type, and wheat yield data. Data preprocessing steps such as handling missing values, normalization, and feature engineering are performed before the analysis.

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Visual and statistical exploration of the dataset to understand relationships and identify potential confounders.

2. **Causal Inference Techniques**:
   - Implementing methods such as regression adjustment and propensity score matching to estimate causal effects.

3. **Statistical Modeling**:
   - Using models like linear regression to quantify the impact of cover crops on wheat yields.

4. **Result Interpretation**:
   - Interpreting the results in the context of agricultural practices and making recommendations.

## Results

The Average Treatment Effect (ATE) is about 3.58. I estimate that when counties have at least 10% of farms with cover crops, average total yield of wheat increases by about 3.58 bushels per acre.

## Reproducing the Analysis

To reproduce the analysis, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/Causal-Inference-Wheat-Yields-Analysis.git
    cd Causal-Inference-Wheat-Yields-Analysis
    ```

2. **Install the required R packages**:
   - Open R or RStudio and run the following command to install the necessary packages:
    ```R
    install.packages(c("tidyverse", "causalinference", "knitr", "ggplot2", "dplyr"))
    ```

3. **Run the analysis**:
   - Open the `Causal-Inference-Cover-Crops-Wheat-Yields.Rmd` file in RStudio.
   - Knit the RMarkdown file to generate the HTML report of the analysis.

## Requirements

A list of the required R packages can be found in the `requirements.txt` file.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [colepetty57@gmail.com].
