These are the code files for an AWS architecture that ingests earnings call transcript and news articles, then eventually upserts them into Iceberg tables. For a full description, see the accompanying Medium article: https://medium.com/p/261c44edd20a/edit

The folder structure is:
- Ingestion-layer: getting from data sources the financial texts
- Staging-layer: creating tables based on these financial texts
- Orchestration: calling services to do the above
