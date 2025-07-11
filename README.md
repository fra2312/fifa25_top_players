\# FIFA 2025 – Top Players (80+ Overall) – EDA & Value Prediction

This project analyzes 480+ top-rated players in FIFA 2025 (Overall 80+) to uncover patterns in player performance, wage vs value gaps, and predict market value using regression models.

\## Dataset

[Kaggle: Top FIFA Players 80+ OVR from Sofifa (2025)](https://www.kaggle.com/datasets/kshitijsingh2k4/top-fifa-players-80-ovr-from-sofifa-with-value)

\## Key Analyses

- Distribution of Overall, Potential, Market Value (€), and Wage (€)
- Identification of overpaid and underpaid players using Value-to-Wage ratio
- Attribute comparison (Age, Stats, Ratings) between underpaid and overpaid profiles
- Correlation matrix of numerical features
- Regression models to predict player value (with and without position encoding)
- Custom player simulation for value estimation

\## Key Insights

- Value and wage distributions are highly right-skewed, with a small group of elite players
- Potential, Wage, and Overall are the top predictors of market value
- Underpaid players tend to be younger with higher potential and better total stats
- Overpaid players are typically older with inflated wages and lower performance
- Regression model with Age, Wage, Overall, and Potential achieves R² ≈ 0.85
- Adding player position (one-hot encoded) improves accuracy to R² ≈ 0.88

\## Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

\## How to Run

1. Download the dataset from Kaggle and save it as `Top\_FIFA\_Players\_2025\_80plus.csv` in a `data/` folder
1. Open the notebook `fifa\_players\_eda.ipynb` inside the `notebook/` directory
1. Install the required Python libraries using:

\```bash

pip install -r requirements.txt
