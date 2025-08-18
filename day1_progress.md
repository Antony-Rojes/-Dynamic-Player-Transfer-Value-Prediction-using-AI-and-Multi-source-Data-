# Day 1 Progress Report

## 1. Perfect Data Illusion

* Today we discussed the concept of **Perfect Data Illusion**.
* It happens when data looks "too clean" or "too perfect" compared to real-world data.
* Real-world data usually contains missing values, noise, and outliers.
* Having perfectly clean data can actually be a **bad sign** because it may indicate:

  * Data has been over-processed (important signals lost).
  * Possible fabrication or manipulation.
  * Lack of real-world variability, which makes models fail to generalize.

## 2. Creating a New Branch

* Following the mentor’s instructions, I created a new branch with my name (`<Aman_Singh>`).
* This branch will be used for my work without affecting the main branch.

## 3. Data Exploration

* The main work today was **exploring the StatsBomb Football Data** from Kaggle.
* StatsBomb provides one of the largest open datasets for football analytics.
* It contains detailed **event data** (passes, shots, tackles, dribbles) as well as **match data** (teams, players, results).
* The dataset is very detailed, covering multiple leagues and competitions.
* I observed that the dataset is **huge**, which might cause performance issues on my current PC hardware.
* Handling such large datasets requires careful optimization:

  * Using efficient file formats.
  * Loading data in chunks instead of all at once.
  * Using cloud/colab environments if local resources are insufficient.

## 4. Tomorrow’s Question

* Mentor provided a discussion point for tomorrow:
  **What is "huge data"?**

  * Should we define it as an absolute value (e.g., >1GB, >10M rows)?
  * Or does "huge" depend on the project requirements and available computing resources?
