# Explorando IA Generativa em um Pipeline de ETL com Python

Este projeto implementa um pipeline **ETL (Extract, Transform, Load)** para processamento de dados de vendas, integrando **IA Generativa** para gerar insights automáticos.

## 🚀 Funcionalidades
- **Extract:** leitura de dados brutos de vendas em CSV.
- **Transform:** limpeza, cálculo de totais e padronização dos dados.
- **Load:** exportação para um Data Warehouse simulado (arquivo final).
- **IA Generativa:** criação de resumos automáticos dos resultados para apoiar decisões.

## 📂 Estrutura
- `src/` → módulos ETL (extract, transform, load, pipeline).
- `ai/` → módulo de IA generativa para insights.
- `data/` → arquivos de entrada e saída.

## ▶️ Execução
```bash
python src/pipeline.py
