# Optimising-Air-Travel
 This project aims to predict flight delays using past flight performance data with the help of machine learning. Flight delays are a major issue in air travel, leading to inconvenience for passengers and increased operational costs for airlines. The goal is to build a two-part system: one that predicts whether a flight will be delayed, and another that estimates how long the delay will be.

The dataset was cleaned by removing unnecessary columns, encoding categorical values, filling missing data, and handling outliers. A custom metric called Operational Adjustability Index (OAI) was created to help analyze carrier performance.

Exploratory analysis showed that delays are not evenly spread — only 30% of airports show high delays, mostly during summer months like June and July. Some airlines, like Southwest (WN), perform better in terms of on-time arrivals, while others like KS and F9 have high delay rates.

The project used XGBoost for both classification and regression. The classification model predicts if a flight will be delayed (F1 score: 0.85), and the regression model estimates the delay in minutes (R²: 0.78). The combined system gives clear and accurate predictions, helping airlines make better decisions.

Key suggestions include rebalancing flight schedules, improving ground handling, updating passengers in real time, and focusing more resources on high-risk airports during peak times.
