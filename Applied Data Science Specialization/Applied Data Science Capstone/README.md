# SpaceX Falcon 9 First Stage Landing Prediction

## Overview

This project predicts the landing success of SpaceX Falcon 9's first stage to analyze cost-efficiency and improve reusable rocket technology. The goal is to assess factors influencing the success of first-stage landings, such as payload, orbit type, and launch site, and to determine the best-performing predictive model.

## Objectives

- **Exploratory Data Analysis (EDA):** Explore patterns and relationships in SpaceX's launch data using SQL, interactive maps, and visualizations.
- **Predictive Analysis:** Build, tune, and evaluate classification models to predict landing success.
- **Insights for SpaceX:** Understand factors like orbit type, payload mass, and launch site trends to aid decision-making.

## Project Highlights

### 1. **Data Collection and Preparation**
- Data was gathered via:
  - **API Calls:** SpaceX's API provided structured data on launches.
  - **Web Scraping:** Extracted supplementary data from Wikipedia using BeautifulSoup.
- Preprocessing steps included cleaning, encoding categorical variables, and standardizing numeric data.

### 2. **Exploratory Data Analysis (EDA)**
- SQL queries and visualizations provided key insights:
  - **Launch Sites:** Most launches occurred at CCAFS SLC-40, followed by KSC LC-39A.
  - **Payload Analysis:** Heavier payloads were associated with higher failure rates, particularly at certain launch sites.
  - **Orbit Type Challenges:** Higher-altitude orbits (e.g., GTO) posed greater mission challenges.

### 3. **Predictive Modeling**
- Several classification models were built and compared:
  - **Decision Tree:** Achieved the highest test accuracy (88.8%), demonstrating strong generalization and reliability.
  - Other models like Logistic Regression, SVM, and KNN performed reasonably well (~83.3% test accuracy).
- **Confusion Matrix Analysis:** Highlighted false positives as a challenge for some models.

### 4. **Key Insights**
- SpaceX's landing success improved significantly over time, showcasing the effectiveness of iterative development.
- Payload mass and orbit type were critical factors influencing mission outcomes.
- Decision Tree proved to be the most effective model for predicting landing success.

## Repository Contents

- **Presentation Slides:** A detailed summary of the methodology, results, and conclusions.
- **Code:** Scripts for data collection, preprocessing, EDA, and modeling.

## Conclusions

- SpaceX's iterative development approach has significantly enhanced landing success rates.
- Predictive modeling provides valuable insights for optimizing future missions.
- Decision Tree stands out as the most reliable model for predicting landing outcomes.
