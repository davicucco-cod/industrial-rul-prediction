# Previsão de Vida Útil (RUL) de Máquinas Industriais

## Sobre o Projeto
Diferente da classificação binária (Quebra/Não Quebra), este projeto de **Regressão** estima o **tempo exato restante** (Remaining Useful Life - RUL) de uma máquina antes da falha.

O objetivo é permitir um planejamento de manutenção preditiva mais preciso.

## Resultados (Engenharia)
* **Algoritmo:** Random Forest Regressor.
* **R² (Explicação da Variância):** 98% (O modelo entendeu a física do desgaste).
* **MAE (Erro Médio Absoluto):** ~4.5 horas.
    * *Significado:* O modelo consegue prever a hora da quebra com uma margem de erro de apenas 4 horas e meia.

## Stack
* Python, Pandas, Scikit-Learn.
* Análise de Correlação (Pearson) e Heatmaps.
* Simulação de cenários de desgaste térmico e mecânico.

---
*Desenvolvido por Davi Cucco | [LinkedIn](https://www.linkedin.com/in/davi-duarte-cucco-8b272a238/)*
