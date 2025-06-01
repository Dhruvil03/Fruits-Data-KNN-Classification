# Fruits Data KNN Classification 🍎🍊🍌

A machine learning project that classifies different fruit types using K-Nearest Neighbors (KNN) algorithm based on physical characteristics and properties of fruits.

## 🌟 Project Overview

This project implements the K-Nearest Neighbors classification algorithm to predict fruit types based on their physical attributes. The model analyzes fruit characteristics such as mass, width, height, and color score to accurately classify different fruit varieties, demonstrating KNN algorithm implementation with comprehensive visualization and K-value optimization.

## 🚀 Features

- **KNN algorithm implementation** for fruit classification
- **Multi-class fruit classification** based on physical characteristics
- **Data preprocessing** pipeline for handling numerical fruit features
- **Advanced visualization** with scatter matrix and 3D scatter plots
- **K-value comparison** with accuracy analysis for different k values
- **Model evaluation** with performance metrics and accuracy analysis
- **K-value optimization** analysis for optimal model performance

## 📊 Dataset

The model uses a fruits dataset with the following features:
- **Mass** - Weight of the fruit
- **Width** - Width measurement of the fruit
- **Height** - Height measurement of the fruit
- **Color Score** - Numerical representation of fruit color
- **Fruit Label** - Target variable (apple, orange, lemon, mandarin, etc.)

## 🏗️ Algorithm Implemented

The project uses the **K-Nearest Neighbors (KNN)** classification algorithm to predict fruit types based on similar fruit characteristics in the feature space.

**Optimal K Value**: [Add your optimal k value] with [Add accuracy]% accuracy

## 🔍 Key Features

### Data Analysis
- Exploratory data analysis (EDA)
- **Scatter matrix** for feature relationship visualization
- **3D scatter plot** for multi-dimensional data exploration
- Data preprocessing and normalization

### Model Development
- KNN algorithm implementation
- **Comprehensive K-value testing** (k=1, 3, 5, 7, 9, etc.)
- **Accuracy comparison across different k values**
- Cross-validation for model validation
- Distance metric selection

### Evaluation
- Confusion matrix analysis
- **K-value accuracy comparison charts**
- **Scatter matrix visualization** for feature relationships
- **3D scatter plots** for data pattern analysis
- Model interpretation and insights

## 🎯 Key Analysis Features

### Visualization Components
- **Scatter Matrix**: Comprehensive pairwise feature relationship analysis showing correlations between mass, width, height, and color score
- **3D Scatter Plot**: Multi-dimensional data exploration and pattern recognition for fruit clustering
- **K-Value Comparison**: Visual comparison of accuracy across different k values
- **Feature Distribution**: Understanding the distribution of fruit characteristics

### K-Value Optimization
The project systematically tests multiple k values to find the optimal parameter:
- Tests odd k values (1, 3, 5, 7, 9, etc.) to avoid ties
- Compares accuracy metrics for each k value
- Identifies the best performing k through cross-validation
- Visualizes the relationship between k and model performance

## 🍎 Fruit Classification Insights

Key findings from the analysis:
- **Mass and width** are strong predictors for fruit classification
- **Color score** helps distinguish between similar-sized fruits
- **3D visualization** reveals distinct clustering patterns for different fruits
- Optimal k-value balances between overfitting and underfitting

## 🔧 Customization

You can easily adapt this project for other classification problems:
1. Replace the dataset with your own fruit data or similar classification data
2. Modify feature columns in the preprocessing section
3. Adjust k-value range for testing
4. Add new visualization techniques as needed
