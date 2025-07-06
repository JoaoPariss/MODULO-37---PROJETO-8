# 🛒 Projeto: Previsão de Intenção de Compra de Clientes em Loja Web

## 📌 Descrição do Projeto

Neste projeto, o objetivo foi criar um sistema inteligente para prever a intenção de compra dos clientes em um site de e-commerce. A ideia é antecipar quais clientes têm maior probabilidade de realizar compras online com base em seus dados demográficos e comportamentais. Com isso, a empresa pode direcionar melhor suas estratégias de marketing e aprimorar a experiência dos usuários.

---

## 🎯 Objetivo

Desenvolver um modelo preditivo que analise os padrões de comportamento dos clientes e identifique sinais que indiquem a propensão à compra. A base de dados utilizada contém:

- Informações demográficas (idade, renda, etc.)
- Histórico de compras anteriores

---

## 🔎 ETAPA 1: Preparação dos Dados

- **Exploração e Limpeza**: Análise e tratamento dos dados para corrigir inconsistências e garantir qualidade.
- **Análise Exploratória**: Construção de uma narrativa visual com gráficos e geração de insights relevantes sobre os dados.

---

## ⚙️ ETAPA 2: Pré-processamento

- **Correlação**: Verificação das correlações entre as variáveis para avaliar possíveis exclusões.
- **Codificação de Variáveis Categóricas**: Transformação das variáveis categóricas em formato numérico.
- **Separação da Base**: Definição das variáveis `X` (features) e `y` (target), e divisão entre treino e teste.
- **Padronização**: Aplicação da padronização dos dados para melhorar a performance dos modelos.

---

## 🤖 ETAPA 3: Modelagem

- Foram testadas duas técnicas de machine learning para resolver o problema de classificação binária:
  - **Regressão Logística**
  - **Random Forest Classifier**

---

## 📊 Avaliação

- Ambos os modelos foram avaliados com métricas de desempenho como precisão, recall, f1-score e acurácia.
- Também foi utilizada a **matriz de confusão** para entender os acertos e erros de cada classe.
- O modelo **Random Forest** obteve os melhores resultados, com maior acurácia e melhor equilíbrio entre precisão e recall.

---

## ✅ Conclusão

O projeto permitiu identificar com eficiência os clientes com maior chance de realizar compras no site, utilizando dados históricos e demográficos. O modelo Random Forest se destacou e é o mais indicado para aplicação prática.
