# Geocodificacao

Este notebook realiza a padronização, geocodificação e enriquecimento de endereços da cidade de São Paulo com base em shapefile e serviços SOAP da Prefeitura.

## Funcionalidades
- Padroniza nomes de logradouros conforme padrão PMSP
- Consulta `codlog` e coordenadas via serviços SOAP
- Enriquecimento com:
  - Tipo de via, Localidade, DET, GET, SUB, Região, Distrito
- Exportação dos dados em `.xlsx` e `.parquet`

## Tecnologias utilizadas
- Python
- Pandas, Geopandas, Shapely
- requests, xml.etree
- Shapefiles urbanos da PMSP

Criado por Vitor Henrique Leal Lopes Bráz
