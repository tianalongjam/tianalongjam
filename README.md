<!--
===================================================================================
  SETUP: Snake Contribution Graph (one-time, ~2 minutes)
  1. In this repo, go to Settings > Actions > General
     - Set "Workflow permissions" to "Read and write permissions"
  2. Create file: .github/workflows/snake.yml with this content:

  name: Generate Snake
  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: tianalongjam
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Go to Actions tab > "Generate Snake" > Run workflow
  4. The snake SVG will be committed to the `output` branch automatically.
===================================================================================
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hi,%20I'm%20Tiana%20(˶ˆᗜˆ˵)&animation=fadeIn&type=waving&color=gradient&customColorList=12,20,24&height=120&fontColor=ffffff&fontSize=42"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/tiana-longjam"><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/></a>
  &nbsp;&nbsp;
  <a href="mailto:longjam@wisc.edu"><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg"/></a>
  &nbsp;&nbsp;
  <a href="https://tianalongjam.github.io/"><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg"/></a>
  &nbsp;&nbsp;
  <a href="https://drive.google.com/file/d/1nVGfGoxgTpFd6Yrv8Sp36t_4xkG7q0ml/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-View%20PDF-6B46C1?style=flat-square&logo=googledrive&logoColor=white"/>
  </a>
  &nbsp;&nbsp;
  <img src="https://komarev.com/ghpvc/?username=tianalongjam&style=flat-square&color=A78BFA&label=profile+views"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&pause=1000&color=A78BFA&center=true&vCenter=true&width=620&lines=Data+Science+%26+Mathematics+%40+UW-Madison;ML+%7C+Scientific+Computing+%7C+Data+Engineering;Building+AI+that+actually+helps+people" alt="Typing SVG"/>
</p>

---

```yaml
name:        Tiana Longjam
school:      University of Wisconsin–Madison
majors:      Data Science & Mathematics
minor:       Business (Finance & Accounting)
graduating:  December 2026
currently:
  - Data Science Intern @ Infisum
  - UW–Madison SAIL Program — building SpeakEasy, an AI speech therapy
    companion for children worldwide (Summer 2026)
  - Undergraduate Research — Scientific Machine Learning & Numerical Methods
    (Neural Semi-Lagrangian methods for high-dimensional PDEs)
  - Previously: Data Science Intern @ Deloitte
interests:   Machine Learning, Scientific Computing, Data Engineering, Fair AI, Quant
certifications:
  - AWS Certified Cloud Practitioner
  - AWS ML Engineer – Associate (in progress)
looking_for: Full-time Data Science / ML Engineering roles (2026/2027)
```

---

## Tech Stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="42" height="42" title="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" width="42" height="42" title="R"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="42" height="42" title="Java"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="42" height="42" title="C"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="42" height="42" title="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="42" height="42" title="CSS3"/>
  <br/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="42" height="42" title="TensorFlow"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="42" height="42" title="PyTorch"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="42" height="42" title="Pandas"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="42" height="42" title="NumPy"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="42" height="42" title="scikit-learn"/>
  <br/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachespark/apachespark-original.svg" width="42" height="42" title="Apache Spark"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="42" height="42" title="Google Cloud"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="42" height="42" title="SQLite"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="42" height="42" title="PostgreSQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="42" height="42" title="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="42" height="42" title="Git"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="42" height="42" title="React"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neo4j/neo4j-original.svg" width="42" height="42" title="Neo4j"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="42" height="42" title="FastAPI"/>
</p>

---

## Featured Projects

### [SpeakEasy — AI Speech Therapy Companion](https://github.com/SahelAbraham/SpeakEasy) &nbsp; `Summer 2026 · SAIL Program`
WhatsApp-native AI speech therapy app built for 500+ underserved children worldwide. Integrates Twilio, OpenAI Whisper, a Mel Spectrogram + CNN pronunciation scorer, and a Contextual Bandit RL agent that adapts exercise selection in real time. Phoneme-level accuracy is tracked longitudinally in a **Neo4j Knowledge Graph**, with a progress dashboard surfacing fluency heatmaps for users and caregivers.

`Neo4j` `OpenAI Whisper` `CNN` `Contextual Bandit RL` `RAG` `wav2vec` `Twilio` `Python`

---

### [PrivacyLens](https://github.com/tianalongjam/PrivacyLens--CheeseHacks-Hackathon) &nbsp; `CheeseHacks 2026`
Full-stack privacy audit app that scans 30+ apps from a single phone screenshot and returns plain-English risk breakdowns in under 30 seconds. Dual-backend architecture (Flask for AI vision, FastAPI for scoring) using Google Gemini 2.5 Flash Vision API — achieving **90%+ app icon detection accuracy** across 37 apps. Risk scores are weighted against real permission + tracker data from the Exodus Privacy database.

`React` `FastAPI` `Flask` `Google Gemini` `Python`

---

