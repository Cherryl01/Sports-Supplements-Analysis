# Sports Supplements Data Analysis
*An end-to-end data analysis project exploring supplement effectiveness, research evidence, popularity trends, and performance rankings.*

---

## Table of Contents
* [About the Project](#about-the-project)
* [Business Questions Answered](#business-questions-answered)
* [Data & Tech Stack](#data--tech-stack)
* [Visuals & Key Findings](#visuals--key-findings)
* [Getting Started](#getting-started)
* [Executive Recommendations](#executive-recommendations)

---

## About the Project

This project focuses on analyzing sports supplement data to understand the relationship between scientific evidence, effectiveness, popularity, and overall supplement performance.

Using the Sports Supplements dataset, the goal was to identify which supplements demonstrate stronger research support, analyze consumer popularity patterns, evaluate effectiveness levels, and rank supplements based on combined performance indicators.

This analysis follows an end-to-end data analytics workflow, moving from raw dataset cleaning and feature engineering to exploratory data analysis and insight generation.

---

# Business Questions Answered

1. Which supplement categories have the highest number of products?

2. Which supplements are the most popular among consumers?

3. Which supplements have the strongest scientific evidence?

4. How are supplements distributed based on effectiveness scores?

5. Which supplements rank highest based on popularity, efficacy, and evidence level?

6. Does stronger research evidence relate to higher supplement performance?

7. Which supplements provide the best overall balance between research support and effectiveness?

---

## Data & Tech Stack

* **Dataset:** Sports Supplements Dataset

* **Language:** Python 3

* **Environment:** Google Colab

* **Libraries:**
  * `pandas` (Data manipulation and cleaning)
  * `numpy` (Numerical computing)
  * `matplotlib` (Data visualization)
  * `seaborn` (Statistical visualization)

---

# Visuals & Key Findings

## 1. Supplement Categories Distribution

![Supplement Categories](https://github.com/Cherryl01/Sports-Supplements-Analysis/blob/main/Images/category_plot.png)

> *Insight:* The analysis shows the distribution of supplements across different categories. Categories with a higher number of products indicate greater market focus and wider availability.

---

## 2. Top 10 Most Popular Supplements

![Popular Supplements](Images/top_popular_supplements.png)

> *Insight:* The popularity analysis identifies supplements with the highest consumer demand. Highly popular supplements demonstrate stronger market recognition and user interest.

---

## 3. Evidence Level Analysis

![Evidence Analysis](Images/evidence_analysis.png)

> *Insight:* Supplements vary significantly in scientific support. Supplements with stronger evidence levels have more reliable research backing and greater confidence in their effectiveness.

---

## 4. Efficacy Distribution

![Efficacy Distribution](Images/efficacy_distribution.png)

> *Insight:* The efficacy analysis highlights differences in supplement effectiveness. Supplements with higher efficacy scores demonstrate stronger potential benefits based on available research.

---

## 5. Top 10 Highest Ranked Supplements

![Supplement Ranking](Images/top_ranked_supplements.png)

> *Insight:* The ranking analysis combines effectiveness, popularity, and evidence level to identify the strongest overall performing supplements.

---

# Feature Engineering

Additional features were created to improve analysis:

### Research Success Rate
Calculated the percentage of positive studies:
