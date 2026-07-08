# 04 · Engenharia de Atributos em Dados de Saúde

Feature engineering aplicado ao dataset **Diabetes 130-US Hospitals** (~100 mil internações) para preparar os dados para estratificação de risco de readmissão hospitalar.

**Destaques:**

- Recategorização da variável alvo e de variáveis de ID com significado clínico
- Criação de atributo de **comorbidade** com base em conhecimento de domínio (códigos CID)
- Agregação de 23 variáveis de medicamentos em atributos de contagem e alteração de dosagem
- Recoding de variáveis categóricas

**Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn

> Dados: [Diabetes 130-US Hospitals (UCI ML Repository)](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008) — incluído como `dataset.zip` (descompacte antes de executar o notebook).
