# 👋 Hi, I'm Yoonseol (Winter) Jang

I build quantitative models, LLM agents, and large-scale data systems at the intersection of finance, ML, and engineering — currently a Mortgage Credit Risk Student Researcher at KKR, previously building LLM agents and data pipelines at Quantbot Technologies. Originally from South Korea 🇰🇷, based in New York City.

## 🚀 About Me

- 🎓 **M.S. in Data Science** @ *New York University* (2027)
- 📚 **B.A. in Data Science** @ *UC Berkeley*
- 🎯 **Focus:** Machine Learning & Statistical Inference · Quantitative Modeling · LLM Systems · Data Engineering
- 💼 **Career Interests:** Data Scientist · Quantitative Analyst · ML Engineer
- 🌍 **Location:** New York City, NY
- 📬 **Connect:** [LinkedIn](https://linkedin.com/in/yoonseol-jang) | [Email](mailto:y.seol0799@gmail.com)

---

## 📂 Featured Projects

[Quantitative Modeling](#quantitative-modeling) · [ML & Recommender Systems](#ml--recommender-systems) · [Applied ML & Engineering](#applied-ml--engineering)

### Quantitative Modeling

| Project | Description | Stack |
|---------|-------------|-------|
| 📊 **KKR — Mortgage Credit Risk Capstone** *(ongoing)* | Survival model predicting loan-level prepayment, default, and loss severity from borrower characteristics and macro drivers; outputs pool-level risk metrics for investor reporting | Snowflake, Survival Analysis, Gradient Boosting, Credit Risk Modeling |
| 📈 **[Portfolio Optimization with Convex Reformulations](https://github.com/yoonseol-jang/convex-portfolio-optimization)** | Reformulated Max Sharpe and CVaR as convex programs, raising the CVaR solve rate from 21% to 100%; found that 10 bps transaction costs let a passive 60/40 benchmark outperform both strategies | CVXPY, mpi4py, NumPy, LedoitWolf Covariance, Clarabel |
| ⛽ **Natural Gas Price Forecasting & Trading Analysis** | Forecasted Henry Hub natural gas prices from engineered weather, storage, and macro features; rolling walk-forward backtests showed strong week-ahead directional accuracy, with month-ahead reliability declining materially | SQL, Bloomberg, PCA, Time-Series Forecasting, Backtesting |

### ML & Recommender Systems

| Project | Description | Stack |
|---------|-------------|-------|
| 📚 **[Goodreads Recommendation System](https://github.com/yoonseol-jang/goodreads-recommendation-system)** | Book recommendation engine trained on 223M interactions, achieving 76% MAP improvement over a popularity baseline; LSH segmentation revealed tightly clustered reader cohorts | PySpark, ALS, Ranking Metrics, MinHash LSH, HDFS, GCP Dataproc |
| 🛒 **[Next-Basket Reorder Prediction & Controlled Error Analysis](https://github.com/yoonseol-jang/instacart-reorder-prediction)** | Benchmarked 5 grocery reorder models on 3.4M orders; found that the best model by item-level accuracy ranked differently at basket-level — the same data, a different metric, a different model ships | XGBoost, scikit-learn, Optuna, User-Grouped CV |

### Applied ML & Engineering

| Project | Description | Stack |
|---------|-------------|-------|
| 🌍 **NLP Classification Pipeline & Stakeholder Dashboard** | Classification pipeline for the World Bank to flag COVID-delayed infrastructure deals; 4-model ensemble reached 86% accuracy; findings delivered via an interactive dashboard | TF-IDF, Ensemble Methods, AWS EC2, CI/CD |
| 🚗 **[Distributed ETL & Count Regression on NYC Crash Data](https://github.com/yoonseol-jang/distributed-etl-urban-crash-analysis)** | Merged 10GB of NYC traffic, mobility, and weather data into a unified panel; found that snow raises hourly crash counts ~25% after controlling for traffic volume and time of day | Java, Hive SQL, Hadoop, GCP Dataproc, Negative Binomial |
| 🎓 **[Professor Effectiveness Analysis (RateMyProfessor)](https://github.com/yoonseol-jang/ratemyprofessor-analysis)** | Statistical analysis of 70K+ professor records; confirmed a gender rating gap and found that teaching style (caring, inspiring) predicted ratings better than difficulty or gender | Mann-Whitney U, Permutation Testing, Logistic Regression, Ridge Regression |

---

## ⚙️ Tech Stack

**Languages** · Python · SQL · R · Java · Bash

**ML & Modeling** · PyTorch · XGBoost · CVXPY · LLM Agents · RAG · Gradient Boosting · Survival Analysis · Time-Series Forecasting · Convex Optimization

**Data & Systems** · Apache Spark · Snowflake · HDFS · DuckDB · Parquet · SQL Server · AWS · Bloomberg · Git · GCP Dataproc

