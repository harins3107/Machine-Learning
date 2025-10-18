# Machine-Learning
A beginner-friendly repository containing implementations of fundamental machine learning algorithms using Python and scikit-learn.

## 📚 Projects

### 1. Linear Regression - Home Price Prediction
Predicts house prices based on area using Linear Regression.

**Dataset:** `homeprices.csv` (5 samples)  
**Model Performance:** R² Score = 95.29%  
**Equation:** `Price = 135.79 × Area + 180,616.44`

### 2. Logistic Regression - Insurance Purchase Prediction
Predicts whether a person will buy insurance based on age using Logistic Regression.

**Dataset:** `insurance_data.csv` (27 samples)  
**Model Performance:** Accuracy = 83.33%  
**Equation:** `P(y=1) = 1 / (1 + e^(-z))` where `z = 0.1609 × Age - 5.8189`

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas scikit-learn matplotlib jupyter
```

### Running the Projects

1. **Clone the repository:**
```bash
git clone https://github.com/harins3107/Machine-Learning.git
cd Machine-Learning
```

2. **Open Jupyter Notebook:**
```bash
jupyter notebook
```

3. **Run the notebooks:**
   - Open `logistic_regression.ipynb` for the insurance prediction project
   - Explore the visualizations and model results

## 📊 Key Features

- **Data Visualization:** Scatter plots, regression lines, and sigmoid curves
- **Model Training:** Step-by-step implementation with scikit-learn
- **Performance Metrics:** R² score, accuracy, coefficients, and intercepts
- **Predictions:** Sample predictions on test data with probability estimates

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation
- **scikit-learn** - Machine learning algorithms
- **matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive development

## 📈 Results Summary

| Project | Algorithm | Accuracy/Score | Dataset Size |
|---------|-----------|----------------|--------------|
| Home Price Prediction | Linear Regression | 95.29% (R²) | 5 samples |
| Insurance Prediction | Logistic Regression | 83.33% | 27 samples |

## 📝 What You'll Learn

- Difference between regression (continuous) and classification (binary) problems
- Training machine learning models with scikit-learn
- Evaluating model performance using appropriate metrics
- Creating visualizations to understand data patterns
- Making predictions using trained models

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## 📄 License

This project is for educational purposes.

## 👤 Author

**Harini VK**

GitHub: [@harins3107](https://github.com/harins3107)
