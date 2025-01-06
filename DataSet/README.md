# Dataset Information: Amazon Dataset (2018 Version)

This README provides an overview of the dataset used in the study: the **2018 Amazon Dataset** (Ni et al., 2019). This dataset is a comprehensive collection of product reviews and metadata, making it a popular choice for research in natural language processing (NLP), recommendation systems, and sentiment analysis.

---

## Overview of the Dataset

- **Name**: Amazon Dataset (2018 Version)
- **Categories**: 29 distinct categories, including Books, All Beauty, Software, and Video Games.
- **Key Features**:
  - User reviews (ratings, text, helpfulness votes)
  - Product metadata (descriptions, categories)
  - Relational links (e.g., "also viewed" and "also bought" graphs)
- **Files Used**:
  - **Metadata File**: Contains detailed product information (e.g., descriptions, categories, brands, prices).
  - **Rating Only File**: Simplified CSV format with tuples of items, users, ratings, and timestamps.

---

## Why This Dataset?

The **2018 Amazon Dataset** is particularly suitable for recommendation system research due to its:
- **Extensive User-Item Interactions**: Millions of reviews and ratings, enabling robust model development.
- **Diverse Product Categories**: Reflects real-world conditions for accurate and relevant recommendations.
- **Rich Metadata**: Attributes such as 'category,' 'description,' 'title,' 'brand,' and 'feature' enhance content-based and hybrid recommendation models.

---

## Data Utilization in This Study

### Primary Goals:
1. Assess item similarity and diversity.
2. Recommend items aligned with user preferences.

### Key Attributes Analyzed:
- **Category**: Used for grouping and filtering products.
- **Description**: Analyzed with NLP techniques for item features.
- **Title**: Identifies products for recommendation.
- **Brand**: Adds specificity to recommendations.
- **Features**: Enhances the diversity and relevance of recommended bundles.

### Visualization:
- A **bar chart** of the top 100 products was generated to showcase item popularity.
  - **X-Axis**: Product identifiers (Amazon Standard Identification Numbers, ASINs).
  - **Y-Axis**: Customer ratings (ranging from 0 to 8000).

---

## Applications of the Dataset

- **Content-Based Recommendation**: Using metadata for item analysis and ranking.
- **Collaborative Filtering**: Leveraging user-item interactions for recommendations.
- **Hybrid Models**: Combining content-based insights with collaborative filtering for optimal results.

---

## Citation

If you use this dataset, please cite:
Ni, J., Li, J., & McAuley, J. (2019). Justifying recommendations using distantly-labeled reviews and fine-grained aspects. *Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP)*.

---

For further details on dataset preprocessing or usage, pl
the bellow is the link for download: 
https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/