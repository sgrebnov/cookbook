# Spice.ai OSS Cookbook

The Spice.ai OSS Cookbook is a collection of recipes for building and deploying data & AI applications using Spice.ai. Each recipe is a self-contained example that demonstrates a specific use case or feature of Spice.ai.

## Recipes

### Core scenarios

- [Federated SQL Query](./federation/README.md) - Query data from S3, PostgreSQL, and Dremio in a single query.

### Models & AI - Connect data to hosted or local AI models

- [Azure OpenAI Models](./azure_openai/README.md)
- [LLM Memory](./llm-memory/README.md) - Persistent memory for language models.
- [Text to SQL (NSQL)](./nsql/README.md) - Ask natural language questions of your datasets.
- [Text to SQL (Tools)](./text-to-sql/README.md)
- [Nvidia NIM](./nvidia-nim/README.md) - Deploy Nvidia NIM infrastructure, on Kubernetes, with GPUs connected to Spice.
- [Searching GitHub Files](./search_github_files/README.md) - Search GitHub files with embeddings and vector similarity search.

### Data Acceleration - Materializing & accelerating data locally with Data Accelerators

- [DuckDB Data Accelerator](./duckdb/accelerator/README.md)
- [PostgreSQL Data Accelerator](./postgres/accelerator/README.md)
- [SQLite Data Accelerator](./sqlite/accelerator/README.md)
- [Apache Arrow Data Accelerator](./arrow/README.md)

### Consuming and visualizing data with clients

- [Sales BI (Apache Superset)](./sales-bi/README.md)

### Connecting to Data Sources with Data Connectors

- [Postgres Data Connector](./postgres/connector/README.md)
  - [AWS RDS PostgreSQL](./postgres/rds/README.md)
  - [Supabase](./postgres/supabase/README.md)
- [MySQL Data Connector](./mysql/connector/README.md)
  - [AWS RDS Aurora (MySQL Compatible)](./mysql/rds-aurora/README.md)
  - [PlanetScale](./mysql/planetscale/README.md)
- [Clickhouse Data Connector](./clickhouse/README.md)
- [Databricks Delta Lake Data Connector](./databricks/delta_lake/README.md)
- [Dremio Data Connector](./dremio/README.md)
- [DuckDB Data Connector](./duckdb/connector/README.md) - Use a DuckDB database with sample TPCH data.
- [File Data Connector](./file/README.md) - Query data from local files.
- [FTP Data Connector](./ftp/README.md) - Query data from an FTP server.
- [GitHub Data Connector](./github/README.md)
- [GraphQL Data Connector](./graphql/README.md)
- [MSSQL (Microsoft SQL Server) Data Connector](./mssql/README.md)
- [ODBC Data Connector](./odbc/README.md)
- [S3 Data Connector](./s3/README.md)
- [SharePoint/OneDrive for Business Data Connector](./sharepoint/README.md)
- [Snowflake Data Connector](./snowflake/README.md)
- [Spice.ai Cloud Platform Data Connector](./spiceai/README.md)
- [Apache Spark Data Connector](./spark/README.md)

### Connecting to Data Sources with Catalog Connectors

- [Spice.ai Cloud Platform Catalog Connector](./catalogs/spiceai/README.md)
- [Databricks Unity Catalog Connector](./catalogs/databricks/README.md)
- [Unity Catalog Connector](./catalogs/unity_catalog/README.md)

### Deployment and Installation

- [Deploying to Kubernetes](./kubernetes/README.md)

### Performance

- [TPC-H Benchmarking](./tpc-h/README.md)
- [Results Caching](./caching/README.md)
- [Indexes on Accelerated Data](./acceleration/indexes/README.md)

### Acceleration Data Refresh/Retention

- [Data Retention Policy](./retention/README.md)
- [Refresh Data Window](./refresh-data-window/README.md)
- [Advanced Data Refresh](./acceleration/data-refresh/README.md)

### Security

- [Encryption in transit using TLS](./tls/README.md)
- [API Key Authentication](./api_key/README.md)

### Advanced Topics

- [Local dataset replication](./localpod/README.md) - Link datasets in a parent/child relationship within the current Spicepod