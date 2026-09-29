# Content-Based Movie Recommendation System

A machine-learning project that recommends movies with similar content profiles using the **MovieLens Small dataset**, genre features, and cosine similarity.

## Objective

Build an interpretable recommendation pipeline that can return movies similar to a selected title based on genre information.

## Dataset

The project uses the **MovieLens Small Dataset**, including:

- `movies.csv`
- `ratings.csv`

## Method

The recommendation workflow is:

1. Load and inspect the movie data
2. Prepare genre information
3. Convert movie genres into numerical vectors using **CountVectorizer**
4. Compute pairwise similarity using **cosine similarity**
5. Rank movies by similarity to the selected title
6. Return the most relevant recommendations

## Core Techniques

- Content-based recommendation
- Text/vector feature representation
- CountVectorizer
- Cosine similarity
- Ranking and retrieval

## Example

**Input:** `Toy Story (1995)`

**Output:** movies with similar genre characteristics, particularly animated and family-oriented titles.

## Why This Project Matters

Recommendation systems are widely used in streaming, e-commerce, news, and content platforms. This project demonstrates the core idea behind content-based retrieval in a simple and interpretable form.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Repository Structure

```text
04-AI-Based-Recommendation-System/
├── data/
├── images/
├── notebooks/
├── outputs/
├── reports/
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

## Skills Demonstrated

- Recommendation systems
- Feature representation
- Similarity-based retrieval
- Data preprocessing
- Machine-learning workflow design
- Business-oriented problem framing

## Limitations

The current system is content-based and primarily relies on genre information. It does not yet learn individual user preferences from interaction history.

## Future Improvements

- Collaborative filtering
- Matrix factorization
- Hybrid recommendation
- User-personalized ranking
- Richer metadata such as tags and descriptions
- Offline recommendation metrics
- Recommendation API or interactive interface

---

**Author:** Manan Paliwal  
B.Tech Computer Science Engineering — Artificial Intelligence & Machine Learning
