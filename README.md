# Alex the Analyst YouTube Content Analysis

> A data-driven exploration of 355 videos from the “Alex the Analyst” YouTube channel, uncovering key engagement patterns, timing effects, and keyword insights.

---

## 📖 Table of Contents

1. [Overview](#overview)  
2. [Project Structure](#project-structure)  
3. [Data Collection](#data-collection)   
4. [Key Findings](#key-findings)  
 

---

## 📊 Overview

Briefly describe your objective and why it matters.  
> “I analyzed Alex the Analyst’s YouTube channel to identify what drives views and engagement, with actionable recommendations for content strategy.”

---

## 🗂 Project Structure

```text
├── data/                   # raw and processed CSVs
│   ├── raw/                # raw API exports
│   └── processed/          # cleaned file
│
├── notebook/              # Jupyter notebook
│   Alex_Youtube_Analytics.ipynb
│
└──README.md               # this file
```
---

## 🛠 Data Collection

Source: YouTube Data API v3
Endpoints used: videos.list, search.list
Fields retrieved: viewCount, likeCount, commentCount, duration, publishedAt, title

---

## 🔑 Key Findings
- Shorter videos tend to yield higher likes-per-view ratios.
- Sunday uploads outperform other days in total views (p < 0.01).
- Views, likes, and comments are strongly correlated (views vs likes ≈ 0.94).
- Duration has virtually no correlation with views (r ≈ 0.00).
- Top keywords in the most-viewed titles: data, SQL, analyst, beginners.

For a detailed narrative, see the final report in reports [here](https://adewoye-saheed-dml.medium.com/alex-the-analyst-youtube-channel-insights-e349b6d16269)
