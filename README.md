# Product Analytics Case Study: Identifying Trust Gaps in Food Delivery Apps

A product analytics case study that analyzes user reviews from Zomato and Swiggy to identify the largest drivers of negative user experience and propose data-backed product improvements.

---

## Overview

Product decisions should be driven by user feedback rather than assumptions. In this project, I collected and analyzed 1,000 recent Google Play reviews (500 each from Zomato and Swiggy) to understand the primary reasons behind poor user experiences.

Using Python, I built an automated pipeline to scrape reviews, classify issues using rule-based keyword matching, visualize trends, and compare both platforms. The analysis showed that refund friction and order accuracy are among the most common causes of negative sentiment, leading to a product recommendation focused on improving user trust.

---

## Objectives

- Collect large-scale user feedback from Google Play.
- Identify the major causes of negative reviews.
- Benchmark Zomato against Swiggy.
- Prioritize product improvements using the RICE framework.
- Estimate the potential business impact of the proposed solution.

---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- google-play-scraper

---

## Dataset

- **Source:** Google Play Reviews
- **Platforms:** Zomato & Swiggy
- **Total Reviews:** 1,000
  - 500 Zomato
  - 500 Swiggy
- **Analysis Focus:** 1–3 star reviews

---

## Methodology

1. Scraped reviews using `google-play-scraper`.
2. Cleaned and processed the review text.
3. Classified reviews into predefined issue categories using rule-based keyword matching.
4. Calculated issue frequencies for each platform.
5. Compared Zomato with Swiggy.
6. Prioritized potential product solutions using the RICE framework.

---

## Key Findings

- Refund and customer support issues were among the most frequent drivers of negative reviews.
- Order accuracy (missing or incorrect items) was another major source of dissatisfaction.
- Similar patterns were observed across both Zomato and Swiggy, suggesting an industry-wide operational challenge rather than a platform-specific issue.
### Issue Distribution
![Issue Breakdown](images/zomato_issues.png)

### Competitor Comparison
![Competitor Benchmark](images/competitor_benchmark.png)

---

## Product Recommendation

Based on the findings, I proposed an **Auto-Refund Proof** feature that enables users to submit photo evidence for missing or incorrect items, allowing eligible cases to be resolved faster while reducing support friction.

Among the evaluated feature ideas, this solution received the highest RICE score because of its potential user impact relative to implementation effort.

---

## Business Impact

A simple business impact model was created using public assumptions to estimate the potential effect of reducing refund-related friction.

The estimates are illustrative and intended to demonstrate product thinking rather than represent actual internal company metrics.

---

## Repository Structure

```
├── data/
├── images/
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## Project Highlights

- Scraped and analyzed 1,000 Google Play reviews.
- Built an automated data pipeline using Python.
- Performed rule-based text classification on unstructured reviews.
- Benchmarked two competing food delivery platforms.
- Used data to support a product recommendation instead of relying on intuition.

