# Taste of the World Café – SQL Projeto de Análise de Dados.

## 📌 A Situação 
Você foi contratado como **Analista de Dados** para o **Taste of the World Café**, um restaurante conhecido por oferecer um menu diversificado e porções generosas.

No início do ano, o restaurante lançou um **novo cardápio**, e a equipe de gestão deseja entender como os clientes estão reagindo a essas mudanças.

---

## 🎯 A Tarefa 
Sua tarefa é analisar os dados disponíveis para:
- Identificar quais itens do menu estão tendo **bom desempenho**
- Descobrir quais itens **não estão performando bem**
- Entender **as preferências dos principais clientes**

A análise foi realizada utilizando dados armazenados em um banco de dados MySQL.

---

## 🧭 Os Objetivos

- Explorar a tabela `menu_items` para compreender a composição do novo cardápio
- Explorar a tabela `order_details` para entender os dados de pedidos coletados
- Utilizar ambas as tabelas em conjunto para analisar a reação dos clientes ao novo menu

---

## 🥗 Objetivo 1: Explorar a Tabela de Itens

Nesta etapa, o foco foi analisar o cardápio do restaurante por meio da tabela `menu_items`.

As análises realizadas incluem:

- **Visualização e contagem**
  - Visualizar a tabela `menu_items`
  - Contar o número total de itens disponíveis no menu

- **Análise de preços**
  - Identificar os itens mais baratos e mais caros do cardápio

- **Filtro por categoria (Italiana)**
  - Determinar quantos pratos italianos existem no menu
  - Identificar os pratos italianos mais baratos e mais caros

- **Estatísticas por categoria**
  - Contar quantos pratos existem em cada categoria
  - Calcular o preço médio dos pratos dentro de cada categoria

---

## 🧾 Objetivo 2: Explorar a Tabela de Pedidos

Nesta fase, a análise concentrou-se na tabela `order_details`, com os seguintes objetivos:

- Visualizar os dados de pedidos registrados
- Identificar o intervalo de datas coberto pela base de dados
- Contar quantos pedidos foram realizados no período analisado
- Analisar a quantidade total de itens pedidos
- Identificar pedidos com grande volume de itens

---

## 👥 Objetivo 3: Analisar o Comportamento do Cliente

A fase final do projeto combina as tabelas `menu_items` e `order_details` para gerar insights estratégicos.

As análises incluem:

- Unir as tabelas `menu_items` e `order_details` em uma única tabela utilizando JOIN
- Identificar os itens mais pedidos e menos pedidos, juntamente com suas categorias
- Listar os **top 5 pedidos** que geraram o maior gasto financeiro
- **Bônus**: Analisar detalhadamente os pedidos de maior gasto para extrair insights sobre as preferências dos clientes mais valiosos

---

## 🛠️ Tecnologias Usadas
- MySQL
- SQL
- MySQL Workbench



