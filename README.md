# Tesla Stock Price Prediction through MFCC Feature Extraction and LSTM Modeling

## Features
- Converts Tesla stock price data into audio signals using MFCC feature extraction.
- Trains LSTM and SVM models to predict stock price movements based on extracted features.
- Provides a comprehensive analysis of model performance using various metrics.
- Includes both code and datasets required to replicate the study.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jeanqazxcv/master-s-thesis.git
2. Navigate to the project directory:
   ```bash
   cd master-s-thesis
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
## Usage

1. Run Jupyter Notebooks:
- Open the Jupyter notebooks in the Code/ directory to start running the experiments. You can use the following command to start Jupyter Notebook:
  ```bash
  jupyter notebook
  
- The following .ipynb files are available:
  - mfcc_5daysfeature_tsla_LSTM.ipynb: For training and evaluating the LSTM model.
  - mfcc_5daysfeature_tsla_svm.ipynb: For training and evaluating the SVM model.
  - mfcc_5daysfeature_tsla_svm_pca.ipynb: For training and evaluating the SVM model with PCA applied to the features.
2. Load the Datasets:
- The datasets are located in the Datasets/ directory and include .wav files representing Tesla's stock prices.

3. Train the Models:
- Open the respective Jupyter notebooks to preprocess the data, extract MFCC features, and train the models.
- Follow the instructions in each notebook for specific steps.

## Credits
This project is part of a Master's thesis by Jean Hong, focusing on innovative methods for stock price prediction using audio signal processing techniques.
