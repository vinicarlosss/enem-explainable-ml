# ENEM – Análise do Desempenho Escolar com Explainable AI (XAI)

Este repositório contém os códigos e análises desenvolvidos no âmbito do Trabalho de Conclusão de Curso (TCC), cujo objetivo é aplicar técnicas de **Aprendizado de Máquina Explicável (Explainable Artificial Intelligence – XAI)** para analisar fatores socioeconômicos e educacionais associados ao desempenho de estudantes no **Exame Nacional do Ensino Médio (ENEM)**.

A pesquisa investiga como variáveis socioeconômicas influenciam o desempenho médio dos alunos, com foco especial na **faixa de renda familiar**, utilizando modelos interpretáveis e métodos de explicação baseados em SHAP.

---

## 📌 Objetivo do Trabalho

O objetivo principal deste trabalho é:

- Modelar a relação entre características socioeconômicas e educacionais dos estudantes e seu desempenho no ENEM;
- Utilizar **Árvores de Decisão** como modelo de classificação;
- Aplicar **SHAP (SHapley Additive exPlanations)** para interpretar as decisões do modelo;
- Avaliar a importância das variáveis para cada **classe de renda**, promovendo **transparência, interpretabilidade e análise crítica dos resultados**.

---

## 📊 Dados Utilizados

Os dados utilizados são provenientes dos **microdados do ENEM**, disponibilizados pelo INEP, referentes aos anos de:

- **2018**
- **2019**
- **2023**

Cada ano é analisado de forma **independente**, respeitando possíveis diferenças estruturais nos dados, garantindo maior clareza metodológica e reprodutibilidade dos resultados.

---

## 📁 Estrutura do Repositório

```text
.
├── arvore_decisao_2018.ipynb
├── arvore_decisao_2019.ipynb
├── arvore_decisao_2023.ipynb
├── README.md
