# Hi, I'm Sai Chetan Reddy

### Computer Science Graduate (Artificial Intelligence) | AI/ML | Data Analytics | Backend Development

Computer Science graduate specializing in Artificial Intelligence, with hands-on experience building end-to-end AI, machine learning, backend, and data analytics applications. I work with Python, SQL, FastAPI, LLMs, Retrieval-Augmented Generation (RAG), and data engineering pipelines to build scalable, data-driven software.

---

# Featured Projects

## PokéDex AI — RAG Question Answering & Recommendation System

A local Pokémon assistant that answers questions with Retrieval-Augmented Generation and ranks Pokémon, builds teams, and analyzes teams from structured data.

### Highlights

- Indexed 1,576 documents (151 Pokémon, 592 moves, 78 evolution chains) from PokéAPI in ChromaDB
- Manual retrieval pipeline: query parsing, metadata filtering with semantic-search fallback, and context-grounded prompting across 8 document types
- Semantic search with SentenceTransformers (`all-MiniLM-L6-v2`) and local inference with Phi-3 via Ollama
- Recommender, team builder, and team analyzer with LLM explanations and a rule-based fallback
- FastAPI REST backend with a 4-tab Gradio interface

### Tech Stack

`Python` `FastAPI` `ChromaDB` `SentenceTransformers` `Ollama` `Phi-3` `LangChain` `Gradio` `Pydantic` `Pandas`

**Repository:** https://github.com/saichetanreddy07/pokedex-ai-rag

---

## Meta-Learning Framework for Automated Time-Series Model Selection

A meta-learning framework that extracts statistical features from a time series and recommends whether ARIMA or Prophet will forecast it more accurately, without fitting both models.

### Highlights

- Extracted 10 statistical meta-features (ADF statistic, lag-1 autocorrelation, trend slope, and more)
- Compared ARIMA(1,1,1) and Prophet on 1,359 M4 benchmark series (Monthly, Yearly, Weekly) using RMSE
- Trained a Random Forest meta-classifier with 69.12% holdout accuracy
- Streamlit app for batch CSV inference with confidence scores and interactive holdout validation

### Tech Stack

`Python` `Scikit-learn` `Pandas` `NumPy` `Statsmodels` `Prophet` `Streamlit`

**Repository:** https://github.com/saichetanreddy07/Meta-Learning-Time-Series-Forecasting

---

## Enterprise SQL Analytics & Business Intelligence Platform

An end-to-end BI platform covering ETL, a normalized PostgreSQL model, SQL analytics, and an interactive Power BI report.

### Highlights

- Python ETL pipeline that samples, cleans, and validates a 5+ GB e-commerce events dataset (309,967 sampled records)
- Normalized 4-table PostgreSQL schema (categories, products, users, events)
- 39 numbered business questions in SQL, including window functions (ranking, running totals, moving averages, `LAG`)
- 4-page Power BI dashboard: executive, customer, product/category, and conversion analytics

### Tech Stack

`Python` `SQL` `PostgreSQL` `Power BI` `Pandas`

**Repository:** https://github.com/saichetanreddy07/ecommerce-sql-bi-platform

---

## RestaurantAI — Restaurant Operations & Inventory Management System 🚧 *In Progress*

A backend system for restaurant operations, covering inventory lot tracking, automated ingredient consumption, and real-time dish availability. The backend is built; the React frontend is under active development.

### Highlights

- Layered FastAPI backend with SQLAlchemy 2.0, MySQL, and Alembic migrations
- FEFO (First-Expiring, First-Out) consumption engine with atomic, all-or-nothing deductions across batches
- Immutable audit ledger for every stock movement
- Real-time availability engine that finds bottleneck ingredients and avoids N+1 queries
- Pydantic v2 validation and a Pytest suite
- **Currently building:** React 19 + TypeScript dashboard (Vite, Tailwind, React Query)

### Tech Stack

`Python` `FastAPI` `SQLAlchemy` `MySQL` `Alembic` `Pydantic` `React` `TypeScript`

**Repository:** https://github.com/saichetanreddy07/Restaurant-AI

---

# Technical Skills

## Languages
`Python` `Java` `SQL`

## AI & LLMs
`Large Language Models (LLMs)` `Retrieval-Augmented Generation (RAG)` `LangChain` `Prompt Engineering` `Semantic Search` `Vector Databases`

## Machine Learning
`Scikit-learn` `Time-Series Forecasting` `Feature Engineering` `Model Evaluation`

## Backend
`FastAPI` `REST APIs` `SQLAlchemy` `Pydantic`

## Data Analytics
`Pandas` `NumPy` `ETL` `Data Cleaning` `Data Validation` `Power BI` `Tableau` `Matplotlib`

## Databases
`MySQL` `PostgreSQL` `ChromaDB`

## Tools
`Git` `GitHub` `VS Code` `PyCharm` `Jupyter Notebook` `Gradio` `Streamlit` `Ollama`

---

# Certifications

- IBM Data Science Professional Certificate
- Google Data Analytics Professional Certificate
- AWS Data Engineering (Foundations)
- Java Programming: Solving Problems with Software

---

# Connect

**Email:** badvel.saichetanreddy@gmail.com
**LinkedIn:** https://www.linkedin.com/in/sai-chetan-reddy-a18b4624b/
**GitHub:** https://github.com/saichetanreddy07

---

Thank you for visiting my profile. Feel free to explore my repositories and connect with me.
