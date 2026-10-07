# Tech Challenge – Análise E-commerce Olist

Projeto da Fase 1 da Pós-Tech FIAP em Data Analytics.

## Objetivo

A Olist apresenta crescimento nas vendas e satisfação de clientes que justifiquem investimentos na expansão da plataforma?

Perguntas de apoio:
- As vendas estão crescendo? -> Analisar a evolução mensal dos pedidos e valor vendido
- Os clientes estão satisfeitos? -> Analisar review score
- O que prejudica a satisfação de um cliente? -> Analisar prazo de entrega x review_score
- Onde estão as oportunidades? -> Olhar categorias e regiões com melhor/pior desempenho

## Dados

Brazilian E-Commerce Public Dataset by Olist, com cerca de 100 mil pedidos entre 2016 e 2018.

Fonte: [\[Kaggle\]](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Schema:
![Schema das tabelas](img/schema.png)

## Estrutura do repositório

- `notebooks/01_recon.ipynb`: reconhecimento das tabelas e decisões sobre os dados
- `notebooks/02_limpeza.ipynb`: limpeza e organização dos dados
- `data/raw`: pasta dos CSVs com dados brutos (não versionada)
- `data/processed`: pasta dos CSVs após as limpezas (não versionada)
- `img/`: imagens do projeto

## Como executar

1. Baixe os dados no Kaggle e coloque os CSVs na pasta `data/raw`
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute os notebooks na ordem numérica

## Resultados

Em construção.

## Autor

Alexandre Faizibaioff
LinkedIn: https://www.linkedin.com/in/alexandrecsf/
Portfólio: https://alexandrecsf.my.canva.site/