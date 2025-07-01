# Unsupervised Learning for Cognitive Behavior Analysis - Ball Game Data

This project applies unsupervised machine learning techniques to analyze and uncover hidden patterns in behavioral data collected from a logic-based ball counting game. The aim is to explore cognitive task performance using clustering and dimensionality reduction methods without predefined labels.

Developed as part of an academic internship project at **NIT Trichy**, this work complements a broader machine learning framework for cognitive assessment through interactive games.

---

## 📂 Dataset

The dataset includes:
- Task completion times for 2, 3, 4, and 5-ball problem-solving rounds
- Data collected from 10 participants over 20 cycles each (200 records total)

**Features:**
- `Person` - Participant identifier (P1 to P10)
- `Time_2` - Time taken for 2-ball task (seconds)
- `Time_3` - Time taken for 3-ball task
- `Time_4` - Time taken for 4-ball task
- `Time_5` - Time taken for 5-ball task

---

## 🧠 Applied Unsupervised Learning Techniques

- **K-Means Clustering**  
  Identify distinct performance groups based on task completion times.

- **Hierarchical Clustering (Dendrograms)**  
  Visualize relationships and cluster hierarchies among participants.

- **Principal Component Analysis (PCA)**  
  Reduce dimensionality and visualize cognitive behavior patterns in 2D space.

---

## 📊 Exploratory Data Analysis (EDA)

- Visualize average performance trends
- Boxplots for variation and outlier detection
- Correlation heatmaps of time features

---
