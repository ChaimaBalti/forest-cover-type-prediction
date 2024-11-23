# **Forest Cover Type Prediction**

## **Introduction**

This repository documents a project focused on predicting forest cover types using the [Kaggle dataset: Forest Cover Type Prediction Dataset](https://www.kaggle.com/competitions/forest-cover-type-prediction/data). The project is part of the **Big Data** module of ENIT's 3rd year MIndS 2024-2025 program and is undertaken by **Group 4**: Chaima Balti, Roukaya Lakhzouri, and Salsabil Rouahi. We are working under the supervision of our professor, **Moez Ben Haj Hmida**.

The primary goal of this project is to explore and apply various machine learning techniques to accurately classify forest cover types based on features related to soil, climate, and topography.

## **Project Structure**

The repository currently includes the following files and notebooks:

- **README.md**: This file provides an overview of the project, its objectives, and the file structure.
- **SVM_all_data.ipynb**: A Jupyter notebook that documents the application of a Support Vector Machine (SVM) model using the entire dataset.
- **SVM_sampled_features.ipynb**: A Jupyter notebook that documents the application of a Support Vector Machine (SVM) model using a selected subset of features for optimized performance.
- **train.csv**: The training dataset containing features and target labels for building the model.
- **test.csv**: The test dataset used for evaluating the model's performance.
- **test_target.csv**: The target labels corresponding to the test dataset for validation purposes.

More models and analysis files will be added in the future as the project progresses.

## **Dataset Description**

The dataset used for this project contains various attributes related to environmental factors such as:

- **Soil** characteristics.
- **Climate** conditions.
- **Topographical** information.

These features are used to classify different types of forest cover, making the dataset a valuable resource for testing various classification algorithms.

## **Project Objectives**

1. **Data Exploration**: Perform an initial analysis of the dataset to understand the distributions, correlations, and relevance of features.
2. **Feature Engineering**: Identify the most impactful features and engineer new features if necessary.
3. **Model Development**: Implement a range of machine learning models, such as:
   - Support Vector Machine (SVM)
   - Random Forests
4. **Model Evaluation**: Evaluate the models using performance metrics like accuracy, precision, recall, and F1 score.
5. **Model Optimization**: Fine-tune the models for better performance and compare the results.
6. **Future Work**: Integrate more advanced models and explore ensemble methods for improved accuracy.

## **Getting Started**

### **Prerequisites**

To run the notebooks and replicate the results, you need the following software and libraries installed:

- Python 3.8 or higher
- Jupyter Notebook
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

### **Installation**

Clone the repository to your local machine:

```bash
git clone https://github.com/ChaimaBalti/forest-cover-type-prediction
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## **Contributors**

- **Chaima Balti**
- **Roukaya Lakhzouri**
- **Salsabil Rouahi**

Supervised by **Professor Moez Ben Haj Hmida**.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgments**

- **ENIT and Moez Ben Haj Hmida** for providing the resources and guidance.
- **Kaggle** for the Forest Cover Type Prediction Dataset.
