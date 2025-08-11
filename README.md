# 🛒 Visionary Analytics – Two-Layer Recommendation Engine
We set out to solve a problem that every digital commerce platform faces:
“How do you recommend the right products, at the right time, to the right customer — without falling into the trap of showing the same old things?”
Our solution is a two-layer recommendation engine that blends:
-Fast, smart cart completion (so customers don’t leave with half-filled carts)
-Behavior-driven personalization (so newbies and loyal customers get what they are most likely to buy next)
-Dynamic freshness & diversity control (so the feed doesn’t get repetitive)
This is not just another “collaborative filtering” model, we designed it so it learns, adapts, and balances business objectives with user delight.

## Overview
An **AI-powered recommendation system** designed to optimize product suggestions through:
- Layer 1: **Cart Completion** using co-occurrence + seasonal trends + LambdaRank.
- Layer 1.5: **Behavioral Segmentation**.
- Layer 2: **TTA Personalization** for improved ranking relevance.
- Freshness & diversity control to maintain engagement and final recommendations item 4 on the given test_data_question(1).csv

## Our novelty-
Hybrid architecture: Combining co-occurrence-based cart completion + LambdaRank personalization in a multi-stage pipeline.
Customer state awareness: New vs. loyal customers get different recommendation strategies.
Freshness controls: Popular items stay, but older trends phase out gracefully.
Business-aware ranking: Recommendations are not only accurate but also optimized for AOV (Average Order Value).

## Description
We began by cleaning the store dataset, handling null values and inconsistencies. Once the store data was ready, we moved on to customer_data, applying similar cleaning steps and then performing EDA. The detailed EDA reports are included in the EDA_docs inside the provided ZIP.
After preprocessing and analysis, we merged order_data and customer_data on STORE_ID, producing the file: orders_grouped_cleaned(1).csv.
We then conducted EDA and preprocessing on this final_input dataset, referred to in our workflow as MRS(4).
For the test_data_questions dataset, we further augmented the data by introducing new derived features: DAY_TYPE– Classifying orders as Weekend or Weekday
SUB_CHANNEL – Identifying the order source as App, Kiosk, or Website
All code execution was done in Jupyter Notebooks, and the dependencies required to reproduce our work are listed in the requirements.txt file.

NOTE: Due to file size limitations, we’re unable to upload it directly to GitHub. You can either access it via the Google Drive link provided below or use the dataset named "orders_grouped_cleaned(1).csv" included in the zip file uploaded on Unstop.
Apologies for the inconvenience caused.
[Click here to access the dataset](https://drive.google.com/drive/folders/1_xHRoxZMJHa__FUUv3d7dcUD3TAB29J4?usp=sharing).






  



