# 🌽 Challenge Ingredion – Sprint 3

## 🧠 Validação Estatística de Modelo Preditivo de Produtividade Agrícola

Este repositório contém a entrega da Sprint 3 do Challenge Ingredion, cujo objetivo foi validar, por meio de análise estatística, um modelo de Inteligência Artificial treinado para prever a produtividade agrícola de milho com base em índices de vegetação (NDVI).

---

## 📌 Objetivo da Sprint

Correlacionar previsões de produtividade agrícola com dados reais da safra 2023/2024 em Minas Gerais, utilizando técnicas estatísticas como:

- Correlação de Pearson e Spearman
- Regressão Linear Simples
- Visualizações comparativas

---

## 📂 Estrutura do Projeto
```
challenge-ingredion-sprint3/
│
├── 📁 data/
│   └── dados_milho_mg_2023_2024.xlsx       # Dados utilizados na análise
│
├── 📁 figures/
│   ├── grafico_dispersao_ndvi_produtividade.png
│   └── grafico_barras_real_vs_predito.png
│
├── 📁 notebooks/
│   └── analise_sprint3.ipynb                    # Notebook Colab com o código
│
├── 📄 Relatorio_Tecnico_Sprint3.pdf             # Relatório final em PDF
└── 📄 README.md                                 # Documentação principal do projeto
```

---

## 🔬 Métodos Utilizados

- **Correlação de Pearson:** r = 0.72 (p < 0.05)
- **Correlação de Spearman:** r = 0.75 (p < 0.05)
- **Regressão Linear:**  
  - y = 5511.18 × NDVI + 2532.84  
  - R² = 0.51

---

## 📈 Visualizações

- Gráfico de dispersão entre NDVI e produtividade
- Gráfico de barras comparando produtividade real e predita por município

---

## 📑 Relatório Técnico

Disponível em [`Relatorio_Tecnico_Sprint3.pdf`](Relatorio_Tecnico_Sprint3.pdf).  
Inclui metodologia, análise estatística, gráficos e propostas de melhoria.

---

## 🔗 Fontes de Dados

- [CONAB – Série Histórica de Safras](https://portaldeinformacoes.conab.gov.br/safra-serie-historica-graos.html)
- [Embrapa SatVeg – NDVI](https://www.satveg.cnptia.embrapa.br)

---

## 👥 Autores

- Matheus Augusto Rodrigues Maia – RM560683  
- Alex da Silva Lima – RM559784  
- Johnatan Sousa Macedo Loriano – RM559546  
- Bruno Henrique Nielsen Conter – RM560518  
- Fabio Santos Cardoso – RM560479
