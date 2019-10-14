# steam-machine-learning

# Description

A machine learning project using data about 27,000 Steam games.

The objective is to predict whether a game has many/few ratings based on its other attributes. I got the model to predict with ~80% accuracy.

I started this project because I wanted to try a binary classification problem with all binarized data.

# Jupyter Notebooks

[steam_clean_data.ipynb](steam_clean_data.ipynb): prepares data to be fed into the models

[steam_models.ipynb](steam_models.ipynb): evaluates a handful of models then tunes RFC

# Data Sources

[steam.csv](steam.csv): https://www.kaggle.com/nikdavis/steam-store-games

[top-dev-pub.csv](top-dev-pub.csv): https://steam250.com/developer and https://steam250.com/publisher (retrieved on 08/19/2019)

[steam-cleaned.csv](steam-cleaned.csv): self-cleaned data using steam.csv

# Visualizations

[visualizations](visualizations): provides larger versions of graphs that got obscured in steam_clean_data.ipynb 

Note: [achievements_vs_total_ratings.png](visualizations/achievements_vs_total_ratings.png) & [owners_mid_vs_total_ratings.png](visualizations/owners_mid_vs_total_ratings.png) show only a part of the full graph to demonstrate a point;
[low_price_vs_total_ratings.png](visualizations/low_price_vs_total_ratings.png) & [high_price_vs_total_ratings.png](visualizations/high_price_vs_total_ratings.png) show 2 parts of the graph to demonstrate a point. For these graphs, the range of data on the x-axis is so big that including the whole graph would obscure the labels.
