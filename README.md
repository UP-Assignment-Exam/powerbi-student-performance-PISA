# 📊 Simple Guide: PISA Dashboard & Why Each Number Matters

This simple guide explains **what each number and chart means** in your Power BI Dashboard and **why we chose to include them**.

---

## 🎯 Quick Rule of Thumb for PISA Scores
* **500 points** = The official OECD World Average benchmark.
* **Above 500** = Above average / strong education system (e.g. Singapore, Canada, Australia).
* **Below 500** = Below average / needs improvement.
* **30–40 points difference** = Approximately **1 full academic year of learning** in school.

---

# 📖 Page 1: Overview Dashboard

---

### 1. Top 5 Metric Cards — Why Are They There?

| Metric | What It Shows | Why We Added It |
| :--- | :--- | :--- |
| **📖 Reading Score (`486`)** | Global average score in reading comprehension | **Why**: Stakeholders immediately want to know the baseline score for reading literacy worldwide. |
| **🧮 Math Score (`487`)** | Global average score in mathematics problem-solving | **Why**: Shows how well students apply math concepts in real-world scenarios. |
| **🧪 Science Score (`490`)** | Global average score in scientific knowledge | **Why**: Shows students' grasp of scientific facts and inquiry (currently the highest average among the three). |
| **🌐 Economies (`47` to `81`)** | Total count of countries & territories included | **Why**: Gives geographic context so people know how many countries participated. |
| **👥 Students (`1M`)** | Total sample of 15-year-old students tested | **Why**: Proves credibility and statistical power — it represents over 30 million students globally. |
| **▲ vs 2018 Comparison (`▲ 5`, `▲ 7`, `▲ 6`)** | Score change compared to the previous assessment | **Why**: A standalone number doesn't tell a story. The delta shows whether global performance is going up or down. |

---

### 2. Page 1 Charts — What Do They Show & Why?

#### 📈 Chart 1: Score Trends by Subject
* **What it shows**: A 20-year line graph showing Reading, Math, and Science scores over time.
* **Why we added it**: 
  1. To show the historical trajectory over two decades.
  2. To highlight the **2022 post-pandemic drop** across the world due to COVID-19 school closures.

#### 📊 Chart 2: Top 10 Countries by Score
* **What it shows**: Horizontal ranking of the top economies (e.g. Canada 525, Australia 513, Belgium 508).
* **Why we added it**: 
  * Allows educators and policymakers to identify top-performing models and benchmark other countries against them.

#### 🌍 Chart 3: Average Score by Region
* **What it shows**: Regional averages (Oceania ~514, Europe ~497, Asia ~479, Americas ~446).
* **Why we added it**: 
  * Shows that geographic region is a major factor. Oceania and Europe consistently lead, while Latin America faces systemic resource shortages.

#### 🍩 Chart 4: Students by Region (Donut Chart)
* **What it shows**: Breakdown of student sample weights across global regions.
* **Why we added it**: 
  * Proves fair representation so viewers understand which regions make up the data.

---

# 🔍 Page 2: Deep Dive Dashboard

---

### 3. Executive Metric Banner — Why Are They There?

| Metric Banner Item | Value | What It Means & Why We Added It |
| :--- | :--- | :--- |
| **Highest Score** | **Singapore (575)** | **Why**: Sets the global gold standard. Singapore is 75 points above the OECD average. |
| **Lowest Score** | **Guatemala (334)** | **Why**: Identifies the lower boundary to highlight which systems need urgent intervention. |
| **Score Gap / Disparity** | **241 points** | **Why**: **The most impactful number in the report**. A 241-point gap equals **~6 full years of schooling difference** between students of the same age! |
| **Change vs 2018** | **▲ 5 points** | **Why**: Measures the net shift across all filtered countries compared to 2018. |

---

### 4. Page 2 Charts — What Do They Show & Why?

#### 📊 Chart 1: Score Distribution
* **What it shows**: A bell-curve histogram grouping country scores into bins (350, 400, 450, 500, 550).
* **Why we added it**: 
  * Confirms that most countries cluster around 480–500 points, but there is a long left tail of developing countries falling behind.

#### 💵 Chart 2: Score vs. Wealth Level
* **What it shows**: Scores grouped by World Bank income tier:
  * **High Income**: `499 pts`
  * **Upper Middle Income**: `427 pts`
  * **Lower Middle Income**: `385 pts`
* **Why we added it**: 
  * Answers the key research question: *Does national wealth affect school performance?* The strong correlation ($r = 0.62$) proves richer countries can invest more in teacher quality, modern curriculum, and student support.

#### 📚 Chart 3: Performance by Income Group
* **What it shows**: Compares Reading, Math, and Science bars side-by-side across income tiers.
* **Why we added it**: 
  * Reveals that **Mathematics suffers the biggest drop (377 pts)** in lower-income countries, proving math skills are the most dependent on school resources and teacher training.

#### 🏆 Chart 4: Top 5 Economies
* **What it shows**: A dynamic ranking of the top 5 countries that changes when you click the **Subject Slicer** (Reading / Math / Science).
* **Why we added it**: 
  * Lets users explore specific subjects individually without cluttering the screen.

---

## 💡 How to Explain This Dashboard in 1 Minute (Presentation Pitch)

> *"Our dashboard analyzes PISA test data across 81 economies and 1 million students.*
> 
> *On **Page 1 (Overview)**, we show that global baseline scores hover around **486 to 490 points**, with a noticeable drop in 2022 following COVID school disruptions. High-performing systems like Singapore, Canada, and Australia lead with scores above 510.*
> 
> *On **Page 2 (Deep Dive)**, we reveal a massive **241-point Disparity Gap** between the top and bottom economies—equivalent to **6 academic years of learning**. We also demonstrate a strong **0.62 correlation with wealth**, proving that lower-income nations suffer the steepest decline in mathematics."*
