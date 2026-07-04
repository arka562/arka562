<div align="center">

# Arkaprava Ghosh

<a href="https://arkaprava-ghosh-portfolio.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com/?lines=Full-Stack+Developer+(MERN);Data+Analyst+%7C+Python+%2B+SQL;B.Tech+CSE+(IoT),+Graduated+2026;Open+to+SDE+%26+Data+Analyst+roles&font=Space%20Mono&center=true&width=520&height=45&color=2DD4BF&vCenter=true&size=20" alt="typing animation"/>
</a>

<br>

<a href="https://arkaprava-ghosh-portfolio.netlify.app/">
  <img src="https://img.shields.io/badge/PORTFOLIO-View_Live_Site-2DD4BF?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
</a>
<a href="https://www.linkedin.com/in/arkaprava-ghosh-9255a1251">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:arka792003@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://x.com/arka_ghosh35042">
  <img src="https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter"/>
</a>

<br><br>

![Profile views](https://komarev.com/ghpvc/?username=arka562&color=2DD4BF&style=flat-square&label=Profile+Views)
![LeetCode](https://img.shields.io/badge/LeetCode-250%2B_solved-FFA116?style=flat-square&logo=leetcode&logoColor=white)

</div>

<br>

## About

- Final-year projects and one internship (Adani Power) split across two tracks: **full-stack MERN systems** and **data analysis / ETL**.
- Every metric below comes from measured testing on the actual project — latency numbers, model accuracy, record counts. None of it is estimated.
- Full breakdown of experience, education, and certifications is on the **[portfolio site →](https://arkaprava-ghosh-portfolio.netlify.app/)**

<br>

<details>
<summary><b>🧰 Tech Stack (click to expand)</b></summary>
<br>

<div align="center">

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data & Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Visualization & Tools**
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

</div>
</details>

<br>

## Projects

<details open>
<summary><b>🔹 BlinkChat — Real-Time Chat Application</b></summary>
<br>

`Node.js` `Express.js` `MongoDB` `Redis` `React` `Socket.IO` `Jest`

- Diagnosed a ~2.5s median message latency under cross-region load (Render Oregon ↔ MongoDB Atlas Mumbai / Upstash Redis).
- Fixed it with Redis cache-aside validation and fire-and-forget cache invalidation — **81% latency cut**, down to ~468ms.
- Solved message-ordering race conditions with server-side timestamps; built accurate seen-status tracking via Socket.IO acknowledgements.
- Isolated Jest integration suite (mongodb-memory-server) covering auth and messaging routes, including error paths.

**[Repo](https://github.com/arka562/blinkchat)** · **[Live Demo](https://blinkchat-blond.vercel.app/)**

</details>

<details>
<summary><b>🔹 AI Interview Coach</b></summary>
<br>

`MERN` `Gemini` `OpenRouter` `Groq` `Hugging Face`

- Built a multi-provider LLM routing system with circuit-breaker fallback across four providers.
- Load-tested against real provider failures (rate limits, timeouts) — **100% request success** via automatic failover.
- Groq as primary provider, ~780ms median latency, roughly 3x faster than the Hugging Face fallback.
- Adaptive interview difficulty based on live user performance; resume parsing (PDF/Text) for personalized scenarios; automated PDF feedback reports.

**[Repo](https://github.com/arka562/ai-interview-coach)** · **[Live Demo](https://meek-kheer-3f184f.netlify.app/login)**

> ⚠️ Repo name pending confirmation — verify this matches your actual GitHub repo before publishing.

</details>

<details>
<summary><b>🔹 Supply Chain Delay Prediction</b></summary>
<br>

`Python` `SQL` `Power BI` `Random Forest`

- Random Forest classifier with class-weight balancing for imbalanced delay labels — **87% accuracy**, 18 points above the logistic regression baseline (69%).
- **93% precision** on on-time order predictions.
- Full ETL pipeline: SQL ingestion → cleaning → feature engineering + one-hot encoding → model training → Power BI dashboard.
- SQL feature engineering using multi-table joins, CASE WHEN, GROUP BY/HAVING.

**[Repo](https://github.com/arka562/supply-chain-delay-prediction)**

> No live dashboard link exists in your source resumes for this project — add one if you have it.

</details>

<details>
<summary><b>🔹 IPL Analytics & Prediction Platform</b></summary>
<br>

`Python` `Streamlit` `SQL` `DuckDB` `Plotly`

- Warehoused **1,200+ matches and 294K+ deliveries** into DuckDB via modular Python scripts.
- Season trends, venue par scores, toss impact, phase-wise team/player performance via interactive Plotly charts.
- SQL with CTEs and window functions (`QUALIFY ROW_NUMBER() OVER (PARTITION BY...)`) for batter rankings.
- Supporting ML models for win probability and score projection, deployed to a production Streamlit dashboard.

**[Repo](https://github.com/arka562/ipl_analysis)** · **[Live App](https://iplanalysis-ja3jmqhz5kra7wfydke9xw.streamlit.app/)**

</details>

<details>
<summary><b>🔹 India Crime Analysis & Visualization Dashboard</b></summary>
<br>

`Python` `Pandas` `NumPy` `Streamlit`

- Cleaned and analyzed **10,000+ NCRB crime records**; year-over-year trend analysis and state-wise comparison.
- Production Streamlit dashboard with choropleth maps, crime distribution charts, state-wise filters.
- Growth-rate forecasting projecting 2021–2023 trends per state; per-capita normalization for fair cross-state comparison.

**[Repo](https://github.com/arka562/india-crime-dashboard)** · **[Live App](https://india-crime-dashboard-s3nmqhlxqnxjze74yj2vdn.streamlit.app/)**

</details>

<br>

## GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=arka562&show_icons=true&theme=default&hide_title=true&count_private=true" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arka562&layout=compact&hide_title=true" width="35%" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=arka562&theme=default&hide_border=true" width="60%"/>
</div>

<br>

## Certifications

- [Web Development — Johns Hopkins University](https://www.coursera.org/account/accomplishments/verify/ZXTFB22JQMJP)
- [Node.js Backend Development — EDUCBA](https://www.coursera.org/account/accomplishments/verify/5JUFXCQC65LG)
- [Advanced React — Meta](https://www.coursera.org/account/accomplishments/verify/KM5366AARAA8)
- [Data Analytics Essentials — Cisco](https://www.credly.com/badges/d49fcb8b-4c10-4093-a982-b0d890a8d52f/public_url)
- [Data Analysis & Visualization Foundations — IBM](https://coursera.org/share/fb564e687b918093a10fd4e4508277bc)
- [OCI Foundations Associate — Oracle](https://catalog-education.oracle.com/ords/certview/sharebadge?id=31549976ABA071736B2024DD8AAC36FD38F246AA3B93D9A26E5E3212843C0F71)

<br>

<div align="center">

**[→ Full portfolio with all experience, education, and dual dev/data views](https://arkaprava-ghosh-portfolio.netlify.app/)**

[LinkedIn](https://www.linkedin.com/in/arkaprava-ghosh-9255a1251) · [Email](mailto:arka792003@gmail.com) · [Twitter/X](https://x.com/arka_ghosh35042) · [LeetCode](https://leetcode.com/u/arka562/)

</div>
