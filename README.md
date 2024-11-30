# SkinType-Ingredient-Classifier

This repository contains Jupyter Notebooks for data preprocessing and the development of machine learning model architectures to detect suitable skin types based on the ingredients in skincare products. It also includes a preprocessed dataset used in the model development process.

## 📝 Description  
- **Dataset:** Contains a list of skincare ingredients along with their corresponding skin types.
- **Preprocessing Data:** A notebook for cleaning, filtering, and processing the data before using it in the machine learning model.
- **Model Development:** A notebook for building and training the machine learning model using the processed data.

## Data Source
The dataset was collected from publicly available sources such as **Kaggle**.  
Link to the dataset: [Kaggle - Skincare Product Ingredients](https://www.kaggle.com/datasets/dominoweir/skincare-product-ingredients)

## Model
This project features a text classification model using deep learning with **TensorFlow**. The model is designed to classify text sequences into one or more of five categories, making it suitable for multi-label classification tasks.

### Model Details
- **Type:** Sequential Neural Network  
- **Base Architecture:** Embedding and LSTM Layers  

### Performance
| **Metric**               | **Value**   |
|--------------------------|-------------|
| **Accuracy**              | 0.9735      |
| **Validation Accuracy**   | 0.9668      |
| **Loss**                  | 0.3007      |
| **Validation Loss**       | 0.3030      |

