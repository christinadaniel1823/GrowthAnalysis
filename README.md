# GrowthAnalysis
AI-Powered Business Growth &amp; Marketing Insights 

Business Growth & Sentiment Analysis for Moroccan Coworking Spaces & Marketing Agencies

Unlock actionable insights into the Moroccan coworking and marketing agency markets by analyzing key growth drivers, customer engagement, advertising impact, and sentiment trends.

🚀 Project Overview

This project combines two rich datasets — Coworking Spaces and Marketing Agencies in Morocco — to deliver deep business intelligence focused on:

Identifying growth opportunities through funnel and engagement metrics

Understanding advertising efficiency and investment impact

Benchmarking competitors to drive strategic advantage

Leveraging sentiment analysis for customer satisfaction insights

Predicting business ratings using advanced machine learning models

Providing a data-driven roadmap for market expansion and competitive positioning

🎯 Why This Matters for Growth Managers and Industry Leaders

Discover Which Factors Drive Customer Engagement & Ratings
Understand how ad spending, competitor density, and operating hours influence business success.

Funnel Analysis to Optimize Marketing & Sales
Visualize how businesses progress through key performance stages — from attracting reviews to effective ad spend — helping identify bottlenecks and opportunities.

Attribution Modeling with SHAP for Transparent Decision-Making
Pinpoint the most impactful features on ratings, guiding resource allocation and campaign strategies.

Sentiment Insights to Improve Customer Experience
Analyze real customer feedback sentiment to tailor services and address pain points.

Predictive Modeling for Forecasting & Planning
Use machine learning to estimate future performance, enabling proactive management.

📁 Datasets

Coworking Space In Morocco.csv

Marketing Agency In Morocco.csv

Datasets include business ratings, reviews, competitors, ad spend indicators, operating hours, review keywords, and featured reviews.

🛠️ Step-by-Step Process

Step 1: Load & Inspect Both Datasets
Quickly understand dataset structure and quality.

Step 2: Standardize Columns
Align naming conventions for seamless analysis.

Step 3: Data Cleaning & Feature Engineering
Remove duplicates, flatten JSON columns, and create meaningful features like:

Ad Spend Flag — marks businesses investing in ads

Engagement Rate — reviews normalized by operating hours

Ad Efficiency — ad spend impact per review

Step 4: Merge or Keep Separate
Analyze datasets jointly or separately depending on business questions.

Step 5: Funnel & Growth Analysis
Visualize key metrics by category and city, including:

Total reviews and ad spend counts

Average engagement rates

Identification of high-growth vs. underperforming segments

Step 6: Attribution Analysis (SHAP)
Use XGBoost and SHAP to uncover feature importance influencing ratings.

Step 7: Predictive Modeling
Train and validate models to predict business ratings and identify potential growth levers.

Step 8: Sentiment Analysis
Extract customer sentiment from reviews to align business strategies with customer satisfaction.

📊 Key Business Insights Delivered

Growth Levers: Which marketing investments most effectively boost ratings?

Competitive Landscape: How do businesses stack up against local competitors?

Customer Voice: What are customers really saying?

Operational Efficiency: Are operating hours and ad spend optimized?

Market Segmentation: Which cities or categories show highest potential for expansion?

📦 Requirements

Python 3.x

pandas, numpy, matplotlib, seaborn

xgboost, shap, textblob

scikit-learn

Install dependencies using:

pip install pandas numpy matplotlib seaborn xgboost shap textblob scikit-learn

🧑‍💻 How to Use

Clone this repository

Place datasets in a /data folder or update paths in the script

Execute the scripts or Jupyter notebooks step-by-step

Explore visualizations and results to inform your business strategy

📈 Growth & Industry Impact

This project equips decision-makers with:

Data-driven marketing allocation to maximize ROI

Customer-centric service improvements through sentiment feedback

Benchmarking tools for competitive advantage

Predictive capabilities for proactive planning and scaling

Empower your growth strategy with analytics tailored for Morocco’s dynamic coworking and marketing industries.

📖 References & Tools

XGBoost Documentation

SHAP (Shapley Values) Documentation

TextBlob Documentation

🙌 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the project and submit a pull request!
