<img src="./assets/header.svg" alt="Omkar Gadhave · Data Analyst · HR analytics, MIS reporting and machine learning · Pune, India" width="100%">

<p>
  <a href="https://www.linkedin.com/in/omkar-gadhave-data/"><img src="https://img.shields.io/badge/LinkedIn-omkar--gadhave--data-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Open%20to-Data%20Scientist%20%C2%B7%20ML%20Engineer%20%C2%B7%20Data%20Analyst%20roles-2ea44f" alt="Open to Data Scientist, Machine Learning Engineer and Data Analyst roles"></p>

Data Analyst with four years in HR analytics, MIS reporting and data analysis. I also build machine learning models that are validated honestly and explained clearly; they ship with held-out results, the weak numbers included.

---

## Shipped in public

### Retention Intelligence · *ML engineering*

<table>
  <tr>
    <td width="55%">
      <a href="https://retention-intelligence-b3zd.onrender.com"><img src="https://raw.githubusercontent.com/OmkarG-Star/Retention-Intelligence/main/docs/screenshots/overview.png" alt="Retention Intelligence overview: weekly briefing, key numbers and every employee as one square sorted by risk"></a>
    </td>
    <td>
      Resignation early warning for an EPC workforce, from 7 to 180 days ahead.
      <br><br>
      At 30 days, the <b>top 15% flagged catch 57% of resignations</b> (PR-AUC 0.22 against a 4.1% base rate), validated on embargoed time splits.
      <br><br>
      <code>LightGBM</code> <code>SHAP</code> <code>Survival Analysis</code> <code>FastAPI</code> <code>Docker</code> <code>72 tests</code>
      <br><br>
      <a href="https://retention-intelligence-b3zd.onrender.com"><b>Live demo</b></a> · <a href="https://github.com/OmkarG-Star/Retention-Intelligence">Code</a>
    </td>
  </tr>
</table>

### Resume Intelligence · *ML / NLP*

<table>
  <tr>
    <td width="55%">
      <a href="https://resume-intelligence-hg1g.onrender.com"><img src="https://raw.githubusercontent.com/OmkarG-Star/AI-resume-analyzer/main/docs/screenshots/overview.png" alt="Resume Intelligence hiring overview: open roles, session activity and model health"></a>
    </td>
    <td>
      Explainable resume screening for recruiters, with per-score reasons and a four-fifths-rule fairness audit.
      <br><br>
      MiniLM sentence embeddings on ONNX, so there's <b>no PyTorch at runtime</b>. Accuracy is reported on held-out sets, including the weaker one.
      <br><br>
      <code>NLP</code> <code>ONNX</code> <code>FastAPI</code> <code>Docker</code> <code>57 tests</code> <code>CI</code>
      <br><br>
      <a href="https://resume-intelligence-hg1g.onrender.com"><b>Live demo</b></a> · <a href="https://github.com/OmkarG-Star/AI-resume-analyzer">Code</a>
    </td>
  </tr>
</table>

### Credit Risk on Real Lending Club Loans · *data science*

<table>
  <tr>
    <td width="55%">
      <a href="https://github.com/OmkarG-Star/AI-Credit-Risk-Decision-System"><img src="https://raw.githubusercontent.com/OmkarG-Star/AI-Credit-Risk-Decision-System/main/reports/figures/flag_by_grade.png" alt="Flagged loans earned lower returns than unflagged loans within Lending Club grades A to F in 2014"></a>
    </td>
    <td>
      Probability of default for 309,955 real loans, trained on 2007–2012 and tested on 136,967 loans from 2014.
      <br><br>
      Loans flagged as <b>riskier than their grade returned 7.6%</b> over three years against 9.5% for the rest. ROC-AUC 0.638 from application data alone, benchmarked against Lending Club's own grade.
      <br><br>
      <code>LightGBM</code> <code>Calibration</code> <code>Out-of-time validation</code> <code>PSI</code> <code>SHAP</code> <code>Streamlit</code>
      <br><br>
      <a href="https://credit-risk-lending-club.onrender.com"><b>Live demo</b></a> · <a href="https://github.com/OmkarG-Star/AI-Credit-Risk-Decision-System">Code</a>
    </td>
  </tr>
</table>

### Two-Wheeler Loan Risk on Real Indian Loans · *data science*

