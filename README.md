# Movie Data Mining & Performance Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/) [![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3%2B-orange)](https://scikit-learn.org/)

[![GitHub Repo stars](https://img.shields.io/github/stars/its-Pratik-15/movie-trends?style=social)](https://github.com/its-Pratik-15/movie-trends)

**Analyzes 7,668 movies using decision tree classification (72.4% test accuracy), Apriori association rules, and content-based recommendations to predict movie performance and uncover success patterns.**[file:1]

## 🎯 Project Overview
Movie industry stakeholders need data-driven insights for investment decisions and content strategy. This project:
- **Classifies** movies into performance categories (Flop, Hit, Blockbuster)
- **Discovers** association rules linking budget, talent, and outcomes
- **Recommends** similar movies using engineered features[file:1]

## 📊 Table of Contents
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Repository Structure](#repository-structure)
- [Demo](#demo)
- [Paper](#paper)
- [Contributing](#contributing)

## ✨ Features
- **Decision Tree Classifier** (72.4% test accuracy on balanced classes)
- **Apriori Association Rules** (e.g., "Low Budget + Medium Director → Blockbuster, Lift=6.36")
- **Content-Based Recommendations** (cosine similarity on feature vectors)
- **Feature Engineering**: Profit ratio, budget tiers, actor/director success scores
- **EDA Visualizations**: Budget-revenue correlation, genre distribution, ROI trends
- **Class Balancing** for stable model performance[file:1]

## 📦 Dataset
| Dataset | Source | Size | Years |
|---------|--------|------|-------|
| **Movies Dataset** | [Kaggle: Daniel Grijalvas](https://www.kaggle.com/datasets/danielgrijalvas/movies) | 7,668 movies | 1986-2016 |[web:3][file:1]

**Required**: Download `movies.csv` (16MB) → `data/raw/`

**Key Columns**: `budget`, `gross`, `rating`, `genre`, `runtime`, `leadactor`, `director`, `production_company`

**License**: CC0: Public Domain

