# SmartCart — Recommender System & Pattern Mining

E-commerce recommender using collaborative filtering and association rule mining.

## Requirements
- Python 3.10+
- Install dependencies: `pip install -r requirements.txt`

## Setup
1. Place `ecommerce_user_data.csv` and `product_details.csv` inside a `data/` folder.
2. Open `smartcart_notebook.ipynb` in VS Code (with the Jupyter extension) or run `jupyter notebook` in your terminal.
3. Run all cells top to bottom.

## Outputs
- `outputs/recommendations.csv` — top-N product recommendations per user
- `outputs/association_rules.csv` — generated rules with support, confidence, lift
- `visuals/` — heatmap and itemset charts
