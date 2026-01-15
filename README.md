SkinMatch: Data-Driven Skincare Product Analysis & Recommendation

SkinMatch is a data science project that explores how skincare product ingredients, pricing, and claimed effects relate to product ratings and skin-type suitability.

The project builds a clean analytical pipeline and a lightweight recommendation prototype to support transparent, data-driven skincare decision-making.

Project Motivation:
Skincare consumers often face information overload: long ingredient lists, vague marketing claims, and large price differences with unclear justification.

This project aims to answer:
How do skincare prices vary across product categories and claimed effects?

Are higher prices associated with higher user ratings?

Can ingredient- and feature-based analysis support basic skincare recommendations?

Rather than treating skincare as a black box, SkinMatch emphasizes interpretability, structured data processing, and reproducibility.

Dataset:
Source: Kaggle skincare products dataset
Size: 1,472 products × 11 core features
Key attributes: Brand, product name, price, rating
Ingredient lists
Skin-type suitability labels (Dry, Oily, Sensitive, etc.)
Product category (e.g., moisturizer, cleanser)

Data Processing Pipeline:
1. Data Cleaning:
Standardized text fields and column names
Removed duplicates and invalid entries
Ensured consistent data types and completeness
After cleaning, all 1,472 products were retained with no missing values.

2. Feature Engineering:
Derived interpretable features including:
Ingredient count per product
Primary skincare effect indicators
Binary skin-type compatibility features
These features enable analysis beyond raw product metadata.

3. Analytical Data Mart:
A focused data mart was constructed to isolate variables relevant to:
Pricing
Ratings
Product categories
Skin-type suitability
This structure improves clarity, reusability, and downstream analysis.

Exploratory Analysis:
Key analytical insights include:
Anti-aging products tend to have higher median prices than other categories
Higher prices do not consistently imply higher user ratings
Certain skincare effects show tighter price distributions, suggesting market standardization
Visualizations are provided in the analysis notebook to support these findings.

Recommendation Prototype:
A simple rule-based recommendation function selects top-rated products that match a given skin type.  
This prototype demonstrates how analytical insights can be translated into a user-facing decision-support tool.

Future Work:
Planned extensions include:
Ingredient embedding and similarity-based recommendations
Review-based sentiment analysis
Interactive web interface for personalized skincare exploration
Machine learning models for preference-aware recommendations

Skills & Tools Demonstrated:
Python (pandas, numpy, matplotlib)
Data cleaning & feature engineering
Exploratory data analysis (EDA)
Modular code design
Reproducible analytical workflows

Author:
Runlin Liu
Applied and Computational Mathematics @ USC
Interests: Data Science, Applied Analytics, AI-driven consumer insights
