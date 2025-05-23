# Airbnb Occupancy Optimization Using Python
Predictive modeling and clustering to help Airbnb hosts improve occupancy and revenue


## Project Overview
**Premium Program for Airbnb Hosts**  
This project aimed to help Airbnb hosts maximize revenue by **predicting occupancy rates** and offering **actionable listing optimizations** based on pricing tier and feature analysis. 

Using **K-Means clustering**, listings were segmented into low, medium, and high nightly rate groups. For each cluster, we built **custom Gradient Boosting Tree models** to predict occupancy, achieving up to **R² = 0.9977**.

Our Premium Program identifies the most impactful listing features (e.g., superhost status, cleaning fees, pets allowed) and simulates the revenue impact of feature changes. One test case showed **occupancy rising from 5% to 45%** after targeted feature adjustments.

## Tech Stack
- Python (Pandas, scikit-learn, XGBoost, matplotlib)
- Jupyter Notebooks
- K-Means Clustering
- Gradient Boosting Regression

## Modeling Highlights

### Clustering
- **K-Means (k=3)**: Clustered listings into Low (~$119), Medium (~$342), and High (~$873) nightly rates
- Segmentation helped model listings with similar price sensitivity separately

### Feature Engineering
- Superhost history, booking patterns, review trends, demographic indicators, pets policy, and cleaning fees
- Created interaction variables and selected features via Lasso

### Predictive Models
- Built **Gradient Boosting Tree regressors** per cluster
- R² Scores:
  - Low: 0.9977
  - Medium: 0.9968
  - High: 0.9591

## Key Insights
- Superhost status and pet-friendliness strongly improve occupancy
- Cleaning fee and availability also have tier-specific impact
- Hosts in all segments can benefit from data-informed feature optimization
- Feature adjustments led to a **40% increase in predicted occupancy** in a real-world test scenario

##  Repository Structure
- `model `: Including three clusters modeling with low, medium, and high night rate
- `data`: Using the Airbnb dataset from the Washington region ( the dataset is too large to upload)
- `report `: Including the presentation slide and summary report

---
📍 Oct 2024 – Jan 2025  
🏫 Purdue University Daniels School of Business


