# project04-vivo-50
YouTube Healthcare Dashboard
Project Overview

This project explores how viewer engagement and attitudes differ across health education topics on YouTube. Using data collected from the YouTube Data API, we analyze engagement metrics (views, likes, comments), sentiment from video titles and descriptions, and topic-level differences between professional medical content and influencer-driven wellness content.

The final product is an interactive R Shiny dashboard that allows users to explore engagement patterns, compare topics, and examine statistical drivers of video popularity in an accessible and reproducible way.

Team Members

Yujie Gong

Mo Wang

Chengxi Zhou

Key Features

API-based data collection using the YouTube Data API

Sentiment analysis of video titles and descriptions using tidytext

Engagement analysis with normalized metrics (like rate, comment rate)

Regression modeling to identify predictors of view counts

Interactive Shiny dashboard with dynamic filtering and visualization

Data Sources

YouTube Data API v3
Publicly available metadata for YouTube videos, including views, likes, comments, titles, descriptions, and publication dates.

Technologies Used

R, Shiny

tidyverse (dplyr, tidyr, stringr, purrr)

tidytext

ggplot2

broom

Repository Structure

dashboard/ – Shiny app UI and server code

data/ – Processed datasets used in the dashboard

scripts/ – Data collection, cleaning, and analysis scripts

README.md – Project overview and documentation

Final Product

The Shiny dashboard supports both exploratory analysis and instructional use, with an emphasis on accessibility for users without extensive statistical backgrounds.
