\# FIFA 2025 – Top Players (80+ Overall) – EDA & Value Prediction

This project analyzes 480+ top-rated players in FIFA 2025 (Overall 80+) to uncover trends in performance, wage-value imbalances, and predict market value using regression models.

\## Dataset

Kaggle: [Top FIFA Players 80+ OVR from Sofifa (2025)](https://www.kaggle.com/datasets/kshitijsingh2k4/top-fifa-players-80-ovr-from-sofifa-with-value)

\## Key Analyses

- Distribution of Overall, Potential, Market Value (€), and Wage (€)
- Identification of overpaid and underpaid players using Value-to-Wage ratio
- Attribute comparison between underpaid and overpaid profiles
- Correlation matrix across key numeric features
- Value prediction via linear regression (with and without position encoding)
- Custom player simulation for market value estimation

\## Key Insights

- Value and wage distributions are highly right-skewed, with a small group of elite players
- Potential, Wage, and Overall are the strongest predictors of market value
- Underpaid players tend to be younger with higher potential and better total stats
- Overpaid players are typically older with inflated wages and lower performance
- Linear regression using Age, Wage, Overall, and Potential achieves R² ≈ 0.85
- Adding player position (one-hot encoded) improves accuracy to R² ≈ 0.88

\## Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

\## How to Run

1. Download the dataset from Kaggle and place it in a folder named `data/` as `Top\_FIFA\_Players\_2025\_80plus.csv`
1. Open the notebook `fifa\_players\_eda.ipynb` inside the `notebook/` folder
1. Install required libraries with:

\```bash

pip install -r requirements.txt
