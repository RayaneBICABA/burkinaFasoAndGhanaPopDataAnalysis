# Population Data Analysis: Burkina Faso & Ghana (1960-2024)

A comprehensive data-driven analysis examining population trends, growth patterns, and demographic shifts in Burkina Faso and Ghana over six decades using Python, Pandas, NumPy, and Matplotlib.

## 📋 Project Overview

This project analyzes historical population data for Burkina Faso and Ghana from 1960 to 2023, uncovering key insights about demographic growth, stability, and critical population milestones. Through statistical analysis and data visualization, we explore how these two West African nations have evolved over time.

### Key Objectives

- **Data Cleaning & Preprocessing**: Handle missing values and irrelevant columns
- **Statistical Analysis**: Calculate growth rates, mean populations, and stability metrics
- **Trend Identification**: Identify critical population thresholds and tipping points
- **Data Visualization**: Create compelling visualizations for comparative analysis

---

## 👥 Project Team

| Name |
|------|
| Rayane BICABA |
| Lydia BERE |
| Aïda MADIEGA |
| Patricia SILGA |

---

## 📊 Key Findings

### Population Growth Analysis (1960-2023)

- **Burkina Faso Growth**: Experienced explosive population growth of ~391% over 63 years
- **Ghana Growth**: Saw significant expansion of ~211% during the same period
- **Average Populations**: 
  - Burkina Faso: ~11.23 million inhabitants
  - Ghana: ~17.82 million inhabitants

### Stability Metrics (Standard Deviation)

- **Burkina Faso**: 5.6 million (indicating rapid growth acceleration)
- **Ghana**: 8.18 million (showing sustained population expansion)

### Population Doubling Milestones

The analysis identifies when each country's population doubled from its 1960 baseline, revealing the intensity and timing of demographic transitions.

---

## 📁 Project Structure

```
burkinaFasoAndGhanaPopDataAnalysis/
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
├── data/
│   └── population.csv       # World population dataset (1960-2023)
├── notebook/
│   └── FinalTest.ipynb      # Complete analysis notebook with visualizations
└── presentation/
    └── Group4Presentation.pdf
```

---

## 🛠️ Technologies & Tools

- **Python 3.x** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive analysis environment

---

## 📈 Analysis Sections

### 1. Data Importation & Exploration
- Load and inspect the world population dataset
- Overview of data structure (270 rows, 69 columns)

### 2. Data Cleaning
- Remove rows with missing values (NaN)
- Drop irrelevant columns (Indicator Name, Indicator Code)
- Prepare clean dataset for analysis

### 3. Statistical Analysis
- **Growth Rate Calculation**: Measure population expansion from 1960 to 2023
- **Descriptive Statistics**: Compute mean and standard deviation for stability assessment
- **Threshold Analysis**: Identify the year when each country's population doubled

### 4. Data Visualization
- **Line Plot**: Comparative population trends showing growth trajectories
- **Bar Chart**: Population milestones at key years (1960, 1990, 2023)
- **Trend Comparison**: Visual representation of relative growth rates

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/RayaneBICABA/burkinaFasoAndGhanaPopDataAnalysis.git
cd burkinaFasoAndGhanaPopDataAnalysis
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `notebook/FinalTest.ipynb` and run all cells to execute the analysis

---

## 📊 Main Results Summary

| Metric | Burkina Faso | Ghana |
|--------|--------------|-------|
| **1960 Population** | ~3.6 million | ~6.7 million |
| **2023 Population** | ~23.3 million | ~14.1 million |
| **Growth Rate** | +391% | +211% |
| **Average Population** | 11.23 million | 17.82 million |
| **Standard Deviation** | 5.6 million | 8.18 million |

---

## 🔍 Key Insights

✅ **Rapid Demographic Expansion**: Both countries experienced significant population growth, with Burkina Faso showing the highest growth rate.

✅ **Non-linear Growth Pattern**: High standard deviation values indicate accelerating growth rather than steady expansion, reflecting improving healthcare and declining mortality rates.

✅ **Regional Comparison**: Ghana maintained a consistently higher population throughout the 63-year period, suggesting different fertility and migration patterns.

✅ **Population Doubling**: Analysis reveals critical years when each nation's population doubled, providing insight into demographic transition timing.

---

## 📝 Data Source

- **Dataset**: World Bank population data
- **Coverage**: 270 countries/regions, 1960-2023
- **Format**: CSV with annual population figures

---

## 🔗 How to Use This Project

1. **For Research**: Use the statistical findings and visualizations for academic papers or reports
2. **For Learning**: Study the data cleaning and analysis pipeline as a Python/Pandas tutorial
3. **For Replication**: Adapt the methodology to analyze other countries or regions
4. **For Presentation**: Use the generated visualizations in policy discussions or academic presentations

---

## 📌 Notes & Considerations

- Data cleaning removed rows with incomplete information to ensure analysis accuracy
- Population figures represent estimates based on available statistics
- Analysis focuses on long-term trends rather than year-to-year fluctuations
- Standard deviation provides insight into growth acceleration patterns

---

## 👨‍💻 Contributing

This project was completed as a group academic exercise. For inquiries or improvements, please contact the project team.

---

## 📄 License

This project is provided for educational purposes.

---

## 📬 Contact

For questions about this analysis, please reach out to:
- **Email**: rayane.bicaba@example.com

---

**Last Updated**: January 2026  
**Status**: Complete ✓
