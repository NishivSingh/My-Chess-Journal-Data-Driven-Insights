# ♟️ Chess Game Data Analysis

## 📌 Overview
This project presents a comprehensive analysis of my year-long Lichess chess games using Python. The objective was to uncover actionable insights from my play history, focusing on time control, openings, performance trends, and rating progression. The analysis is enhanced with visualizations and observations rooted in real game data.

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- python-chess
- Jupyter Notebook

## 📂 Data Source
- Personal `.pgn` file exported from [Lichess](https://lichess.org)
- Covers one full year of game activity

---

## 📊 Exploratory Data Analysis

### 1. Game Distribution by Variant and Time Control
> I primarily play Blitz and Bullet formats, with the vast majority being Standard variants.

![Game distribution](images/variant_timecontrol_distribution.png)

---

### 2. Monthly Game Count
> There is a clear spike in playing activity during June and September, which aligns with periods of increased free time or motivation.

![Monthly games](images/monthly_game_count.png)

---

### 3. Performance by Opening
> Openings like the **Sicilian Defense** and **King’s Pawn Opening** not only appear most frequently but also yield consistently higher win rates. This demonstrates a strategic advantage when I stick to familiar and tested openings.

![Opening win rate](images/opening_winrate.png)

---

### 4. Win Rate by Time Control
> I perform best in **Classical** games, where I have more time to think and reduce blunders. **Blitz** games follow closely. **Bullet** games, while exciting, show a noticeable dip in performance, reinforcing the impact of time pressure on quality of play.

![Win rate by time control](images/timecontrol_winrate.png)

---

### 5. Elo Rating Progression Over Time
> My rating has shown steady improvement over time, with small dips aligning with overplaying or fatigue. The upward trajectory confirms the effectiveness of consistent practice and strategic opening usage.

![Rating progression](images/rating_over_time.png)

---

## 💡 Key Insights

- **Time control directly affects performance**: My win rate improves significantly with more time to think — Classical games produce the best outcomes.
- **Opening selection has a measurable impact**: Sticking to a core set of openings leads to better results.
- **Evening play = peak performance**: Most wins occur in the evening, suggesting improved focus during those hours.
- **Bullet games are fun but costly**: While fast-paced, they yield the lowest win rate — an area for targeted improvement.

---

## 📌 Future Enhancements
- ✅ Add predictive modeling to forecast match outcomes using metadata
- ✅ Include positional analysis (e.g., centipawn loss, blunders, inaccuracies)
- ✅ Deploy as an interactive dashboard with Streamlit or Power BI

---

## 📁 Project Output
- ✅ [Project PDF with outputs](link-to-your-pdf-if-hosted)
- ✅ [Jupyter Notebook](your_notebook.ipynb)

---

## 📬 Let's Connect!
If you're passionate about chess, data, or both — feel free to connect on [LinkedIn](https://linkedin.com/in/your-profile) or explore my other projects.

---

## 📌 Example Directory Structure
