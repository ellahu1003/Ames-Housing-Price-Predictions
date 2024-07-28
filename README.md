# Ames-Housing-Price-Predictions

## Project Overview
This project focuses on predicting residential property prices in Ames, Iowa using multiple linear regression models. The aim is to utilise data cleaning, exploratory data analysis (EDA), and model evaluation to provide insights that can optimize real estate sales strategies.

## Technologies Used
1) Python
2) Pandas
3) NumPy
3) Scikit-Learn
4) Matplotlib
5) Seaborn

## Dataset
The dataset used for this project is 'ames.csv', which contains detailed information about various residential properties in Ames, Iowa.

## Setup and Installation
1) Clone the repository:
   ```bash
    git clone https://github.com/ellahu1003/ames-housing-price-prediction.git
    cd ames-housing-price-prediction
    ```
2) Install the required packages:
   ```bash
    pip install -r requirements.txt
    ```
3) Run the Jupyter Notebook:
   ```bash
    jupyter notebook notebook/Linear_Regression_Ames.ipynb
    ```
## Project Structure
```markdown
ames-housing-price-prediction/
│
├── data/
│ └── ames.csv
│
├── notebook/
│ └── Linear_Regression_Ames.ipynb
│
├── results/
│ ├── ground_living_area_vs_sale_price.png
│ ├── garage_area_vs_sale_price.png
│ └── error_bars_plot.png
│
└── requirements.txt
```

## Requirements
The `Requirements.txt` file lists all the Python packages required to run the project. Install these dependencies to avoid any compatibility issues.

## Results
1) MSE: [2835241787.28]
2) Relationship between variables and Model performance insights are visualised in ground_living_area_vs_sale_price.png, garage_area_vs_sale_price.png and error_bars_plot.

## Conclusion
1) The relationship between ground living area (in square feet) and sale price, as well as the relationship between garage area and sale price, shows positive correlations. The correlation between ground living area and sale price is stronger.
2) The MSE value is large, but considering the sale price range (hundreds of thousands), this may not be a major concern.
3) The error bar plots show that most predicted values are close to the true values, though predictions for outliers are further off.
