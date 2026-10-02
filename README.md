# Max Baldiviezo

**ML / Applied AI Engineer** · Santa Cruz, Bolivia (UTC−4, full US-hours overlap) · English, Spanish, Portuguese

I take machine learning models to production and measure whether they work. 3+ years shipping ML in telecom, consulting and startups: models that cut churn, LLM features with evals and tracing, and the data pipelines underneath. Currently Data Specialist (Data Science & ML) at ixpantia.

## What I've shipped

- **LLM evaluation and observability for a live AI SaaS (Claude API).** Langfuse / OpenTelemetry tracing from each API endpoint to every model call, with PII masking and per-request latency, token and cost tracking. A prompt-evaluation harness with deterministic scoring to compare prompt versions.
- **Churn model in production at Tigo (multinational telecom).** Built from scratch on AWS (SageMaker, Athena) after replacing an external consultancy: −10% customer loss. Also lifted an upsell model's F1 by 19%, validated with A/B tests.
- **Automated valuation model serving a live real-estate platform.** scikit-learn and XGBoost tuned with Optuna, leakage-safe out-of-fold validation, open geospatial features, reproducible with Snakemake and MLflow. The valuation is exposed as MCP tools so an LLM agent can price a listing from its URL.
- **Data warehouse for a fintech.** Python ELT into BigQuery + dbt (37 models), run daily on GitHub Actions with 145+ data-quality tests.

Most of that lives in private client repos. Public work:

| Project | What it shows |
|---|---|
| [TriloByte](https://github.com/Maxbm19/TriloByte) | **How well do LLMs understand Bolivian Quechua?** An eval pipeline with two independent methods (embedding similarity with a data-calibrated threshold, and an LLM judge). Finding: models answer in fluent but wrong Spanish. |
| [micunaSowProject](https://github.com/Maxbm19/micunaSowProject) | NASA Space Apps: an XGBoost model served through a Flask API that uses weather data to tell a farmer whether to plant. |

## Stack

- **ML:** Python, scikit-learn, XGBoost, Optuna, A/B testing
- **MLOps:** MLflow, Snakemake, GitHub Actions
- **LLMs:** Claude API, LLM evals (deterministic scoring, LLM-as-judge), Langfuse, OpenTelemetry, MCP
- **Data and cloud:** SQL, dbt, BigQuery, Snowflake, AWS (SageMaker, Athena)

## Contact

[LinkedIn](https://linkedin.com/in/maxbaldiviezo)
