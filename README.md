# Max Baldiviezo

**ML / Applied AI Engineer** · Santa Cruz, Bolivia (UTC−4, full US-hours overlap) · English, Spanish, Portuguese

I take machine learning models to production and measure whether they work. 3+ years shipping ML in telecom, consulting and startups: models that cut churn, LLM agents with evals, and the data pipelines underneath. Currently Data Specialist (Data Science & ML) at ixpantia.

## What I've built

- **LLM agents over a fintech's data warehouse (Claude API, MCP).** A text-to-SQL agent, deployed in the company's reporting app, where every query must pass a dry-run, a SELECT-only check, a table allowlist and a byte cap. Its evals recompute the right answer from the warehouse and compare models (Haiku vs Sonnet). Plus an MCP server that serves governed metrics from a semantic layer, with PII columns hidden and 14 tests in CI.
- **Valuation models in production for a real-estate platform.** Four XGBoost models (sale and rent) promoted through an MLflow registry, with a contract of metrics and library versions that the serving API checks before loading. Conformal prediction bands calibrated per price range (coverage from 72% to 80%), and a walk-forward backtest showing that random cross-validation understated error by 3.4 points.
- **Churn model in production at Tigo (multinational telecom).** Built from scratch on AWS (SageMaker, Athena) after replacing an external consultancy: −10% customer loss. Also lifted an upsell model's F1 by 19%, validated with A/B tests.
- **LLM features in an AI email-marketing SaaS.** A natural-language-to-HubSpot audience builder with type sanitization and fallback filtering, and a template mode that cut the output-token cap from 8,192 to 2,048.
- **Two dbt + BigQuery warehouses.** 100+ models and 350+ data-quality tests, with CI and daily runs on GitHub Actions, including SCD2 history of every listing.

Most of that lives in private repos. Public work:

| Project | What it shows |
| --- | --- |
| [TriloByte](https://github.com/Maxbm19/TriloByte) | **How well do LLMs understand Bolivian Quechua?** An eval pipeline with two independent methods (embedding similarity with a data-calibrated threshold, and an LLM judge). Finding: models answer in fluent but wrong Spanish. |
| [micunaSowProject](https://github.com/Maxbm19/micunaSowProject) | NASA Space Apps: an XGBoost model served through a Flask API that uses weather data to tell a farmer whether to plant. |

## Stack

- **ML:** Python, scikit-learn, XGBoost, Optuna, conformal prediction, Bayesian marketing mix modeling (Google Meridian), A/B testing
- **MLOps:** MLflow (tracking and model registry), Snakemake, GitHub Actions
- **LLMs:** Claude API, agents and tool use, MCP, LLM evals (deterministic scoring, LLM-as-judge), Langfuse, OpenTelemetry
- **Data and cloud:** SQL, dbt, BigQuery, Snowflake, AWS (SageMaker, Athena)

## Contact

[LinkedIn](https://linkedin.com/in/maxbaldiviezo)
