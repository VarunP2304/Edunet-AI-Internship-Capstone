# Edunet-AI-Internship-Capstone

# Employee Burnout Analysis (EBA)

## Overview

The **Employee Burnout Analysis (EBA)** project aims to predict and analyze employee burnout levels based on various workplace factors, such as workload, job satisfaction, and work-life balance. Using machine learning models, the project provides insights into key drivers of burnout, helping organizations take proactive steps to prevent employee burnout and improve well-being.

## Features

- **Burnout Prediction**: Predicts the likelihood of employee burnout based on multiple factors.
- **Key Factors Analysis**: Identifies the most significant factors contributing to burnout, such as workload, job satisfaction, and work-life balance.
- **Performance Metrics**: Includes evaluation metrics like Mean Absolute Error (MAE), R-squared, and others to assess model performance.
- **Data-driven Insights**: Provides actionable insights for HR departments to intervene and manage employee well-being.

## Technologies Used

- **Python**: The primary programming language for data analysis and modeling.
- **Scikit-learn**: For implementing machine learning models like Random Forest Regressor.
- **Pandas & Numpy**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization (e.g., correlation heatmaps, performance plots).
- **Jupyter Notebook**: For interactive code execution and results visualization.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/employee-burnout-analysis.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook to explore the project:
   ```bash
   jupyter notebook
   ```

## Project Structure

```
employee-burnout-analysis/
│
├── data/                  # Dataset folder (ensure you have the data here)
├── notebooks/             # Jupyter notebooks for analysis and model building
├── models/                # Saved models and training scripts
├── requirements.txt       # List of required Python packages
├── README.md              # This file
└── .gitignore             # Git ignore configuration
```

## Model Evaluation

The model's performance is evaluated based on the following metrics:
- **Mean Absolute Error (MAE)**
- **R-squared (R²)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## Future Improvements

- Incorporate real-time data for dynamic burnout prediction.
- Experiment with advanced machine learning models (e.g., Gradient Boosting, Neural Networks).
- Extend the dataset with employee feedback or performance reviews.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project, report issues, or provide suggestions through GitHub Issues or Pull Requests.
