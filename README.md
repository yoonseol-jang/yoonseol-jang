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

| Project | Description |
|---------|-------------|
| 📊 **KKR — Mortgage Credit Risk Capstone** *(ongoing)* <br> `Snowflake` `Survival Analysis` `Gradient Boosting` | Prepayment, default, and severity don't happen independently in a mortgage pool: they compete. Modeling each outcome at loan level from borrower characteristics and macro drivers to build pool-level risk projections for investor reporting |
| 📈 **[Portfolio Optimization with Convex Reformulations](https://github.com/yoonseol-jang/convex-portfolio-optimization)** <br> `CVXPY` `Convex Optimization` `CVaR` `MPI` | CVaR optimization breaks down in practice; standard solvers converge on roughly 1 in 5 rebalance dates. Reformulated as a convex program to fix that, then stress-tested across 1,080 configurations to find where optimized strategies actually beat a passive index |
| ⛽ **Natural Gas Price Forecasting & Trading Analysis** <br> `Python` `PCA` `Regression Analysis` `Bloomberg` | Weather, storage cycles, and macro shifts all move natural gas prices — but which signals hold up when forecasting a week out versus a month? Built a model from each source and validated with walk-forward backtests to map where predictability breaks down |

### ML & Recommender Systems

| Project | Description |
|---------|-------------|
| 📚 **[Goodreads Recommendation System](https://github.com/yoonseol-jang/goodreads-recommendation-system)** <br> `PySpark` `ALS` `MinHash LSH` `GCP Dataproc` | Popularity-based recommendation is the simplest baseline imaginable. Built a collaborative filtering engine on 223M interactions to see how far it could be beaten, and whether readers cluster into meaningful segments at that scale |
| 🛒 **[Next-Basket Reorder Prediction & Controlled Error Analysis](https://github.com/yoonseol-jang/instacart-reorder-prediction)** <br> `XGBoost` `Grid Search` `Hyperparameter Tuning` | Whether the same model is "best" depends on how you measure. Benchmarked 5 grocery reorder models on 3.4M orders and found that rankings reversed between item-level and basket-level evaluation |

### Applied ML & Engineering

| Project | Description |
|---------|-------------|
| 🌍 **NLP Classification Pipeline & Stakeholder Dashboard** <br> `TF-IDF` `Logistic Regression` `Node.js` `AWS EC2` | COVID disrupted hundreds of infrastructure deals worldwide, but tracking them meant reading thousands of news sources manually. Built an end-to-end classification pipeline for the World Bank to surface them automatically, with findings delivered through an interactive dashboard |
| 🚗 **[Distributed ETL & Count Regression on NYC Crash Data](https://github.com/yoonseol-jang/distributed-etl-urban-crash-analysis)** <br> `Hadoop` `Hive SQL` `Negative Binomial` `GCP Dataproc` | How much do crashes actually rise in snow, once you account for fewer cars being on the road? Merged 10GB of NYC collision, mobility, and weather data to isolate the independent effect of adverse weather |
| 🎓 **[Professor Effectiveness Analysis (RateMyProfessor)](https://github.com/yoonseol-jang/ratemyprofessor-analysis)** <br> `Mann-Whitney U` `Permutation Testing` `Logistic Regression` `Ridge Regression` | Teaching behavior, gender, perceived attractiveness: all suspected drivers of professor ratings, but rarely tested together. Analyzed 70K+ records to separate which factors actually predict how students rate their professors |

---

## ⚙️ Tech Stack

**Languages** · Python · SQL · R · Java · Bash

**ML & Modeling** · PyTorch · XGBoost · CVXPY · LLM Agents · RAG · Gradient Boosting · Survival Analysis · Time-Series Forecasting · Convex Optimization

**Data & Systems** · Apache Spark · Snowflake · HDFS · DuckDB · Parquet · SQL Server · AWS · Bloomberg · Git · GCP Dataproc
