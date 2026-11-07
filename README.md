# Acidentes nas Rodovias Federais (PRF)

Projeto de Ciência de Dados seguindo o modelo CRISP-DM.
Disciplina: Ciência de Dados e Aprendizagem de Máquina.

## Perguntas do projeto

1. Em que **dia da semana e horário** os acidentes **com mortes** mais acontecem?
2. Quais **causas** mais levam a mortes, e isso muda por **estado**?

## Dados

- Fonte: Dados Abertos da PRF (Polícia Rodoviária Federal)
- Link: https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf
- Período previsto: 2020 a 2025
- Formato: CSV "agrupados por ocorrência" (uma linha por acidente)

Os CSVs originais ficam em `data/raw/` e não são enviados ao GitHub (ver `.gitignore`).

## Estrutura

```
├── data/
│   ├── raw/          dados originais da PRF
│   └── processed/    dados limpos
├── notebooks/        um notebook por fase do CRISP-DM
├── sql/              consultas (se usarmos)
├── dashboard/        prints dos gráficos
├── docs/             relatório e dicionário de dados
├── requirements.txt
└── README.md
```

## Fases do CRISP-DM

| Fase | Notebook | Status |
|------|----------|--------|
| 1. Entendimento do Negócio | `01_negocio.ipynb` | em andamento |
| 2. Entendimento dos Dados | `02_dados.ipynb` | pendente |
| 3. Preparação dos Dados | `03_preparacao.ipynb` | pendente |
| 4. Modelagem | `04_modelagem.ipynb` | pendente |
| 5. Avaliação | `05_avaliacao.ipynb` | pendente |
| 6. Implementação | `docs/` | pendente |

## Gráficos planejados

Mapa de calor, linhas, barras horizontais, lollipop, mapa do Brasil e treemap.
Não usamos gráfico de pizza.

## Ferramentas

Python, pandas, seaborn, plotly e matplotlib.

## Autoria

Anna Oki
