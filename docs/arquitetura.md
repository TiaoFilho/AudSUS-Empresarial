# Arquitetura de Dados - AudSUS Empresarial

## Camadas

- **Bronze**: Dados brutos convertidos do DATASUS (.dbc/.dbf → .parquet).
- **Silver**: Dados tratados e padronizados, com joins e validações aplicadas.
- **Gold**: Tabelas finais para consumo analítico e dashboards.

## Tecnologias simuladas

- Spark (Databricks ou EMR)
- Data Lake simulado no disco (ou em S3 futuramente)
- Orquestração futura com Airflow (opcional)
