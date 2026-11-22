# Hi, I'm Shahzeb Ali

**Data Engineer based in Lahore | Open-Source Contributor**

I build reliable data pipelines, from ingestion to analytics-ready datasets. Day to day, that means ETL/ELT in Python and SQL, large-scale processing on Apache Spark and Databricks, and dimensional modeling, with a focus on getting incremental ingestion right: CDC, Delta Lake MERGE, and clean dbt transformations. I also hunt the bugs that do not crash. They quietly return the wrong answer.

## What I'm working on now

- Built the **Jira source connector for Galaxy's Filament**, which shipped in Filament **v0.46.0** (November 2026); now building the **Trello source connector** (in review)
- Contributing to **delta-rs** (Delta Lake, Rust) and maintaining my open pull requests across the data stack
- Research: fault-injection benchmarking for data quality monitoring, and CDC strategies on Delta Lake under late-arriving updates

## Open-source contributions: <!-- merged-prs -->24<!-- /merged-prs --> merged pull requests

| Project | Merged | Pull requests | What I contributed |
|---|---|---|---|
| [delta-io/delta-rs](https://github.com/delta-io/delta-rs) | 7 | [#4832](https://github.com/delta-io/delta-rs/pull/4832), [#4833](https://github.com/delta-io/delta-rs/pull/4833), [#4866](https://github.com/delta-io/delta-rs/pull/4866), [#4890](https://github.com/delta-io/delta-rs/pull/4890), [#4942](https://github.com/delta-io/delta-rs/pull/4942), [#4966](https://github.com/delta-io/delta-rs/pull/4966), [#5004](https://github.com/delta-io/delta-rs/pull/5004) | Correctness fixes: schema-merge nullability, pre-epoch timestamp statistics, TIMESTAMP UTC offset, validation error naming; docs on retention config, merge examples, and writer env vars |
| [kedro-org/kedro](https://github.com/kedro-org/kedro) | 3 | [#5808](https://github.com/kedro-org/kedro/pull/5808), [#5809](https://github.com/kedro-org/kedro/pull/5809), [#5828](https://github.com/kedro-org/kedro/pull/5828) | CachedDataset docs example, templating concept page rewrite, OmegaConfigLoader resolver fix |
| [apache/iceberg-python](https://github.com/apache/iceberg-python) | 4 | [#4135](https://github.com/apache/iceberg-python/pull/4135), [#4142](https://github.com/apache/iceberg-python/pull/4142), [#4144](https://github.com/apache/iceberg-python/pull/4144), [#4383](https://github.com/apache/iceberg-python/pull/4383) | Timestamp parser and predicate evaluation fixes; reject fractional strings converting to int/long |
| [apache/datafusion](https://github.com/apache/datafusion) | 1 | [#26489](https://github.com/apache/datafusion/pull/26489) | width_bucket bucket-computation dedup |
| [bytewax/bytewax](https://github.com/bytewax/bytewax) | 1 | [#637](https://github.com/bytewax/bytewax/pull/637) | Build info: `__version__`, `__git_revision__`, `__git_dirty__` |
| [galaxy-io/filament](https://github.com/galaxy-io/filament) | 1 | [#682](https://github.com/galaxy-io/filament/pull/682) | Jira source connector: 9 resources, incremental reads on `updated`, shipped in v0.46.0 |
| [open-metadata/docs-om](https://github.com/open-metadata/docs-om) | 2 | [#599](https://github.com/open-metadata/docs-om/pull/599), [#615](https://github.com/open-metadata/docs-om/pull/615) | OpenSearch FGAC permissions guide, dev container setup fix |
| [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | 1 | [#125739](https://github.com/ClickHouse/ClickHouse/pull/125739) | Version note for Replicated engine `default_replica_path` settings |
| [sqlfluff/sqlfluff](https://github.com/sqlfluff/sqlfluff) | 1 | [#8715](https://github.com/sqlfluff/sqlfluff/pull/8715) | Removed outdated Snowflake USING note from Rule ST07 |
| [airbytehq/airbyte](https://github.com/airbytehq/airbyte) | 1 | [#88468](https://github.com/airbytehq/airbyte/pull/88468) | Fixed dead low-code CDK sample connector links |
| [canonical/starbase](https://github.com/canonical/starbase) | 2 | [#638](https://github.com/canonical/starbase/pull/638), [#649](https://github.com/canonical/starbase/pull/649) | `llms.txt` description from `index.rst`; removed stale ruff overrides entries |

Also in review: [Filament #757](https://github.com/galaxy-io/filament/pull/757) (Trello source) and [#716](https://github.com/galaxy-io/filament/pull/716) (last_record pagination), [vLLM #68358](https://github.com/vllm-project/vllm/pull/68358) (detokenizer flush fix), [craft-cli #527](https://github.com/canonical/craft-cli/pull/527) (progress bar total-0 fix), [trino-python-client #654](https://github.com/trinodb/trino-python-client/pull/654), [delta-rs #5012](https://github.com/delta-io/delta-rs/pull/5012), [#5037](https://github.com/delta-io/delta-rs/pull/5037) and [#5098](https://github.com/delta-io/delta-rs/pull/5098) (MERGE with CDF fix), [dbt #16690](https://github.com/dbt-labs/dbt/pull/16690), [Airflow #74424](https://github.com/apache/airflow/pull/74424), and pull requests in Chroma, Apache Iceberg, lakeFS, and Canonical projects.

Previously validated the Databricks Zerobus sink for Galaxy's Filament, which shipped in Filament v0.24.0.

## Technical skills

- **Languages:** Python, SQL, Rust, Go
- **Data processing:** Apache Spark, Databricks, Delta Lake, dbt, Apache Airflow
- **Databases:** PostgreSQL, MS SQL Server, SSIS, SSAS
- **Data manipulation:** Pandas, NumPy
- **Architecture:** Medallion Architecture, CDC, Delta Lake MERGE, Dimensional Modeling
- **Testing and quality:** pytest, Rust tests, SQL validation

## Experience and education

- **Associate Data Engineer** — Alphabridge Consulting, Lahore (Aug – Sep 2026)
- **Teaching Assistant, DBMS & Data Warehousing / BI** — PUCIT, Lahore (Jan 2025 – Jan 2026)
- **Freelance Data Engineer** — Self-employed, remote (2023 – Present)
- **BS Data Science** — University of the Punjab, PUCIT (2022 – 2026)

## Connect with me

- **Blog:** [Medium — @shahzeb.dataengineer](https://medium.com/@shahzeb.dataengineer) — writing what I learn from open source
- **Email:** shahzebali1218@gmail.com

---

*Building reliable data pipelines, one PR at a time.*
