# India-Startup-Funding-Pulse-2024-vs-2026

## What This Project Is About
A data analysis project exploring Indian startup funding patterns across 2024 and 2026 — which sectors are attracting capital, how funding stages are shifting, which cities dominate, and whether the AI wave is reflected in actual funding numbers.

This isn't a tutorial project. The goal was to answer a real question:
**"What does the Indian startup funding landscape actually look like, and what changed in two years?"**

---

## Key Findings
- **Healthcare and FinTech** dominate funded sectors in both years
- **Seed stage** funding is the most common — most Indian startups are still early
- **Bengaluru, Mumbai, and Pune** are the top 3 cities for startup funding
- **AI startups**, despite the hype, represent a smaller share of total funding than non-AI startups — capital is still flowing into traditional sectors
- Total funding shows a significant jump from 2024 to 2026

---

## Tools Used
- **Python** — data cleaning, analysis, visualizations (Pandas, NumPy, Matplotlib, Seaborn)
- **Tableau Public** — interactive dashboard
- **Excel/CSV** — raw data handling

---

## Dataset
- `Startup_funding_2024.csv` — 436 Indian startups funded in 2024
- `Recently_Funded_Startups_In_India_2026.csv` — 100 Indian startups funded in early 2026
- Combined and cleaned into `india_startup_funding_clean.csv`

---

## Project Structure
india-startup-funding-analysis/
│
├── data/
│   ├── Startup_funding_2024.csv
│   ├── Recently_Funded_Startups_In_India_2026.csv
│   └── india_startup_funding_clean.csv
│
├── visuals/
│   ├── top_sectors.png
│   ├── funding_stages.png
│   ├── year_comparison.png
│   ├── ai_vs_nonai.png
│   └── top_cities.png
│
├── india_startup_funding_analysis.ipynb
└── README.md

---

## Tableau Dashboard
Tableau dashboard file included in repo — open `dashboard.twb` in Tableau Public (free) to explore

---

## Insights That Surprised Me
- AI as a sector label appears frequently but actual funding amounts are dwarfed by Healthcare and FinTech
- Pre-Seed dominance suggests India's startup ecosystem is still in early growth phase
- Bengaluru's lead over Mumbai is larger than expected

---

## How to Run
1. Clone the repo
2. Install requirements: `pip install pandas numpy matplotlib seaborn`
3. Open `india_startup_funding_analysis.ipynb` in Jupyter
4. Run all cells in order
