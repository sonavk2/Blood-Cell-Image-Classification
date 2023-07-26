# Blood-Cell-Image-Classification

### Install

This project required **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Objective
The main objective of this analysis is to build a deep learning model using a Blood Cell Images dataset for Image classification. The focus on the analysis is on using Convolutionl Neural Networks(CNNs) for classification. The analysis provides an accuracte model for classifying different types of blood
crlls which can be crucial for medical diagnosis and research. The use of deep learning models can also automate the process of blood cell classification, saving time and effort for medical professionals and researchers.

## Contents
1. Data Cleaning and preprocessing steps
2. EDA
3. Models Trained and Evaluated:
- CNN
- Transfer Learning

## Data
The chosen dataset is from Kaggle(https://www.kaggle.com/datasets/paultimothymooney/blood-cells), which  contains 12,500 augmented images of blood cells (JPEG) with accompanying cell type labels (CSV). There are approximately 3,000 images for each of 4 different cell types 
grouped into 4 different folders (according to cell type).

**Classes**
1. Eosinophil
2. Lymphocyte
3. Monocyte
4. Neutrophil

### The JPEGImages:

Image Type : jpeg(JPEG)
Width x Height : 96 x 96
