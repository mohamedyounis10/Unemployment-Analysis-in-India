# 🚗 Used Car Price Prediction

A comprehensive machine learning project for predicting used car prices using various regression models. This project includes exploratory data analysis, feature engineering, model comparison, and an interactive Power BI dashboard.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Dashboard](#dashboard)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project aims to predict the selling price of used cars based on various features such as car age, kilometers driven, fuel type, transmission type, and more. The project follows a complete machine learning pipeline from data exploration to model deployment visualization.

## ✨ Features

- **Comprehensive EDA**: Exploratory data analysis with visualizations
- **Data Preprocessing**: Handling missing values, duplicates, and feature engineering
- **Multiple ML Models**: Comparison of Linear Regression, SVM, and Decision Tree Regressor
- **Feature Engineering**: Age calculation, skewness correction, and outlier handling
- **Model Evaluation**: Cross-validation with RMSE and R² metrics
- **Interactive Dashboard**: Power BI dashboard for data visualization

## 📁 Project Structure

```
Task 3/
│
├── Dataset/
│   └── car data.csv          # Dataset containing car information
│
├── Dashboard/
│   ├── Car.pbix              # Power BI dashboard file
│   └── img.png              # Dashboard preview image
│
├── notebook.ipynb            # Main Jupyter notebook with analysis
│
└── README.md                 # Project documentation
```

## 📊 Dataset

The dataset contains **301 records** with the following features:

- **Car_Name**: Name of the car
- **Year**: Manufacturing year
- **Selling_Price**: Target variable (selling price in lakhs)
- **Present_Price**: Current price of the car
- **Driven_kms**: Kilometers driven
- **Fuel_Type**: Type of fuel (Petrol, Diesel, CNG)
- **Selling_type**: Type of seller (Dealer, Individual)
- **Transmission**: Transmission type (Manual, Automatic)
- **Owner**: Number of previous owners

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Scikit-learn**: Machine learning models and preprocessing
- **Jupyter Notebook**: Interactive development environment
- **Power BI**: Dashboard creation and visualization

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "Task 3"
   ```

2. **Install required packages**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Open Jupyter Notebook**
   ```bash
   jupyter notebook notebook.ipynb
   ```

## 🚀 Usage

1. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook notebook.ipynb
   ```

2. **Run all cells** to execute the complete analysis pipeline:
   - Data loading and exploration
   - Data preprocessing and cleaning
   - Feature engineering
   - Model training and evaluation
   - Visualization generation

3. **View the Dashboard**
   - Open `Dashboard/Car.pbix` in Power BI Desktop
   - Explore interactive visualizations and insights

## 📈 Model Performance

The project compares three regression models using 5-fold cross-validation:

| Model | RMSE | R² Score |
|-------|------|----------|
| **Linear Regression** | 0.137 | 0.970 |
| **Decision Tree** | 0.157 | 0.958 |
| **SVM** | 0.184 | 0.944 |

**Best Model**: Linear Regression achieved the highest R² score (0.970) and lowest RMSE (0.137).

## 📊 Dashboard

The Power BI dashboard provides interactive visualizations including:

- Price distribution analysis
- Fuel type and transmission comparisons
- Car age vs. selling price relationships
- Kilometers driven analysis
- Model performance metrics

<img width="1283" height="713" alt="Screenshot 2026-01-20 215357" src="https://github.com/user-attachments/assets/95935169-ba12-4e3e-9c54-8a785d7688a4" />

## 🔍 Key Insights

1. **Car Age Impact**: Older cars generally have lower selling prices
2. **Fuel Type**: Diesel cars with automatic transmission tend to be more expensive
3. **Kilometers Driven**: Higher mileage correlates with lower prices
4. **Data Quality**: The dataset was cleaned by removing duplicates and handling outliers

## 📝 Results

- Successfully predicted car prices with **97% accuracy** (R² = 0.970)
- Identified key features affecting car prices
- Created comprehensive visualizations for data understanding
- Developed an interactive dashboard for business insights

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).


## 👤 Author

**Mohamed Younis**
- GitHub: [@mohamedyounis10](https://github.com/mohamedyounis10)
- Email: mohamed1younis1@gmail.com

## 🙏 Acknowledgments

- Dataset source: (https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india/data)
- CodeAlpha for the project opportunity
- Open source community for tools and libraries

---

For questions or suggestions, please open an issue on GitHub.



