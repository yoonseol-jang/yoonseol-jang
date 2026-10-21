# 👋 Hi, I'm Yoonseol (Winter) Jang

I build predictive models, LLM agents, and data pipelines for financial and behavioral data. I'm an M.S. in Data Science student at NYU, working on mortgage risk modeling through a capstone with KKR. Previously, I developed LLM agents and data pipelines as a Data Trading Analyst Intern at Quantbot Technologies.

## 🚀 About Me

- 🎓 **M.S. in Data Science** @ *New York University* (2027)
- 📚 **B.A. in Data Science** @ *UC Berkeley*
- 💼 **Career Interests:** Data Scientist · Quantitative Analyst · ML Engineer
- 🌍 **Location:** New York City, NY
- 📬 **Connect:** [LinkedIn](https://linkedin.com/in/yoonseol-jang) | [Email](mailto:y.seol0799@gmail.com)

---

## 📂 Featured Projects

[Currently Working On](#currently-working-on) · [Quantitative Modeling](#quantitative-modeling) · [ML & Recommender Systems](#ml--recommender-systems) · [Applied ML & Engineering](#applied-ml--engineering)

### Currently Working On

| Project | Description |
|---------|-------------|
| **KKR — Mortgage Prepayment & Credit Risk Modeling** <br> *NYU MSDS Capstone · In progress* <br> `Python` `SQL` `Snowflake` | Developing loan-level models to predict non-QM mortgage prepayment and default probabilities and estimate loss severity using monthly performance data and macroeconomic indicators. Investigating how refinancing incentives, prepayment penalties, and borrower characteristics influence outcomes. |
| **Do Fine-Tuned LLMs Follow the Document or Their Memory?** <br> *NLP Research · In progress* <br> *Planned:* `Python` `PyTorch` `Llama 3.2` `LoRA` `FinQA` | Investigating whether fine-tuning on questions a model can already answer without documents reduces its reliance on supplied evidence. Comparing base Llama 3.2 3B with two LoRA conditions using modified numerical evidence. |

### Quantitative Modeling

| Project | Description |
|---------|-------------|
| **[Portfolio Optimization with Transaction Costs](https://github.com/yoonseol-jang/convex-portfolio-optimization)** <br> `Python` `CVXPY` `MPI` | Reformulated Max-Sharpe and CVaR optimization as convex programs, improving CVaR solver reliability from ~21% to 100% in backtests. Evaluated portfolio performance under transaction costs. |
| **Natural Gas Price Forecasting** <br> `Python` `PCA` `Regression` `Bloomberg` | Forecasted natural gas prices using weather, storage, and macroeconomic indicators. Combined PCA and regression with walk-forward validation across forecast horizons. |

### ML & Recommender Systems

| Project | Description |
|---------|-------------|
| **[Book Recommendation System](https://github.com/yoonseol-jang/goodreads-recommendation-system)** <br> `PySpark` `ALS` `MinHash LSH` `GCP Dataproc` | Implemented a distributed recommendation pipeline for a dataset of 223M user–book interactions using PySpark on GCP Dataproc. On a reproducible 3% user sample, implicit ALS improved MAP by 76% over a popularity baseline. |
| **[Grocery Reorder Prediction (Instacart)](https://github.com/yoonseol-jang/instacart-reorder-prediction)** <br> `Python` `scikit-learn` `XGBoost` `Cross-Validation` | Compared five grocery reorder models using 37 shared features and user-grouped cross-validation, with random forest achieving held-out ROC-AUC of 0.91. Examined how item-level and basket-level metrics affect model selection. |

### Applied ML & Engineering

| Project | Description |
|---------|-------------|
| **Infrastructure Disruption Detection from News** <br> `TF-IDF` `Logistic Regression` `K-means` `AWS EC2` | Automated the identification of COVID-related infrastructure-project disruptions from news for a World Bank project. Combined text classification and clustering with an interactive monitoring dashboard. |
| **[NYC Traffic Crash Analysis](https://github.com/yoonseol-jang/distributed-etl-urban-crash-analysis)** <br> `Hadoop` `Hive` `GCP Dataproc` `Negative Binomial` | Integrated collision, traffic, ride-hailing, and weather data using Hadoop and Hive on GCP Dataproc. Estimated associations between adverse weather and hourly crash counts through count regression, controlling for traffic volume and time of day. |
| **[Professor Rating Analysis (RateMyProfessor)](https://github.com/yoonseol-jang/ratemyprofessor-analysis)** <br> `Permutation Testing` `Logistic Regression` `Ridge Regression` | Examined rating differences and predictors across 70,000+ professor records using hypothesis tests and regression. Modeled average ratings and students' willingness to take a professor again using teaching tags and other observed characteristics. |

---

## ⚙️ Tech Stack

**Languages** · Python · SQL · R · Java · Bash

**ML & Analytics** · pandas · NumPy · scikit-learn · PyTorch · XGBoost · CVXPY · NLP · LLM Agents · RAG · Time-Series Forecasting

**Data & Systems** · Apache Spark · Hadoop · Hive · Snowflake · DuckDB · Parquet · SQL Server · GCP Dataproc · AWS EC2 · Git

**Market Data** · Bloomberg · S&P Global
