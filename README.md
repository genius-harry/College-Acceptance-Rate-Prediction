
# Comprehensive Predictive Analysis of University Acceptance Rates

## Overview
This project seeks to unveil the complex dynamics of college admissions through comprehensive predictive analysis using advanced statistical and machine learning methods. The goal is to explore the various factors influencing college acceptance rates using a combination of traditional statistical models and deep learning techniques.

## Project Structure
- `src/`: Contains the main code for data analysis.
- `data/`: Includes the raw datasets and the processed datasets used for analysis.
  - `raw/`: Raw datasets.
  - `modified/`: Datasets that have been cleaned or modified.
- `notebooks/`: Jupyter notebooks that document the step-by-step process of analysis.
- `docs/`: Contains relevant documentation, including the final presentation.
- `output/`: The output files such as final results from the analysis.

## Methodology
The project employs the following methodologies:
1. **Data Cleaning**: Filtering, aggregating, and merging datasets from various sources.
2. **Exploratory Data Analysis (EDA)**: Understanding and visualizing the data.
3. **Modeling Techniques**:
   - Multi-Variable Regression
   - LASSO for feature selection
   - Polynomial Regression
   - Tree-based models (Random Forest)
   - Feedforward Neural Networks (FNN)
   - Convolutional Neural Networks (CNN)
   - Autoencoder
   - ResNet50
   - DenseNet
4. **Model Comparison**: Evaluating the performance of different models using metrics like MAE and MSE.
5. **Limitations**: The analysis is constrained by the lack of student-level data, and some neural network models offer less interpretability compared to traditional statistical methods.

## Data Sources
- **Kaggle**: College Admissions data and American University data.
- **Urban Catalog**: Racial and ethnic representativeness of U.S. postsecondary institutions.
- **IPEDS Dataset**: Comprehensive data on U.S. colleges, including demographics, tuition, and acceptance rates.

## Models and Architectures
The following deep learning architectures were explored:
- **Feedforward Neural Network**: A simple FNN with multiple hidden layers.
- **CNN**: Convolutional layers with max pooling, followed by dense layers.
- **Autoencoder**: Encodes and decodes data for dimensionality reduction and reconstruction.
- **ResNet50**: Residual networks for deep learning with skip connections to prevent vanishing gradients.
- **DenseNet**: Densely connected convolutional networks for efficient gradient flow and feature reuse.

## Results
The models were evaluated based on their mean absolute error (MAE) and performance metrics. The comparison of different architectures revealed insights into which approaches best predict college acceptance rates.

## Limitations
The analysis focuses on university-level data due to confidentiality restrictions on student-level data. Additionally, some neural networks, while effective, offer less variable explanation compared to traditional models.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/genius-harry/College-Acceptance-Rate-Prediction.git
    cd college-acceptance-rate
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis:
    You can either run the code in the `src/` folder or execute the Jupyter notebooks located in `notebooks/`.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
