# Overview
This project uses a dataset of 3,276 water samples to understand 
what chemical parameters affect whether water is safe to drink.

# Dataset
- 3,276 water samples
- 9 chemical parameters: pH, Hardness, Solids, Chloramines, 
  Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity
- Target variable: Potability (1 = drinkable, 0 = not drinkable)

# What I Did
- Loaded and explored the dataset using Pandas
- Handled missing values by filling with column means
- Visualized pH distribution across all samples
- Built a correlation heatmap to find relationships between parameters
- Compared key parameters between drinkable and non-drinkable samples

# Key Findings
- Only 39% of water samples in this dataset are drinkable
- No single chemical parameter strongly determines potability
- Correlation values between all parameters and potability stayed 
  below 0.04, suggesting water safety depends on the combination 
  of multiple factors rather than only one measurement

# Tools
Python · Pandas · Seaborn · Matplotlib · Jupyter Notebook
