# Acidentes nas Rodovias Federais (PRF)

Projeto de Ciência de Dados seguindo o modelo CRISP-DM.
Disciplina: Ciência de Dados e Aprendizagem de Máquina.

## Objetivo

Usar os dados abertos da PRF para entender **quando** e **por que** acontecem os acidentes com mortes nas rodovias federais. A ideia é que a análise ajude a pensar em onde e em que horários a prevenção e a fiscalização são mais necessárias.

## Perguntas do projeto

**Pergunta 1:** Em que **dia da semana e horário** os acidentes **com mortes** mais acontecem?

**Pergunta 2:** Quais **causas** mais levam a mortes, e isso muda por **estado**?

## Como vamos responder

- Pergunta 1: contar os acidentes com mortes por dia da semana e por hora, e mostrar em um mapa de calor.
- Pergunta 2: somar os mortos por causa e por estado, e comparar em gráficos de barras, mapa do Brasil e mapa de calor.

## Dados

- Fonte: Dados Abertos da PRF (Polícia Rodoviária Federal)
- Link: https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf
- Período previsto: 2020 a 2025
- Formato: CSV "agrupados por ocorrência" (uma linha por acidente)

Os CSVs originais (`datatran2020.csv` a `datatran2025.csv`) ficam em `data/raw/`, sem nenhuma alteração.
Codificação: latin-1. Separador: `;`. Decimal: `,`.

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