<table>
  <tr>
    <td width="55%">
      <a href="https://github.com/OmkarG-Star/india-two-wheeler-loan-risk"><img src="https://raw.githubusercontent.com/OmkarG-Star/india-two-wheeler-loan-risk/main/reports/figures/capture.png" alt="Reviewing the riskiest 19% of October 2018 loans catches 30% of first-EMI defaults"></a>
    </td>
    <td>
      Predicts missed first EMIs on 233,154 real L&amp;T Finance two-wheeler loans, tested on 98,364 loans from October 2018. Demo in rupees.
      <br><br>
      Reviewing the <b>riskiest fifth catches 30% of first-EMI defaults</b>. ROC-AUC 0.642 against 0.550 for the bureau band, with half the borrowers new to credit.
      <br><br>
      <code>LightGBM</code> <code>Calibration</code> <code>Out-of-time validation</code> <code>SHAP</code> <code>Streamlit</code>
      <br><br>
      <a href="https://india-loan-risk.onrender.com"><b>Live demo</b></a> · <a href="https://github.com/OmkarG-Star/india-two-wheeler-loan-risk">Code</a>
    </td>
  </tr>
</table>

### A/B Test: Game Retention Experiment · *statistics*

<table>
  <tr>
    <td width="55%">
      <a href="https://github.com/OmkarG-Star/ab-testing-game-retention"><img src="https://raw.githubusercontent.com/OmkarG-Star/ab-testing-game-retention/main/reports/figures/effects.png" alt="Moving the game's first gate to level 40 lowered 7-day retention by 0.82 points"></a>
    </td>
    <td>
      A real experiment on 90,189 players. Moving the first gate to level 40 <b>cut 7-day retention by 0.82 points</b> (p = 0.002).
      <br><br>
      Caught a sample ratio mismatch (p = 0.009) and showed the decision survives the worst case. Includes power analysis, Holm correction and a peeking simulation.
      <br><br>
      <code>Hypothesis testing</code> <code>Power analysis</code> <code>Bootstrap</code> <code>Bayesian</code>
      <br><br>
      <a href="https://ab-test-calculator-rmke.onrender.com"><b>Live calculator</b></a> · <a href="https://github.com/OmkarG-Star/ab-testing-game-retention">Code</a>
    </td>
  </tr>
</table>

### India Air Quality Data Platform · *data pipeline*

<a href="https://github.com/OmkarG-Star/india-air-quality-data-platform"><img src="./assets/aqp-pipeline.svg" alt="Pipeline: Open-Meteo API to Python ingestion to raw JSON and bronze Parquet layers to quality checks, built and running daily; Airflow, dbt and AQI forecasting are the next milestones" width="100%"></a>

Idempotent daily ingestion of hourly air-quality data for Indian cities into raw and bronze Parquet layers, with data-quality checks and per-city fault isolation. **[Code →](https://github.com/OmkarG-Star/india-air-quality-data-platform)**

`Python` `ETL` `Parquet` `Data Quality` `Pytest` `GitHub Actions`

<sub>Live demos run on a free plan, so the first load can take up to a minute.</sub>

<details>
<summary><b>Earlier projects</b></summary>
<br>

| Project | What it does | Stack |
|---|---|---|
| [Customer Segmentation Strategy](https://github.com/OmkarG-Star/AI-Customer-Segmentation-Strategy-System) | RFM + KMeans segments mapped to marketing actions | SQL · scikit-learn · Streamlit |
| [HR Analytics Dashboard](https://github.com/OmkarG-Star/HR-Analytics-Dashboard-PowerBI) | Attrition, salary and workforce insights | Power BI · DAX |

</details>

---

## How I work

- **Test on data I didn't tune on, and publish the bad numbers too.** My resume screener scored 57.9% on its second unseen set, and that number sits in the README next to the good ones.
- **Explainable by default.** Every prediction ships with the reasons behind it.
- **Production habits.** Idempotent loads, tests, CI on every push, Docker, and a live demo anyone can open without signing up.

## Stack

<img src="https://skillicons.dev/icons?i=py,fastapi,docker,githubactions,sklearn,react,ts,git&theme=light" alt="Python, FastAPI, Docker, GitHub Actions, scikit-learn, React, TypeScript, Git">

**Modelling:** LightGBM · scikit-learn · SHAP · Calibration · Survival Analysis · NLP · ONNX  
**Data:** Python · SQL · Pandas · DuckDB · Parquet · ETL · Data Quality  
**Serving & delivery:** FastAPI · REST APIs · Docker · Pytest · GitHub Actions · CI/CD  
**Analytics:** Power BI · DAX · React · TypeScript  
**Statistics:** A/B testing · Power analysis · Bootstrap · Calibration · PSI

---

Hiring for a Data Scientist, Machine Learning Engineer or Data Analyst role? [Message me on LinkedIn](https://www.linkedin.com/in/omkar-gadhave-data/).
