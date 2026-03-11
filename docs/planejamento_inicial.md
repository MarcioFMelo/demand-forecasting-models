# Previsão de Demanda e Otimização de Estoque (Demand Forecasting)

## O Problema de Negócio
No setor de bens de consumo (FMCG) e varejo, a imprecisão na previsão de demanda gera dois problemas críticos: a ruptura de estoque (perda de vendas) ou o excesso de inventário (custos de armazenagem e risco de vencimento). 

Este projeto tem como objetivo desenvolver modelos estatísticos e de Machine Learning para prever a demanda futura de produtos, auxiliando a equipe de **Demand Planning** na tomada de decisão estratégica e garantindo o nível de serviço (SLA).

## Metodologia e Racional Analítico
Trazendo o rigor técnico da gestão de risco (ciências atuariais), a modelagem não foca apenas na acurácia do algoritmo, mas na **explicabilidade** (storytelling) do modelo para a área de negócios. 

A abordagem inclui:
1. **Análise Exploratória (EDA):** Identificação de sazonalidade, tendências e anomalias na série histórica.
2. **Engenharia de Features:** Incorporação de eventos externos (feriados, campanhas de marketing, ações da concorrência).
3. **Modelagem de Séries Temporais:** Comparação de modelos base (ARIMA/SARIMA) com algoritmos avançados (Prophet, XGBoost Regressor).
4. **Validação:** Monitoramento da assertividade (MAPE, RMSE) garantindo a robustez da solução.

## Stack Tecnológico
* **Linguagem:** Python (Pandas, Scikit-learn, Statsmodels)
* **Manipulação de Dados:** SQL / PySpark (simulando processamento de grandes volumes)
* **Governança:** Git e boas práticas de versionamento

## 🔄 Próximos Passos (Ciclo PDCA)
- [ ] Implementar pipeline automatizado para re-treinamento do modelo.
- [ ] Criar dashboard iterativo para os planejadores de demanda consumirem os insights.
- [ ] Adicionar variáveis macroeconômicas ao modelo preditivo.
