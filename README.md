# SmartCart - Recommender System & Pattern Mining

E-commerce recommender using collaborative filtering and association rule mining.

## Requirements
- Python 3.10+
- Create a virtual environment: `python -m venv .venv`
- Install dependencies: `pip install -r requirements.txt`

## Setup
1. Place `ecommerce_user_data.csv` and `product_details.csv` inside the `data/` folder.
2. Open [project_notebook.ipynb] in VS Code or Jupyter.
3. Run the notebook cells from top to bottom.

## Outputs
- `visuals/user_similarity_heatmap.png` - user similarity heatmap
- `visuals/group_top5_recommendations.csv` - top-5 recommendations aggregated by user group
- `visuals/group_top5_recommendations.png` - grouped recommendation chart
- `visuals/frequent_itemsets_barchart.png` - frequent itemsets bar chart
- `visuals/association_rules_scatter.png` - association rules scatter plot
- `visuals/association_rules_barchart.png` - association rules bar chart
- `association_rules.csv` - exported association rules table
