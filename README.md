# Recommender Systems Project 1 - Content Based Recommender

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2022

Author: [Mateusz Walas](https://github.com/Matraf)

Lecturer: [Piotr Zioło](https://github.com/PiotrZiolo)

## 1. Description

The aim of the project was to implement content-based recommender and train it using different machine learning algorithms.

## 2. Requirements

Requirements are ```environment.yml```. To run enter following commands:
```bash
conda env create --name rs-class-env -f environment.yml
conda activate rs-class-env
```

## 3. Overall score 

| Recommender                     | Score                  |
|:--------------------------------|:-----------------------| 
| LinearRegressionCBUIRecommender | Memory Error after 16h | 
| SVRCBUIRecommender              | None                   |
| RandomForestCBUIRecommender     | None                   |
| XGBoostCBUIRecommender          | None                   |
| AmazonRecommender               | None                   |

Due to bad implementation it was too time and memoryconsuming to train my recommender with different ML algorithms. 