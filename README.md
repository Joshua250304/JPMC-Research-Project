Quantitative Research Virtual Experience – Forage

This repository contains my solutions and analysis for the Quantitative Research Virtual Experience program. The project focuses on applying mathematical models, statistical analysis, and machine learning to solve real-world financial problems, such as commodity pricing and credit risk assessment.

📊 Project Overview

The simulation involved working as a Quantitative Analyst to support a commodities trading desk and a credit risk department. The core objective was to transform raw financial data into predictive models that inform high-stakes decision-making.

🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
Tools: Jupyter Notebooks, Excel


📝 Task Summaries


1. Natural Gas Price Analysis & Forecasting
   
Goal: Analyze historical natural gas prices and develop a model to estimate prices at any given date.

Key Actions: * Cleaned and visualized monthly price data to identify seasonal trends (winter peaks vs. summer troughs).
               Implemented an extrapolation model to forecast prices for future contractual dates.

Skills: Time-series analysis, Data Preprocessing, Linear Regression


2. Credit Risk: Probability of Default (PD)

Goal: Calculate the likelihood of a borrower defaulting on a loan.

Key Actions:Processed a dataset of borrower characteristics (income, loan amount, etc.).
            Identified correlations between financial ratios and historical defaults.
            Calculated the expected loss by modeling the $Probability of Default$ ($PD$).
            
Skills: Statistical Modeling, Exploratory Data Analysis (EDA)

3. Machine Learning: Decision Tree Classifier
   
Goal: Automate the credit classification process.

Key Actions:Built a Decision Tree model to categorize borrowers into "High Risk" or "Low Risk."
            Split data into training and testing sets to validate model accuracy.
            Visualized the tree to ensure the decision logic aligned with financial intuition.

Skills: Supervised Learning, Model Evaluation, Scikit-Learn.

4. Data Quantization & Optimization
   
Goal: Improve model interpretability by "bucketizing" continuous variables.

Key Actions:Developed an algorithm to discretize continuous data (like credit scores) into optimal buckets.
            Used log-likelihood and entropy measures to find the most efficient breakpoints.
            Optimized data structures for better performance in larger risk models.

Skills: Optimization Algorithms, Feature Engineering, Algorithmic Thinking.
