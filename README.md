## Estrutura inicial

- `ProjetoIV_dengue.ipynb`: notebook principal (Colab) com todo o fluxo:
  1. Montagem do Google Drive e organização das pastas
  2. Registro das URLs oficiais do OpenDataSUS
  3. Leitura dos CSVs brutos em chunks
  4. Criação de um único banco concatenado em Parquet
  5. Inspeção leve e resumos automáticos

- `data/` (não incluído aqui): contém os arquivos brutos e processados, armazenados no Google Drive.  
   Arquivos grandes (CSV/Parquet) não são enviados para o GitHub.

## Como usar

1. Abra o notebook no Google Colab.  
2. Monte o Google Drive e ajuste o caminho da pasta do projeto.  
3. Execute as células em ordem para gerar o parquet consolidado.  
4. Use o parquet salvo em `processed/` para análises rápidas e leves.

---
