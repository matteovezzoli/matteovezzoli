# Hi, I'm Matteo 👋

Sports Data Analyst / Data Scientist based in Milan, Italy. I turn event, tracking and spatial data into tactical insights and scouting tools, with one recurring question: **how much of a player's output is his own, and how much comes from his team?**

Statistics background (M.Sc. 110/110 cum laude), Postgraduate in Sports Analytics at Barça Innovation Hub.

---

### ⚽ Football Analytics Projects

**[Contextual Football Scouting](https://github.com/ArMat-Analytics/Contextual-Football-Scouting)** · [Web app](https://contextual-football-scouting.vercel.app/)
Scouting platform covering 272 players from UEFA Euro 2024, built on StatsBomb 360° data to measure the value a player creates independently of his team's context.
- Defensive block modeled as a **Convex Hull**; progression weighted by **Expected Possession Value (EPV)** rather than passing volume
- **Decision Quality Index**: each passing choice scored against the alternatives actually available in the frame
- **Uncapitalized Run Score (URS/90)**: off-ball runs offered but not used by teammates
- Within-role similarity model (11 playing-style metrics), cross-referenced with Transfermarkt values to find low-cost alternatives

**[Serie A Observatory](https://github.com/matteovezzoli/serie-a-observatory)** · [Live dashboard](https://serie-a-observatory.streamlit.app/)
Serie A analytics dashboard built end-to-end from the official Lega Serie A Match Report PDFs.
- **Custom PDF parser** (pdfplumber, word coordinates) for tables where zero values are not printed; validated on 50 matches with no unassigned values
- Player analysis focused on team context: **per-90 rates, share of team output, league percentiles, cosine-similarity search** and a scouting tool for players carrying weak teams
- Team analysis: playing-style and efficiency maps, home/away splits, standings over time
- 12-page Streamlit app, every chart explained, updated matchday by matchday

**[Serie A CB Scouting Engine](https://github.com/matteovezzoli/SerieA-DefensiveScouting-Engine)** · [Dashboard](https://seriea-defensive-engine.streamlit.app/)
Scouting system for Serie A centre-backs (2025/26): **PCA + K-Means** clustering on 77 players to identify similar profiles, in an interactive Streamlit dashboard.

**Expected Goals (xG) Pipeline**
End-to-end development and calibration of xG models with Logistic Regression, Random Forest and XGBoost.

**Technical Scouting & Match Analysis — Girona FC case study**
Scouting reports and tactical assessments following the recruitment data standards of Girona FC's analytics department.

---

### 🎓 Education

- **Postgraduate Degree in Sports Analytics** · *Universitat Central de Catalunya & Barça Innovation Hub* (Jan – Jul 2026)
  Open, event and tracking data; model selection for tactical and performance problems; Python and SQL.
- **M.Sc. Statistics, Economics and Business – Business Analytics** · *University of Bologna* (2023 – 2025)
  110/110 cum laude. Thesis: comparative analysis of multivariate time-series forecasting methods (VAR, Random Forest, XGBoost, LightGBM, CatBoost, SVM, LSTM).
- **B.Sc. Statistics and Economic Sciences** · *University of Milano-Bicocca* (2020 – 2023)
  Thesis project: predictive model for NBA player salaries.

---

### 💼 Experience

- **Research Collaboration** · *University of Bologna* (Oct 2025 – Jan 2026)
  Scientific paper based on my Master's thesis: full ownership of the data pipeline, from curation and ML modeling to software implementation and visualization.
- **Market & Data Analyst (Internship)** · *Nomisma* (Feb – Apr 2025)
  Predictive model in R presented by the company at Vinitaly 2025; database management and strategic reports.

---

### 🛠️ Tech Stack

- **Languages:** Python (pandas, NumPy, scikit-learn, XGBoost), R, SQL, SAS, MongoDB
- **Analytics:** Machine Learning (regression, classification, clustering), Time Series Forecasting, Web Scraping
- **Sports data:** StatsBomb event & 360° data, tracking data, PDF/document data extraction
- **Visualization & apps:** Streamlit, Plotly, Power BI, Excel
- **Tools & deployment:** Git/GitHub, Supabase, Vercel

🌍 Italian (native) · English (B2)

---

### 📫 Contact

[LinkedIn](https://linkedin.com/in/matteo-vezzoli83) · matt.vezzoli@gmail.com

