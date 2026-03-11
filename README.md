# 📈 Case: Previsão de Demanda para Planejamento de Estoque (FMCG)

## 📋 Sumário Executivo (Resultados Reais)
Este projeto desenvolveu um motor de previsão para o item "Achocolatado 400g", utilizando 3 anos de histórico semanal. 

* **Modelo Vencedor:** Holt-Winters (MAPE de **5.47%**).
* **Impacto:** Redução potencial de 10% no estoque de segurança devido à alta acurácia.
* **Diagnóstico:** Resíduos validados com distribuição normal (média próxima a zero).

---

## 🎯 Definição do Projeto (O que foi planejado)
No setor de bens de consumo (FMCG), a imprecisão na demanda gera ruptura ou excesso de inventário. Este projeto auxilia a equipe de **Demand Planning** na tomada de decisão estratégica.

### Metodologia e Racional Analítico
Trazendo o rigor técnico da gestão de risco (ciências atuariais), a abordagem incluiu:
1. **Análise Exploratória (EDA):** Identificação de sazonalidade e tendências.
2. **Modelagem:** Comparação entre Holt-Winters e SARIMA.
3. **Validação:** Monitoramento de MAPE e RMSE e Análise de Resíduos.

### 🛠️ Stack Tecnológico
* **Linguagem:** Python (Pandas, Scikit-learn, Statsmodels)
* **Governança:** Git e Ambientes Virtuais (Venv)

---
## 🔄 Ciclo PDCA (Próximos Passos)
- [x] Implementar modelos base (H-W e SARIMA).
- [ ] Implementar pipeline automatizado para re-treinamento.
- [ ] Adicionar variáveis macroeconômicas (Ex: IPCA, Câmbio).