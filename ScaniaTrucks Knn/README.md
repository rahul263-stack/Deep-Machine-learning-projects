
## Data-set Link: https://archive.ics.uci.edu/ml/machine-learning-databases/00421/.
### Relevant Information:
The dataset consists of data collected from heavy Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurised air that are utilized in various functions in a truck, such as braking and gear changes. The datasets'positive class consists of component failures for a specific component of the APS system. The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts. 
## Objective:
Classify the point in negative class or positive class.
### Type of Problem:
Binary Classification(2-class classification)
### Steps we followed:
Task 1: Perform proper EDA, if any missing values are there try to fill them/remove them based on information that you get from EDA, find the correlation features and remove them from data, do some data cleaning if possible, etc. etc., you can do all sorts of data preprocessing and prepare data for models.

Task 2: Apply KNN on the data find the best k with 3-fold cross-validation and print the error metric value on the test data with the best k.

## How to Run:
1. First download the dataset from the source then run the file: "1-KNN_ScaniaTrucks_CreatingDatasets.ipynb" and create CSV file from raw data.
2. Then run the file: "2-KNN_ScaniaTrucks.ipynb".
## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.

## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/

## Built With
*	ipython-notebook - Python Text Editor
*	sklearn - Machine learning library
*	seaborn, matplotlib.pyplot, - Visualization libraries
*	numpy, scipy- number python library
*	pandas - data handling library

## Authors
*	Rahul Kuamr - Complete work
