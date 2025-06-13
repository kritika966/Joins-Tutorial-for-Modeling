# Tutorial: How to Join Datasets for Modeling (and How to Avoid Common Mistakes)
Example: Home Credit Default Risk Dataset (Kaggle)
Target audience: Data Science / Machine Learning students
Skill level: Beginner to Intermediate

## Overview
This tutorial teaches you how to safely and effectively join multiple datasets to prepare them for machine learning modeling.
It is based on the popular Home Credit Default Risk dataset from Kaggle, which contains multiple related tables — a perfect real-world scenario.

**You will learn:**

- Types of SQL/Pandas joins and when to use them
  
- What is a mutating join and how to avoid it
  
- How to handle 1-to-many relationships correctly
  
- How to prepare a clean modeling dataset with no row duplication
  
- Best practices for building efficient and correct join queries

## Dataset Structure
| File                    | Description                                             |
| ----------------------- | ------------------------------------------------------- |
| `application_train.csv` | Main modeling table (1 row per client)                  |
| `bureau.csv`            | Client’s external credit history (many rows per client) |


## What You'll Implement

- Understand row cardinality between tables

- Use LEFT JOIN and INNER JOIN appropriately

- Aggregate child table features (bureau) before joining

- Build a final dataset suitable for ML: 1 row per client

- Check for row duplication and avoid common pitfalls

## Tutorial Flow
1- Intro to joins and why they matter in ML

2- Types of joins and when to use each

3- Deep dive: mutating joins — the #1 mistake

4️- Safe pattern: Aggregate → LEFT JOIN → Sanity check

5️- Example with application_train.csv + bureau.csv

6- Final best practices and key takeaways

## Key Learning Outcome

**By the end of this tutorial, you will know:**

- How to think about joins and row cardinality

- How to design join queries safely for any ML project

- How to avoid common mistakes that lead to bad models

- How to write clean, efficient, production-ready joins

- Prerequisites

- Basic knowledge of Python & pandas

- Familiarity with SQL joins concepts helpful but not required

## How to Run
# Clone the repo / download the notebook
# Run the notebook in Jupyter or Colab









