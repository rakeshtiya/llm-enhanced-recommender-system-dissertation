# llm-enhanced-recommender-system-dissertation

# LLM-Enhanced Recommender System for Customer Engagement Analysis

## Project Overview
This project investigates how traditional recommender systems can be enhanced using textual analysis and Large Language Models (LLMs) to improve customer engagement insights, explainability, and ethical transparency. The study is conducted as part of a Master’s dissertation in Business Analytics and focuses on bridging predictive performance with managerial interpretability.

The system is evaluated using multiple analytical stages, including recommendation accuracy, engagement classification, time-series forecasting, and LLM-based explanation generation.

---

## Dataset Description
The project uses the **Amazon Movies and TV Reviews dataset**, which contains user–item interactions, textual reviews, ratings, and timestamps.

Due to dataset size and licensing constraints, raw data files are not included in this repository. All data preprocessing, filtering, and feature engineering steps are fully documented in the notebooks.

---

## Methodology
The project follows a multi-stage analytical pipeline:

1. Exploratory Data Analysis (EDA) to understand user behaviour and item characteristics  
2. Baseline recommendation using popularity-based models  
3. Text-enhanced recommendation using TF-IDF similarity on review text  
4. Customer engagement modelling using binary classification  
5. Time-series forecasting to analyse engagement trends over time  
6. LLM-based generation of natural language explanations for recommendations  
7. Evaluation of explainability, diversity, and ethical risk

---

## Repository Structure

LLM_RECSYS_DISSERTATION/
├── notebooks/ # Jupyter notebooks (numbered in execution order)
├── src/ # Reusable Python scripts and pipeline code
├── data/ # Dataset descriptions and placeholders
├── models/ # Trained model artefacts
├── results/ # Evaluation outputs and summary tables
├── figures/ # Plots and visual outputs
├── ethics/ # Ethical analysis and LLM risk notes
├── writing/ # Dissertation-related drafts (if applicable)
├── requirements.txt # Python dependencies
└── README.md


---

## How to Run the Project

### Option 1: Run individual notebooks
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

or 

python src/run_dissertation_pipeline.py
