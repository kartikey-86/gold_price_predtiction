# Optimized Gold Price Prediction using Machine Learning

This project provides a comprehensive, production-ready implementation for predicting gold prices using various machine learning algorithms. 

## 🚀 Features

### Core Functionality
- **Multiple ML Algorithms**: Lasso Regression, Random Forest, and XGBoost
- **Comprehensive Data Preprocessing**: Outlier removal, feature scaling, missing value handling
- **Feature Engineering**: Rolling mean trends, polynomial features
- **Hyperparameter Tuning**: Grid search with cross-validation
- **Model Evaluation**: Multiple metrics (R², RMSE, MAE)
- **Feature Importance Analysis**: For tree-based models
- **Model Persistence**: Save and load trained models


### Visualization & Analysis
- **Correlation Analysis**: Heatmaps and statistical summaries
- **Data Distribution Plots**: Histograms and box plots
- **Model Comparison**: Performance comparison across algorithms
- **Feature Importance**: Visual representation of feature contributions
- **Price Trend Analysis**: Time series visualization

## 📁 Project Structure

```
gold-price-prediction/
├── gold_price_prediction_optimized.py  # Main implementation
├── example_usage.py                    # Usage examples
├── README.md                          # This file
├── sample_gold_price_data.csv         # Sample data (generated)

```
   

## 📊 Data Format

The model expects a CSV file with the following columns:
- `Date`: Date column (will be parsed as datetime)
- `SPX`: S&P 500 index values
- `GLD`: Gold ETF prices
- `USO`: Oil ETF prices
- `SLV`: Silver ETF prices (optional)
- `EUR/USD`: Target variable (gold price in EUR/USD)
