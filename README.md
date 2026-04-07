# GlowGuide - Cosmetic Recommendation System using Ingredient Analysis

## Live Demo
https://aiswarya0109.github.io/Analysis_of_Chemical_Components/cosmetic_dashboard.html

## Project Overview
An interactive data analytics dashboard that analyzes 1,472 Sephora cosmetic products using machine learning and data visualization. The dashboard helps users find the right skincare products based on ingredients, budget, and skin concerns.

## Features
- **Ingredient Similarity Map** - t-SNE scatter plot showing products clustered by ingredient similarity
- **Search Highlight** - Type any brand or product to highlight matching dots on the map
- **Analytics Charts** - Top brands, price distribution, rating distribution, top ingredients
- **Ingredient Intelligence** - Top products by beneficial ingredients, brand overlap heatmap
- **Ingredient Comparison** - Select 2 products and compare shared vs unique ingredients
- **Budget Finder** - Find the best products within your budget ranked by ingredient score
- **Recommendation Engine** - Get personalized recommendations based on skin concerns
- **Dupes Finder** - Find similar products with ingredient similarity percentage

## Tech Stack
- **Python** - Data processing and analysis
- **Pandas & NumPy** - Data manipulation
- **Scikit-learn** - t-SNE dimensionality reduction, cosine similarity
- **Chart.js** - Interactive charts
- **HTML/CSS/JavaScript** - Frontend dashboard
- **GitHub Pages** - Deployment

## Dataset
- Source: Sephora via Kaggle
- 1,472 cosmetic products
- 190 moisturizers analyzed for dry skin
- 2,233 unique ingredients

## How It Works
1. Ingredients are tokenized and converted into a document-term matrix
2. t-SNE reduces the high-dimensional matrix to 2D for visualization
3. Products close together on the map share similar ingredients
4. Cosine similarity is used to find ingredient-based product recommendations

