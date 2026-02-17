# 🐾 Miaujude – Análise de Dados para ONG de Resgate Animal

## 📌 Sobre o Projeto

O Miaujude é um projeto de modelagem e análise de dados que simula a gestão financeira e operacional de uma ONG de resgate de gatos.

O objetivo foi estruturar um banco de dados relacional e gerar indicadores estratégicos a partir dos dados de:

- Gatos resgatados
- Adoções
- Doações
- Custos operacionais

---

## 🗄 Banco de Dados

Banco desenvolvido em PostgreSQL com modelagem relacional contendo:

- Tabelas com chave primária e estrangeira
- Constraints (CHECK)
- Relacionamentos entre entidades
- Controle de integridade dos dados

---

## 🧠 Técnicas SQL Utilizadas

Durante o projeto foram aplicados:

- JOIN (INNER e LEFT)
- GROUP BY
- Funções de agregação (SUM, COUNT, AVG)
- DATE_TRUNC para análise mensal
- COALESCE para tratamento de valores nulos
- Criação de VIEWS analíticas
- Cálculo de métricas como taxa de adoção e saldo financeiro

---

## 📊 Indicadores Criados

- Receita mensal
- Custo mensal
- Saldo mensal
- Custos por categoria
- Adoções por fase de vida
- Impacto de campanhas
- Custo médio por gato

---

## 📈 Visualização

Dashboard desenvolvido no Power BI conectado ao banco PostgreSQL.

Principais análises visuais:

- Receita x Custo por mês
- Saldo financeiro
- Distribuição de despesas
- Perfil de adoção

---

## 🎯 Objetivo Técnico

Demonstrar habilidades em:

- Modelagem relacional
- Estruturação de dados financeiros
- Criação de consultas analíticas
- Transformação de dados operacionais em indicadores estratégicos
- Integração entre banco de dados e ferramenta de BI
