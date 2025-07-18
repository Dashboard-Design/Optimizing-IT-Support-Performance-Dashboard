# 📊 Optimizing IT Support Performance Dashboard

A Power BI dashboard designed to analyze and improve IT service operations through data storytelling, machine learning insights, and strategic visualization.

In this challenge, I stepped into the role of an IT Support Analyst to uncover trends, spot inefficiencies, and drive actionable improvements. The dataset mimics systems like Jira Service Management or Zendesk, containing thousands of support tickets tagged by type, team, priority, category, and more.

My objective? Answer a series of critical business questions — visually, interactively, and impactfully.

---

## 🧠 My Design Philosophy

The dashboard is more than a report — it's a conversation.

- I approach BI development as if I were a **psychotherapist for the business**, constantly asking:  
  *What are we missing? What hurts most? What brings clarity?*
- Each page answers **a single focused theme**, building flow and mental breathing room.
- I emphasized **interaction paths**, intuitive drilldowns, and storytelling clarity.
- I also enhanced the dataset using **Python + NLP**, enabling deeper insights through clustering and semantic similarity.

---

## 📄 Page 1: Ticket Volume & Classification

### 🔍 Business Questions Answered:
1. What kinds of issues (bugs, requests, features) come up most often?
2. Which support teams or queues handle the most tickets?
3. How are different tags (like "Security", "Integration", or "Documentation") used?

### 🖼️ Image:
![Page 1 Screenshot](1.png)

### 🔁 Key Interactions:
- Use filters to slice by Type, Country, Tag, Date, etc.
- Drill through donut and bar charts to uncover detailed tag and category distributions
- Analyze ticket trends over time with resolution overlays

---

## 📄 Page 2: Efficiency & Resolution

### 🔍 Business Questions Answered:
4. How long does it take to resolve tickets, on average?  
5. Do higher-priority tickets get resolved faster?  
6. Which types of tickets take the longest to close?

### 🖼️ Image:
![Page 2 Screenshot](Page%202.png)

### 🔁 Key Interactions:
- Country-by-priority resolution breakdown (thresholds highlight underperformers)
- Cluster queues by resolution delay and volume (risk matrix)
- Zoom into top tags or resolution types that are trending above target thresholds

---

## 📄 Page 3: Optimization & Service Improvement

### 🔍 Business Questions Answered:
9. Can we group similar tickets to create automated replies or help articles?  
10. Are the agent responses helpful and aligned with what the user asked?  
11. Where can the support team save time or improve service quality?

### 🖼️ Image:
![Page 3 Screenshot](Page%203.png)

### 🧠 Features:
- **NLP-based clustering** of ticket subjects using TF-IDF + KMeans to detect automatable topics
- **Cosine similarity scoring** of ticket body vs answer to evaluate agent alignment
- **Time-wasting pattern detection** combining resolution time and ticket volume

Each panel includes **Action Boxes** that translate findings into next-step decisions.

---

## ℹ️ Info Page (Optional Tooltip Overlay)

### 🎯 Purpose:
A lightweight user guide overlay to help first-time users navigate the dashboard.

Includes:
- Filter section functionality
- Page navigation explanation
- Chart interactivity notes (ZoomCharts)
- Meaning of KPIs and thresholds

---

## 🧠 Final Thoughts

This dashboard is the result of combining data, storytelling, and curiosity.  
It's not perfect — no solution ever is. But it **asks better questions**, guides clearer decisions, and opens the door to continuous improvement.

> *"A dashboard is not the destination — it's the map. And the map gets better the more you explore."*

---

### 🚀 Tech Used
- **Power BI** (including ZoomCharts custom visuals)
- **Python** (TF-IDF, KMeans, Cosine Similarity)
- **Pandas, scikit-learn**, and **Matplotlib** for analysis

---

### 📁 Folder Suggestions (if uploading assets):
