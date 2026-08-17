# 📊 YouTube Data Analysis & Sentiment Analysis

## 📌 Project Overview

This project analyzes YouTube data to understand **video performance, audience engagement, trending categories, and audience sentiment**.

The project is divided into two main areas:

- **YouTube Comment Sentiment & Emoji Analysis**
- **YouTube Trending Video Analysis**

The analysis was performed using Python and various data analysis and visualization libraries.

---

## 🎯 Objectives

- Analyze sentiment in YouTube comments
- Classify comments as Positive, Negative, and Neutral
- Identify the most frequently used emojis
- Analyze YouTube trending videos by category
- Compare views and engagement across categories
- Analyze relationships between views, likes, and comments
- Analyze engagement-rate distribution
- Identify categories receiving the most attention

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- NLTK / VADER
- Matplotlib
- Plotly
- Jupyter Notebook

---

# 🔍 Analysis

## 1. YouTube Comment Sentiment Analysis

YouTube comments were analyzed using the **VADER Sentiment Analyzer**.

Comments were classified into:

- Positive
- Negative
- Neutral

### Sentiment Distribution
<img width="277" height="92" alt="Image" src="https://github.com/user-attachments/assets/7e9ab1d6-c0ac-46f4-82f7-e2834b9ca973" />


---

## 2. Emoji Analysis

Emojis were extracted from YouTube comments to identify the most frequently used emojis.

### Top Emojis Used in YouTube Comments

<img width="1340" height="706" alt="Image" src="https://github.com/user-attachments/assets/0f44a3db-b1f2-420c-aac9-4d7c1d7decaf" />

---

# 📈 YouTube Trending Video Analysis

## 3. Category-Wise Video Analysis

The trending videos were analyzed based on their YouTube categories.

### Category-Wise Video Count
<img width="1371" height="726" alt="Image" src="https://github.com/user-attachments/assets/f84cc601-9b54-42ef-8479-e0b5b385d2e1" />



---

## 4. Category Attention Share

A treemap was used to visualize the share of total views received by different categories.

### Category Attention Share With Engagement Efficiency Overlay

<img width="1365" height="731" alt="Image" src="https://github.com/user-attachments/assets/7259cee6-16ce-4663-9fd4-0e449eee70de" />

---

## 5. Views vs Engagement Analysis

A scatter/bubble visualization was used to examine the relationship between video views and engagement metrics.

### Views vs Engagement

<img width="1429" height="789" alt="Image" src="https://github.com/user-attachments/assets/c99a7c13-21fe-42ba-a682-c18aead2218f" />

---

## 6. Engagement Rate Distribution

The distribution of engagement rates was analyzed to understand how engagement varies across videos.

### Engagement Rate Distribution

---
<img width="1365" height="743" alt="Image" src="https://github.com/user-attachments/assets/d04c2d56-20b4-44e7-834a-89bb8fe2d965" />

## 7. Category-Wise Engagement Analysis

### Category-Wise Engagement Efficiency
<img width="1365" height="743" alt="Image" src="https://github.com/user-attachments/assets/eaefdb75-0638-4c88-ae59-47e800da6e2b" />

---

# 📊 Key Findings

### Engagement Rate

The dataset contains **339,525 non-null engagement-rate records**.

| Statistic | Value |
|---|---:|
| Mean | 4.21% |
| Median | 2.75% |
| 75th Percentile | 6.03% |
| Maximum | 95.73% |

The mean engagement rate is higher than the median, indicating a **right-skewed distribution**. Most videos have relatively low engagement, while a smaller number of videos have exceptionally high engagement rates.

### Other Findings

- Different YouTube categories receive different levels of audience attention.
- Video views and engagement vary considerably across categories.
- A smaller group of videos achieves exceptionally high engagement.
- Sentiment analysis provides insight into audience reactions.
- Emoji analysis provides an additional perspective on how viewers express themselves in comments.

---

# 📁 Dataset

The original dataset is not included in this repository because of its large file size.

**Dataset Source:**
https://www.kaggle.com/datasets/datasnaek/youtube-new

The analysis was performed using the original dataset.

---

# 📂 Repository Structure

```text
Youtube-Data-Analysis/
│
├── README.md
├── Youtube Sentiment Analysis.ipynb
