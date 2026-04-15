# Spotify Trend Analysis 2014–2020

An end-to-end data analysis project exploring Spotify track trends across 7 years.

**Live Demo:** https://z1yuguo.github.io/spotify-analysis/
**Tableau Dashboard:** https://public.tableau.com/app/profile/ziyu.guo/viz/spotify_analysis_17762366860580/Dashboard1

---

## Tech Stack

- **SQL** — SQLite, GROUP BY, CTE, Window Functions (RANK, SUM OVER)
- **Python** — pandas, Plotly (interactive visualizations)
- **Tableau** — Dashboard with 3 charts
- **HTML/CSS/JS** — Single-page web deployment via GitHub Pages

---

## Key Insights

- Dataset contains **1,701 tracks** across 5 mood categories (sad, rock, remix, night, love)
- **2016 was the peak year** with 303 tracks
- **Sad music dominated 2014–2019**, consistently ranking #1 in annual share
- **Remix surged to 34.5% in 2020** — a notable shift possibly linked to pandemic listening habits
- **Lil Peep** leads all artists with 21 appearances, followed by Twenty One Pilots (17) and Post Malone (14)

---

## Project Structure
├── spotify_analysis.ipynb   # SQL + Python analysis
├── spotify_analysis.twb     # Tableau workbook
└── docs/
└── index.html           # Web dashboard
---

*Data source: Spotify API via Kaggle*