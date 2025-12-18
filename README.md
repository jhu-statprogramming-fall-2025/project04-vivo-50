# YouTube Healthcare Dashboard

## Project Overview
This project examines how viewer engagement and audience attitudes differ across health education topics on YouTube. Using data collected from the **YouTube Data API**, we analyze engagement metrics (views, likes, comments), sentiment derived from video titles and descriptions, and topic-level differences between **professional medical content** and **influencer-driven wellness content**.

The final product is an **interactive R Shiny dashboard** designed to support exploratory analysis and instructional use, with an emphasis on accessibility and interpretability for users without extensive statistical backgrounds.

---

## Team Members
- **Yujie Gong**  
- **Mo Wang**  
- **Chengxi Zhou**

---

## Key Features
- API-based data collection using the YouTube Data API  
- Sentiment analysis of video titles and descriptions using `tidytext`  
- Engagement analysis with normalized metrics (like rate and comment rate)  
- Regression modeling to identify predictors of video popularity  
- Interactive Shiny dashboard with dynamic filtering and visualizations  
---

## Data Sources
- **YouTube Data API v3**  
  Publicly available metadata for YouTube videos, including titles, descriptions, view counts, likes, comments, and publication dates.

---

## Software and Package Used
- **R**, **Shiny**
- **tidyverse** (`dplyr`, `tidyr`, `stringr`, `purrr`)
- **tidytext**
- **ggplot2**
- **broom**

---

Programming Paradigms

This project integrates multiple programming paradigms discussed in class:

- **API-based data collection**: Data were programmatically retrieved from the YouTube Data API, requiring structured requests, pagination handling, and rate-limit considerations.
- **Functional programming**: Data cleaning, sentiment scoring, and engagement metric calculations were implemented using reusable functions and tidyverse pipelines.
- **Machine learning / statistical modeling**: Linear regression models were used to assess predictors of video popularity, and effect size visualizations were generated to support interpretation.
- **Interactive programming**: An R Shiny dashboard was developed to allow dynamic filtering, visualization, and exploratory analysis by end users.

Combining these paradigms allowed us to build a flexible, reproducible, and user-friendly data analytic product.

---

## Final Product

The dashboard enables users to explore engagement patterns across healthcare topics, compare professional and influencer content, and examine statistical drivers of video popularity through an intuitive, interactive interface.
Our final product is also deployed in https://flusightcategoricalprediction.shinyapps.io/healthcare_dashboard/
