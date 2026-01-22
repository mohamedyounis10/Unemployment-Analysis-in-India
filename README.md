# Unemployment Analysis in India (COVID-19 Impact) 📊

A comprehensive data analysis project examining the unemployment trends across different states in India during the COVID-19 pandemic, with a focus on the impact of the nationwide lockdown implemented in April 2020.

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dataset](#dataset)
- [Key Insights](#key-insights)
- [Dashboard](#dashboard)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project provides an in-depth analysis of unemployment data in India from May 2019 to June 2020, with particular emphasis on understanding the economic impact of the COVID-19 pandemic and the subsequent nationwide lockdown. The analysis includes exploratory data analysis (EDA), visualization, and key insights derived from the data.

### Objectives

- Analyze unemployment trends across different Indian states
- Examine the impact of COVID-19 lockdown on employment rates
- Compare urban vs rural unemployment patterns
- Identify regional disparities in unemployment impact
- Visualize trends and patterns through comprehensive dashboards

## 📁 Project Structure

```
/
│
├── Dataset/
│   └── Unemployment in India.csv          # Main dataset file
│
├── Dashboard/
│   ├── India.pbix                         # Power BI dashboard file
│   ├── Unemployment_India.csv            # Processed dataset for dashboard
│   ├── img1.png                          # Dashboard visualization image
│   ├── india flag.png                    # India flag image
│   └── in.json                           # Dashboard configuration
│
├── images/                                # Project images directory
│   ├── project-banner.png                # Main project banner (add your image here)
│   └── dashboard-screenshot.png          # Dashboard screenshot (add your image here)
│
├── notebook.ipynb                         # Jupyter notebook with complete EDA
│
└── README.md                              # Project documentation
```

## ✨ Features

- **Comprehensive EDA**: Detailed exploratory data analysis with statistical summaries
- **Data Cleaning**: Handling missing values and data preprocessing
- **Visualizations**: Multiple charts and graphs including:
  - Time series analysis
  - Regional comparisons
  - Urban vs Rural analysis
  - Correlation heatmaps
  - Distribution plots
- **Interactive Dashboard**: Power BI dashboard for interactive data exploration
- **Key Insights**: Data-driven conclusions about unemployment trends

## 📊 Dataset

The dataset contains **768 records** with the following attributes:

| Attribute | Description |
|-----------|-------------|
| **Region** | State or administrative region in India |
| **Date** | Month and year of data recording (May 2019 – June 2020) |
| **Frequency** | Data collection interval (Monthly) |
| **Estimated Unemployment Rate (%)** | Percentage of labor force unemployed |
| **Estimated Employed** | Total estimated number of employed individuals |
| **Estimated Labour Participation Rate (%)** | Percentage of working-age population in labor force |
| **Area** | Geographic classification (Rural or Urban) |

### Dataset Statistics

- **Total Records**: 768 entries
- **States Covered**: 28 Indian states/regions
- **Time Period**: May 2019 - June 2020
- **Missing Values**: Handled using mode (categorical) and median (numerical) imputation

## 🔍 Key Insights

### 1. The Lockdown Shock
- **Before Lockdown** (pre-April 2020): Average unemployment rate of **9.56%**
- **During Lockdown** (post-April 2020): Average unemployment rate surged to **20.19%**
- A **111% increase** in unemployment within a single month, directly correlating with the nationwide lockdown implementation.

### 2. Regional Impact Disparities
- States like **Kerala** and **Uttar Pradesh** showed significant increases in unemployment
- **West Bengal** experienced substantial job losses
- Impact varied significantly across states, with industrial/service-sector dependent states hit harder

### 3. Urban vs Rural Divide
- **Urban areas** consistently faced higher unemployment rates and sharper increases
- This is attributed to the shutdown of construction, manufacturing, and service industries in cities
- **Rural areas** were partially buffered by continued agricultural activities

### 4. Labor Force Participation
- Negative correlation between Unemployment Rate and Labor Participation Rate
- Indicates "Discouraged Worker Effect" - workers exiting the labor market as jobs became scarce

### 5. Massive Job Losses
- Major states lost millions of jobs during lockdown
- Example: **West Bengal** lost approximately **3.73 million jobs** (20.72% decline)
- **Kerala** experienced **33.14%** job loss percentage

## 📈 Dashboard

The project includes an interactive Power BI dashboard (`Dashboard/India.pbix`) that provides:

- Real-time unemployment rate visualization
- Regional comparison charts
- Time series analysis
- Urban vs Rural breakdowns
- Interactive filters and drill-down capabilities

<img width="1289" height="721" alt="Screenshot 2026-01-20 214242" src="https://github.com/user-attachments/assets/f1c6eb80-0910-4e61-8438-6f0cbfd3c015" />

### Dashboard Features

- **Interactive Visualizations**: Click-through analysis with multiple chart types
- **Regional Filters**: Filter by state/region for detailed analysis
- **Time-based Analysis**: Track trends over the entire time period
- **Comparative Analysis**: Side-by-side comparison of different metrics

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Power BI Desktop (for dashboard)

### Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install from requirements file:

```bash
pip install -r requirements.txt
```

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "Task 2"
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Open Jupyter Notebook**
   ```bash
   jupyter notebook notebook.ipynb
   ```

4. **Open Power BI Dashboard** (optional)
   - Open `Dashboard/India.pbix` in Power BI Desktop
   - Ensure the data source path is correctly configured

## 💻 Usage

### Running the Analysis

1. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook notebook.ipynb
   ```

2. **Execute Cells Sequentially**
   - The notebook is organized into sections:
     - Data Loading
     - Exploratory Data Analysis
     - Data Cleaning
     - Visualization
     - Key Insights

3. **View Results**
   - All visualizations will be displayed inline
   - Key statistics and insights are printed after each analysis section

### Using the Dashboard

1. Open `Dashboard/India.pbix` in Power BI Desktop
2. Navigate through different visualizations using the filters
3. Export reports or screenshots as needed

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive development environment
- **Power BI**: Business intelligence and dashboard creation

## 📊 Results

The analysis reveals significant economic disruption caused by the COVID-19 pandemic:

- **Unemployment doubled** from ~9.5% to ~20% after lockdown
- **Regional disparities** in impact severity
- **Urban areas** more affected than rural areas
- **Millions of jobs lost** across major states
- **Labor force participation** declined due to discouraged workers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Mohamed Younis**
- GitHub: [@mohamedyounis10](https://github.com/mohamedyounis10)
- Email: mohamed1younis1@gmail.com

## 🙏 Acknowledgments

- Dataset source: (https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india/data)

For questions or suggestions, please open an issue on GitHub.
