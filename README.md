# rainfall-prediction-MajorProject

## Abstract
Predicting heavy rainfall events is crucial for disaster preparedness and agricultural planning, particularly in regions like India, where agriculture is vital to the economy. Traditional statistical methods often fall short in forecasting due to the dynamic nature of the atmosphere. This project applies machine learning (ML) techniques to address the nonlinearity of rainfall data, utilizing historical data from the Indian Meteorological Department (1901-2015). We evaluate the performance of five ML algorithms: Linear Regression, Lasso Regression, Ridge Regression, SVM, and Random Forest. The project also aims to create a user-friendly webpage interface to provide rainfall predictions for specific regions and timeframes

## Key Points
1. **Objective:** Improve rainfall prediction accuracy for India, focusing on Karnataka's three regions: coastal, north interior, and south interior Karnataka.
2. **Importance:** Accurate rainfall prediction is essential for water resource management, agriculture, and disaster preparedness, especially in India.
3. **Data Source:** Historical rainfall data (1901-2015) from the Indian Meteorological Department (IMD) for 36 subdivisions.
4. **Tools Used:**
- Python, Jupyter Notebook for model development and data visualization.
- Microsoft Excel for handling the dataset.
- Visual Studio Code, HTML, CSS for web interface development.
5. **ML Models:**
- Linear Regression, Ridge Regression, Lasso Regression, Support Vector Machine (SVM), Random Forest.
- Random Forest was the best-performing model with MAE: 34.13 mm, RMSE: 48.41 mm.
6. **Process:**
- Data preprocessing to handle missing values, inconsistencies, and outliers.
- Training/testing split: 70-30 ratio.
- Visualization techniques used to understand data and assess model performance.
7. **Results:** Developed a user-friendly web interface allowing users to select subdivisions, months, and years for rainfall predictions.
8. **Accuracy:** Best-fit curve with R-squared value of 0.7969, indicating strong prediction accuracy for the region.
