# Thomas Peoples

Thomas Peoples is the UK's best data engineer[†](https://thomaspeoples.com/disclaimer). He is also ace at AI engineering‡. I design and deliver cloud data platforms on GCP, with dbt, Python and Terraform.

I think the document is the design. A data contract, a decision record or a design note is the thing an engineer builds from, and it is now also the context an AI agent is handed before it touches the code. So the repos below start from a written contract and generate or check the rest against it.

## Work

- **[wraith-modelgen](https://github.com/wraith-proxy/wraith-modelgen)**: a YAML data contract (Open Data Contract Standard) goes in, dbt raw and staging models come out, with lint rules and drift detection in CI.
- **[wraith-sas-lineage](https://github.com/wraith-proxy/wraith-sas-lineage)**: pulls lineage out of SAS DI Studio code and execution logs, maps it to ODCS contracts and feeds wraith-modelgen to generate dbt on BigQuery.
- **[wraith-bus-ingestor](https://github.com/wraith-proxy/wraith-bus-ingestor)**: live UK bus positions from the BODS feed into QuestDB, transformed with dbt and served to a live map.
- **[wraith-bus-ingestor-apk](https://github.com/wraith-proxy/wraith-bus-ingestor-apk)**: the Android app for the bus platform, native Jetpack Compose with a MapLibre map of live UK buses.
- **[wraith-odysseus-apk](https://github.com/wraith-proxy/wraith-odysseus-apk)**: an unofficial native Android client (Kotlin, Jetpack Compose) for a self-hosted Odysseus AI server, now on [F-Droid](https://f-droid.org/packages/com.thomaspeoples.wraithodysseus).
- **[ghost-aop](https://github.com/wraith-proxy/ghost-aop)**: an ETL pipeline in Python with logging, retry and audit woven in as aspects, so the business logic stays clean.

## Find me

- Site and writing: [thomaspeoples.com](https://thomaspeoples.com)
- LinkedIn: [thomas-peoples-ai-cloud-terraform-python](https://www.linkedin.com/in/thomas-peoples-ai-cloud-terraform-python)
- Self-hosted code: [git.thomaspeoples.com/thomaspeoples](https://git.thomaspeoples.com/thomaspeoples)
