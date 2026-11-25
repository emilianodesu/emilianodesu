<div align="center">
  <h1 align="center">嗨！I'm Emiliano and I build distributed data & ML systems =)</h1>
  <p align="center">
    <strong>Junior Data Engineer & AI/ML Engineer | Distributed Systems, Cloud Architecture & Reliability</strong><br>
    <em>Analytics Engineer Intern @ Nu Bank México · Ex-Amazon SDE Intern · UNAM 🇲🇽 & UTS 🇦🇺</em>
  </p>

  <p align="center">
    <a href="https://linkedin.com/in/emilianodesu"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://emilianodesu.github.io/nyc-mobility-data-platform/"><img src="https://img.shields.io/badge/HVFHV_Showcase-0F172A?style=for-the-badge&logo=duckdb&logoColor=FFF000" alt="HVFHV Showcase" /></a>
    <a href="https://emilianodesu.github.io/mx-weather-mos/"><img src="https://img.shields.io/badge/Weather_MOS_App-0F172A?style=for-the-badge&logo=leaflet&logoColor=34D399" alt="MX Weather MOS App" /></a>
    <a href="https://emilianodesu.github.io/spark-graph-ranking/"><img src="https://img.shields.io/badge/Spark_Graph_Showcase-0F172A?style=for-the-badge&logo=apachespark&logoColor=E25A1C" alt="Spark Graph Showcase" /></a>
    <a href="mailto:cemh.fi@comunidad.unam.mx"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

### About Me

- 🚀 Currently working as an **Analytics Engineer Intern at Nu Bank México**.
- 🛠️ Former **SDE Intern at Amazon México (Devices Team)**.
- 🎓 Completed 5 semesters of **Computer Engineering** at **Facultad de Ingeniería, UNAM** and completed 100% of coursework in **Data Science** at **IIMAS, UNAM**.
- 🇦🇺 Completed an international academic exchange at the **University of Technology Sydney (UTS)**, achieving **High Distinction (HD)** in Reinforcement Learning, Image Processing & Pattern Recognition, and **Distinction (D)** in Machine Learning.
- 👨‍🏫 Former **Training Core Member & Instructor at SIAFI UNAM**.

---

### Tech Stack & Tools

<div align="center">

| Domain | Technologies |
|---|---|
| **Data Engineering & Big Data** | `Apache Spark` `PySpark` `Databricks` `Scala` `DuckDB` `Dagster` `SQLite (CAS)` `PyArrow` `PostgreSQL / PostGIS` `Data Mesh` `ETL/ELT` |
| **Cloud & Platforms** | `AWS (S3, CloudWatch)` `Google Cloud (BigQuery, Cloud Storage)` `Microsoft Azure` `Docker` `GitHub Actions CI` `Linux CLI` |
| **Programming Languages** | `Python (Advanced)` `SQL (Distributed / Relational)` `Java` `Scala` `C++` `Bash / Shell Scripting` |
| **Machine Learning & Serving** | `LightGBM` `PyTorch` `Scikit-learn` `FastAPI` `Pydantic` `Pandas` `NumPy` `React + Leaflet` |

</div>

---

### Featured Engineering Platforms

#### 1. [NYC Mobility Data Reliability Platform (HVFHV)](https://github.com/emilianodesu/nyc-mobility-data-platform) · [Live Showcase](https://emilianodesu.github.io/nyc-mobility-data-platform/)
Production-grade single-machine batch data reliability platform processing **41.47M official NYC TLC HVFHV trip records** (Uber & Lyft). Built with **DuckDB 2.0**, transactional **SQLite Compare-and-Swap (CAS)** publication control, **Dagster 1.13** orchestration, and a read-only **Streamlit** console. Handled the 2025 NYC Congestion Pricing `24→25` column schema evolution with zero silent coercion, `0` WAL residuals, and **229 passing automated tests**.

#### 2. [MX Weather MOS — Forecast Verification & ML Bias-Correction Platform](https://github.com/emilianodesu/mx-weather-mos) · [Live App](https://emilianodesu.github.io/mx-weather-mos/)
100% Docker-reproducible operational geospatial & ML post-processing platform across **31 Mexican state capitals** (`n=3,410` holdout). Combines **PostgreSQL 16 + PostGIS**, **LightGBM quantile MOS** + **Isotonic rain calibration**, **FastAPI**, and a **WCAG 2.1 AAA React + Leaflet UI** — reducing temperature RMSE by **30.7%**, MAE by **16.8%**, and rain Brier score by **77.2%** vs. raw NWP (**71/71 CI/Docker tests**).

#### 3. [Spark Graph Ranking — Large-Scale PageRank & HITS Engine](https://github.com/emilianodesu/spark-graph-ranking) · [Live Showcase](https://emilianodesu.github.io/spark-graph-ranking/)
Production-grade **Apache Spark 3.5** Catalyst/Tungsten DataFrame engine implementing **PageRank**, **Topic-Sensitive PageRank**, and **HITS** over real Stanford SNAP graphs up to **4.85M nodes and 68.47M directed edges** (`soc-LiveJournal1`, `0 B` disk spill). Benchmarks head-to-head against a Python RDD baseline with Spark REST UI stage telemetry, achieving **4.34x–8.37x wall-time speedups** and machine-precision numerical equivalence ($L_1 \le 1.43 \times 10^{-16}$) verified against `NetworkX`.

---

<div align="center">
  <sub>Carlos Emiliano Mendoza Hernández · Let's connect on <a href="https://linkedin.com/in/emilianodesu">LinkedIn</a></sub>
</div>
