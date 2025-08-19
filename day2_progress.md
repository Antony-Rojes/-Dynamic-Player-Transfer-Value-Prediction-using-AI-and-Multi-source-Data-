# Day 2 Progress

### 1) Discussion on Huge Data in Context of Project and Model

* **Huge data is relative, not absolute.** It depends on the complexity of the problem and the requirements of the ML model.
* In this project, *huge data* means:

  * A large number of players across multiple leagues and seasons.
  * High-dimensional attributes (performance stats, age, position, injuries, transfers, market values, etc.).
  * Longitudinal data (player career progression over time).
  * Multi-source integration (Transfermarkt, match stats, news sentiment, etc.).
* For the **model**:

  * More data variety improves the ability to learn complex relationships behind transfer values.
  * Huge data ensures the model is less biased toward a specific league, season, or type of player.
  * Small data risks **overfitting**—good performance in training but poor real-world predictions.
* **In this project’s context:**

  * Huge data = sufficient quantity + variety + quality of player-related records.
  * It’s not just about the number of rows, but about covering diverse scenarios across players, leagues, and economies.

### 2) Further Data Exploration

* **Market Value Data:** Explored Transfermarkt data via web scraping.
* Aim: Collect historical player values, transfers, and progression trends to build a strong foundation dataset.

### 3) Question for Day 3

* *Is one data source enough to make a model generalize, or are multiple data sources better?*
* *How will a model trained only on a single data source behave in real-world scenarios?*