### [Competitive Programming Analytics](https://github.com/tianalongjam/Competitive-Programming-Analytics)
Distributed analytics platform over 8,500+ problems and 170,000+ solutions. Bucketed Hive tables cut query latency by **85%**. A natural language to Spark SQL interface (Gemini API) lets users query the dataset in plain English. Includes a PySpark MLlib `DecisionTreeRegressor` pipeline that predicts missing difficulty scores across 10 tree depths.

`Apache Spark` `Hive` `PySpark MLlib` `Gemini API` `Python`

---

### [Wisconsin Census Population Predictor](https://github.com/tianalongjam/Wisconsin-Census-Population-Predictor)
Geospatial ML pipeline integrating GeoPandas, SQLite, and scikit-learn to predict county- and tract-level population from multi-source land-use and census data (GeoJSON, shapefiles, raster imagery). Features cross-validated regression models with interpretability analysis and interactive choropleth visualizations.

`GeoPandas` `scikit-learn` `SQLite` `Python`

---

### [Bias & Source Diversity Checker](https://github.com/tianalongjam/search-engine-with-exa-ai)
Analyzes search engine results for bias and source concentration using HHI, Gini index, and Shannon entropy across 50+ Exa API results per query. HuggingFace Transformer models surface domain-level sentiment skew via heatmaps and bar charts.

`Python` `Exa AI API` `HuggingFace` `NLP`

---

### [Loan Insights & Fair Lending Analysis](https://github.com/tianalongjam/loans_analysis)
Custom OOP + BST framework to analyze 25,000+ Wisconsin HMDA mortgage applicants, surfacing racial lending disparities and interest rate distributions. BST-indexed lookups benchmarked against linear scan across 15,000+ loans, visualizing O(log n) vs. O(n) performance gap.

`Python` `OOP` `BST` `Data Visualization`

---

### [Reflect — Mental Health Companion](https://github.com/tianalongjam/Reflect-MadHacks) &nbsp; `MadData 2026`
Full-stack mental wellness app with 4 core features: facility finder, mood tracker, AI journal, and streak tracker. Google Maps Distance Matrix + Geocoding APIs power real-time proximity sorting across **8,319 SAMHSA-verified facilities**. PostgreSQL on Supabase was populated by parsing 60+ SAMHSA service codes into queryable boolean columns.

`React` `Vite` `Express` `Supabase` `PostgreSQL` `Google Maps API`

---

### [Cloud-Based Geospatial School Analytics Pipeline](https://github.com/tianalongjam/Cloud-Based-Geospatial-School-Analytics-Pipeline-)
End-to-end GCP pipeline across 4 services (GCS, Dataform, BigQuery, GCP VMs) processing 2,000+ Wisconsin schools. BigQuery geospatial SQL maps nearest-school relationships across all 72 counties. Three dependency-managed Dataform pipelines automate raw Parquet to geospatial table transformation.

`GCP` `BigQuery` `Dataform` `GCS` `SQL`

---

### [F1 Point Systems Analysis](https://github.com/tianalongjam/f1_point_systems)
Investigates how old vs. new Formula 1 scoring systems affect championship dynamics, with a focus on midfield competitiveness — using real race data and simulated re-scoring across seasons.

`Python` `Data Analysis` `Visualization`

---

## What I'm Working On

| Project | Description |
|--------|-------------|
| **SpeakEasy** | AI speech therapy companion (SAIL Program, Summer 2026) |
| **Neural Semi-Lagrangian Research** | Scientific ML for high-dimensional PDEs — 50x L-inf error improvement over baselines |
| **AWS ML Engineer – Associate** | Certification in progress |

---

## Beyond the Code

```yaml
communities:
  - WiCS (Women in Computer Science) — Events Lead
  - MadData — Organizer
  - ML Reading Group — Member
  - RangDe Dance
fun_facts:
  - I study PDEs for fun (no, really)
  - F1 fan who actually ran the numbers on whether the scoring system is fair
  - Atomic Habits reader turned morning routine builder
```

---

## Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tianalongjam/tianalongjam/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tianalongjam/tianalongjam/output/github-contribution-grid-snake.svg"/>
  <img alt="Snake animation of GitHub contribution graph" src="https://raw.githubusercontent.com/tianalongjam/tianalongjam/output/github-contribution-grid-snake.svg"/>
</picture>

> The snake updates daily via GitHub Actions. See setup instructions in this file's source if it isn't running yet.

---

## Let's Connect

<p align="left">
  <a href="mailto:longjam@wisc.edu">
    <img src="https://img.shields.io/badge/Email-longjam%40wisc.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://tianalongjam.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-tianalongjam.github.io-4A90D9?style=for-the-badge&logo=githubpages&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://drive.google.com/file/d/1nVGfGoxgTpFd6Yrv8Sp36t_4xkG7q0ml/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-View%20%2F%20Download-6B46C1?style=for-the-badge&logo=googledrive&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/tiana-longjam">
    <img src="https://img.shields.io/badge/LinkedIn-tiana--longjam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tianalongjam&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=80&section=footer"/>
</p>
