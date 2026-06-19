---
layout: project
title: "Live Commerce Pricing Analysis via Text Mining"
year: "January 2024"
categories: project data-analysis
img: assets/img/projects/ecommerce-preview.png
images:
- url: ecommerce-01.jpg
- url: ecommerce-02.jpg
  caption: "Business problem and objectives: helping Jambo Live optimize off-peak revenue by understanding pricing dynamics across 300K–400K monthly health-product transactions."
- url: ecommerce-03.jpg
  caption: "A two-stage text-mining pipeline—training a classifier on Shopee's labeled catalog, then applying it to Jambo's messy transaction data for product tagging, segmentation, and pricing-trend analysis."
- url: ecommerce-04.jpg
  caption: "Revenue by shopping festival and category. Double 11 drives roughly 3x average revenue for Gut Health—a key window for promotional pricing."
- url: ecommerce-05.jpg
  caption: "An SVM model (accuracy ≈ 0.68) classified 14,308 products into eight customer-oriented segments, enabling targeted pricing by health concern."
- url: ecommerce-06.jpg
  caption: "Translating the analysis into four concrete pricing strategies—festival-driven windows, segment-specific bundling, trend-led inventory, and trust-economy pricing."
---
A text-mining and pricing-analysis project for Jambo Live, a Taiwanese live-commerce platform. By analyzing over three million health-product transactions, I set out to uncover how demand shifts across seasons and customer segments—and turn those patterns into actionable, data-driven pricing strategies that lift average order value during off-peak periods.

The work combined natural-language processing (TF-IDF and an SVM classifier trained on Shopee's product catalog) with customer segmentation and Google Trends analysis. The slides below walk through the business problem, the two-stage pipeline, the key findings, and the resulting pricing recommendations.

**Tools:** Python · Scikit-learn (SVM, TF-IDF) · Pandas · Matplotlib · Google Trends API

[View the Project](https://github.com/matkim1369/jambo-pricing-text-mining){: target="_blank"}
