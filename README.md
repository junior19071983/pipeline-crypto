# \# Pipeline Crypto - Databricks + Delta Lake

# 

# Pipeline de dados end-to-end com dados reais de criptomoedas.

# 

# \## Stack

# \- Python + requests — coleta via API CoinGecko com paginação

# \- Apache Spark + PySpark — processamento distribuído

# \- Delta Lake — armazenamento ACID com Time Travel

# \- Databricks — orquestração e jobs automáticos

# 

# \## Arquitetura Medallion

# \- Bronze → dados brutos da API

# \- Silver → dados limpos e tipados

# \- Gold  → agregações prontas para dashboard

# 

# \## Resultado

# \- 100 moedas analisadas

# \- Maior alta 24h: +22,27% (Dash)

# \- Maior queda 24h: -22,41% (Bittensor)

# \- Pipeline agendado todo dia às 8h automaticamente

