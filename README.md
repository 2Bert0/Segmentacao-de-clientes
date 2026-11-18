## 📊 Visualização dos Resultados
![Gráfico de Perfil dos Clusters RFM](cluster_rfm_analise (1).png)


# 📊 Customer Segmentation & E-Commerce Analytics (RFM + K-Means)

## 🎯 Visão Geral do Projeto
Este projeto tem como objetivo aplicar técnicas avançadas de Ciência de Dados e Machine Learning para segmentar a base de clientes do e-commerce brasileiro **Olist** (dados públicos do Kaggle). Utilizando a metodologia **RFM (Recência, Frequência e Valor Monetário)** combinada com o algoritmo de clusterização não supervisionada **K-Means**, a base foi categorizada em perfis comportamentais estratégicos para direcionar campanhas de marketing, retenção e maximização de LTV (Lifetime Value).

## 🛠️ Stack Tecnológica
- **Linguagem:** Python
- **Ambiente de Desenvolvimento:** Google Colab (Mobile-friendly)
- **Controle de Versão & Hospedagem:** Git & GitHub
- **Bibliotecas Principais:** 
  - `pandas` & `numpy` (Manipulação e engenharia de dados)
  - `scikit-learn` (Padronização com `StandardScaler` e Machine Learning com `KMeans`)
  - `matplotlib` & `seaborn` (Visualização de dados e gráficos de perfil)

---

## 📈 Principais Descobertas e Clusters Identificados
Através da aplicação do modelo, os clientes foram divididos em 4 clusters distintos, permitindo uma leitura clara do comportamento de compra:

1. **🚀 Recentes (Base Ativa):** Representam o maior volume da base. Possuem o menor tempo de inatividade e sustentam o fluxo transacional diário.
2. **💎 VIPs (High-Ticket):** O grupo de maior valor financeiro. Gastam muito por pedido, mas apresentam um alerta importante de inatividade intermediária, exigindo estratégias urgentes de retenção.
3. **🔄 Recorrentes (Fiéis):** Clientes com alta frequência de compras e excelente ticket médio, demonstrando forte fidelidade à plataforma.
4. **💤 Inativos (Sumidos):** A maior massa de clientes antigos que esfriaram ao longo do tempo, representando uma oportunidade prioritária para campanhas de *win-back* (recuperação).

---
*Desenvolvido por #Humberto como parte do portfólio prático de Engenharia de Dados e Ciência de Dados Aplicada aos Negócios.*
