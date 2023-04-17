# Image multiclass classification with SVC, Random Forest, and Decission Tree

An example project that demonstrates feature extraction using a pre-trained ResNet-18 model and evaluates the performance of SVC, Random Forest, and Decission Tree classifiers on the extracted features to classify images.
The example uses the [Multi-class Weather Dataset](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset).

## Description

This project provides a framework for extracting features from a dataset using a pre-trained ResNet-18 model, and utility functions for evaluating the performance of a classifier on the extracted features using various metrics and plotting the multiclass ROC curve.

## Installation

1. Clone the repository
   ```bash 
   git clone https://github.com/DavidHdezG/Multiclass-Clasiffication-SVC-RF-DT.git
   
2. Install the requirements
   ```bash 
   pip install -r requirements.txt

## Usage

1. Download the dataset from [here](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset) and extract it to the root directory of the project or set the Kaggle credentials to download the dataset using the official API command
   ```bash 
   kaggle datasets download -d pratik2901/multiclass-weather-dataset
2. Modify the path variable to point to the dataset directory.
3. Run the script
   ```bash 
   python main.py 
