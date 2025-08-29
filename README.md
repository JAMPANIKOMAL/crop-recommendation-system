# AI-Based Crop Recommendation System

A data science project to recommend the optimal crop for a given set of soil and weather conditions, inspired by a problem statement from the Smart India Hackathon (SIH).

## Project Vision

This project addresses the Smart India Hackathon problem statement SIH25030: "AI-Based Crop Recommendation for Farmers." By providing data-driven advice, it aims to help farmers increase yield, improve profitability, and support national food security.

The main objective is to develop a machine learning model that analyzes key agricultural parameters—such as soil nutrient levels, temperature, humidity, and rainfall—to classify and recommend the most suitable crop. This serves as a proof-of-concept for a real-world agricultural advisory tool.

## Core Features

- **Realistic Synthetic Data:** Custom-generated dataset simulating real-world soil and climate data for various crops.
- **Predictive Modeling:** Classification model recommends the best crop based on input data.
- **Feature Importance Analysis:** Highlights the most significant environmental factors for crop prediction.
- **Clear Visualizations:** Presents model performance using confusion matrices and other relevant plots.

## Technology Stack

- **Language:** Python 3
- **Data Science & ML:** pandas, scikit-learn, numpy
- **Data Visualization:** matplotlib, seaborn
- **Development Environment:** Python scripts (runnable from any IDE or terminal)

## Project Structure

The analysis is organized into four sequential Python scripts:

1. **01_data_generation.py:** Creates and explores the synthetic dataset of agricultural conditions and optimal crops.
2. **02_data_preprocessing.py:** Cleans, encodes, and prepares the data for machine learning.
3. **03_model_development.py:** Trains and evaluates several classification models to identify the best performer.
4. **04_results_visualization.py:** Visualizes results, including model accuracy for each crop and key predictive factors.

## How to Run

1. Ensure Python and the required libraries are installed (`pip install -r requirements.txt`).
2. Run the scripts in numerical order from your terminal or IDE, starting with `01_data_generation.py`.

## Acknowledgement

This project was developed with the assistance of Gemini, a large language model from Google, which contributed to dataset generation, workflow structuring, and documentation.
