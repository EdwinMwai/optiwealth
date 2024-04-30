# OPTI_WEALTH

# Stock Portfolio Recommendation based on Risk Tolerance and Cash Compounding

## Authors:
- Fanice Andayi
- Jimmy Mumo
- Kevin Riungu
- Phyllis Kiruki
- Cynthia Chelangat
- Edwin Mwai

## Background of the Industry:
The investment landscape has evolved significantly over the years, driven by advancements in technology, changing market dynamics, and shifting investor preferences. Traditional investment approaches often relied on static asset allocation strategies that did not adapt to individual risk profiles or market conditions. However, with the advent of data analytics, machine learning, and financial modeling techniques, there is a growing opportunity to provide personalized investment advice tailored to investors' unique needs.

## Introduction:
In a world where data and algorithms drive financial decisions, envision having a personalized financial advisor at your fingertips. Instead of a magic wand, this system harnesses the power of data and algorithms to craft investment recommendations tailored specifically to you. Imagine inputting your risk tolerance and investment objectives, and presto! You receive customized portfolio suggestions designed not only to maximize returns but also to incorporate compounding strategies for long-term wealth growth. It's akin to having a financial genie fulfilling your wishes, but in the language of data and analytics!

## Problem Statement:
### Prevailing Circumstance:
Currently, many investors lack access to personalized investment advice tailored to their risk tolerance levels and financial objectives. They often resort to generic investment strategies that may not align with their individual needs, leading to potential underperformance or excessive risk exposure.
### Problem We're Trying to Solve:
Our project aims to address this gap by developing an intelligent recommendation system that leverages machine learning algorithms and financial modeling techniques to provide personalized portfolio recommendations. By considering an investor's risk tolerance, investment horizon, and market conditions, we aim to optimize portfolio allocations and compounding strategies to maximize returns while mitigating risk.
### How the Project Aims to Solve the Problem:
Through data-driven analysis and advanced algorithms, our project seeks to empower investors with actionable insights that align with their unique financial goals and risk preferences. By harnessing historical stock price data, financial statements, and market indices, we aim to build a robust recommendation system capable of dynamically adjusting portfolio allocations and compounding strategies to optimize long-term wealth accumulation.

## Objectives:
### Main Objective:
The primary goal is to create a tailored recommendation system that enhances portfolio allocations and compounding strategies by considering individual risk tolerances and investment timelines.
### Specific Objectives:
1. Employ machine learning algorithms to evaluate historical stock prices, financial records, and market indicators for risk assessment and the identification of appropriate investment prospects.
2. Create adaptive portfolio optimization methods that modify asset distributions according to evolving market dynamics and individual choices.
3. Integrate compounding tactics to optimize wealth growth over time and boost portfolio returns.

## Notebook Structure:
1. Business Understanding
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Preparation
6. Modeling
7. Evaluation
8. Conclusion, Recommendations, and Next Steps

## Business Understanding:
As a prominent financial services provider in Kenya, we understand the crucial role of guiding clients towards informed investment decisions in a complex and volatile market setting. Clients seek tailored investment advice aligned with their financial objectives, risk preferences, and investment timelines. To meet these demands, our goal is to develop an advanced Stock Portfolio Recommendation System utilizing machine learning algorithms to analyze market data and optimize portfolio allocations. By integrating compounding strategies and dynamic optimization techniques, we aim to enhance long-term wealth accumulation for clients while fostering trust and loyalty. This initiative reflects our dedication to innovation, client-centricity, and market leadership in the financial services sector.

## Stakeholders:
- Investors: Individuals in search of personalized investment guidance tailored to their risk tolerance and financial goals.
- Financial Advisors: Professionals seeking to strengthen client relationships by providing sophisticated portfolio recommendations based on data-driven insights.
- Financial Institutions: Entities aiming to set themselves apart and attract clients through innovative investment solutions.

## Metrics of Success:
- Portfolio Return vs. Benchmark: Targeting a 3% annual outperformance against a relevant benchmark like the S&P 500.
- Risk-adjusted Returns: Aiming for a Sharpe ratio exceeding 0.8 to ensure superior risk-adjusted performance compared to the benchmark.
- Portfolio Diversification: Ensuring that at least 90% of portfolios meet diversification standards by being well-spread across various asset classes and industries.

## Data Understanding:
1. **Data Source:** The dataset used for this project is obtained from Yahoo Finance through web scraping. It contains historical stock market data for the top 10 companies listed on the Nasdaq exchange.
2. **Data Size:** The dataset consists of 54,801 instances, each with 7 features. Each row represents the stock market data for a specific company on a given date. The features include 'Ticker', 'Date', 'Close/Last', 'Volume', 'Open', 'High', and 'Low'.

## Data Cleaning:
- Importing necessary libraries for data manipulation, analysis, visualization, modeling, and evaluation.
- Downloading and preprocessing historical stock market data from Yahoo Finance.

## Exploratory Data Analysis (EDA):
- Analyzing individual variables in isolation (Univariate Analysis).
- Exploring relationships between pairs of variables (Bivariate Analysis).
- Examining relationships between three or more variables simultaneously (Multivariate Analysis).

## Data Preparation:
- Calculation of various techniques such as moving averages for stock data to gain insights into stock price trends, volatility, momentum, and potential trading opportunities in the market.

