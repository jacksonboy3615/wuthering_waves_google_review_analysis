# Wuthering Waves Google Review Analysis  
**Interactive analysis of Wuthering Waves’ Google Play reviews from Pre-Launch to Version 2.0, built with Python and ipywidgets.**

---

## 📌 Overview
This project analyzes how player sentiment toward **Wuthering Waves** has evolved over time —  
from the *Pre-Launch* hype phase to the **Version 2.0** update.

Using Python, ipywidgets, and data visualization, it explores trends, recurring themes, and keyword patterns in Wuthering Waves' Google Play reviews.

---

## 🎯 Objectives
- Track sentiment changes across multiple versions  
- Identify keyword trends from player feedback  
- Explore sentiment and score distributions with interactive widgets  
- Visualize rating trends and frequently used words (word clouds)

---

## 🧰 Libraries Used
- **pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **ipywidgets**  
- **VADER Sentiment**  
- **pandasql**

---

## 📊 Sentiment Analysis

Based on VADER sentiment scores, players’ **positive sentiment is steadily increasing**:

- **Overall:** 71% positive  
- **Pre-Launch:** 56% positive  
- **Version 1.0:** 70% positive  
- **Version 2.0:** 72% positive  

<img width="775" height="605" alt="image" src="https://github.com/user-attachments/assets/e5819d1f-c3b8-4342-b3e9-76b85ec7ac6e" />

---

## ⭐ Score Distribution

- Between **Pre-Launch** and **Version 1.0**, the share of **5-star ratings** dropped sharply  
  - 5★ ratio: **82.9% → 60.9%**  
- However, the game made a strong recovery in **Version 2.0 (Rinacita)**  
  - 5★ ratio: **60.9% → 71.0%**

---

## 📈 Average Score by Version

- **Pre-Launch:** 4.5 / 5.0  
- **Version 1.0:** 3.9 / 5.0  
- **Version 2.0:** 4.2 / 5.0  

---

## ☁️ Word Clouds by Version

- Early on, players frequently compared Wuthering Waves to **Genshin Impact**.  
  By **Version 2.0**, Genshin is rarely mentioned, as most players focus on the **Rinacita story and characters**.  
- Some players still report **lag and performance issues**
- However, mentions of lagging are **less frequent in Version 2.0** compared to Version 1.0.

---

## 🔑 Top 10 Keywords by Version

One interesting pattern: **“Genshin Impact” disappears from the Top 10 Keywords in Version 2.0.**  
This suggests that players are increasingly viewing **Wuthering Waves on its own merits**, rather than primarily as a comparison target.

---

## ✅ Conclusion

- Players’ overall sentiment toward Wuthering Waves is **steadily improving**.  
- Word clouds and keyword analysis show a clear trend: Most players **no longer compare** Wuthering Waves heavily with Genshin Impact.  
- **Version 2.0 (Rinacita)** receives strong positive feedback for its **characters, storyline, and graphics**.  
- While **Version 1.0** reviews frequently mentioned lag and bugs, those issue-related keywords **drop significantly in Version 2.0**, indicating noticeable improvements in performance and stability.

There is also a **Plotly-based interactive version** of the analysis available in this repository.

---

## 🔗 Connect with Me

If you’d like to talk about **data analysis, Python, or TV Series 😄**, feel free to reach out:

- **Email:** jkim3615@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/jae-hwan-kim-274190100/
