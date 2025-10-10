# Projeto de Análise de Dados — Vendas, Margem de Lucro e KPI

Neste projeto coloquei em prática o processo inicial de modelagem de dados, cardinalidade, extração, transformação e carregamento dos dados dentro do Power BI, utilizando boas práticas da linguagem DAX. 

---

## Contexto do Projeto

Este projeto é composto por 4 datasets distintos que formam todo o contexto de dados. Os arquivos .csv que são:
- Clientes
- Produtos
- Pedidos
- Vendas

Além do processo de tratamento de dados, foi feito a visualização dentro do Power Bi, com a finalidade de criar um dashboard de vendas onde serão apresentadas todas as informações sobre custo, margem de lucro e KPI, de **janeiro de 2011 a dezembro de 2014**.

Como Analista de Dados, recebi uma solicitação do Diretor Estratégico para fazer uma análise dos dados mais recentes de vendas da empresa. Realizei uma análise do cenário e os principais números da empresa para responder algumas perguntas. Sendo elas:

---

## Questões de Negócio

1. Qual foi o total de valor venda considerando cada modo de envio dos pedidos? 
2. Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? 
3. A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. A empresa ficou abaixo ou acima da meta no período apurado?
4. Qual categoria de produto apresentou maior lucro médio.
5. Qual foi o comportamento da margem de lucro ao longo do tempo? Considerando que a margem de lucro como o lucro dividido pelo valor venda.
7. É necessário um indicador (KPI–Key Performance Indicator) com o valor médio de venda para um melhor acompanhamento. 


---

## 📊 Relatório Executivo — Análise dos Dados

<img width="1276" height="716" alt="Case 4 - Análise de Vendas" src="https://github.com/user-attachments/assets/9c7c4e98-4c3f-4014-b23f-c64990c65a72" />


### Interpretação Estratégica

**1. Qual foi o total de valor venda considerando cada modo de envio dos pedidos?**
1. Classe Padrão: R$ 7.564.473,00
2. Segunda Classe: R$ 2.565.561,05
3. Primeira Classe: R$ 1.843.675,24
4. Mesmo Dia: R$ 685.344,51

Insight curto a ser mencionado é que a **Classe Padrão** explica a maior fatia do faturamento — foco operacional e pricing aqui tem maior impacto no topo da receita.

**Total Geral de Venda: $ 12.642.501,91**

**2. Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?**

1. US — Custo médio de envio: R$ 29,26
2. APAC — R$ 29,15
3. EU — R$ 27,86
4. LATAM — R$ 26,46
5. Africa — R$ 19,44
6. Canada — R$ 17,78

Mercados intercontinentais (US, APAC, EU) têm fretes mais caros — é interessante considerar renegociação de tarifas de transporte ou diferencial de preço por mercado. Isso pode diretamente interferir nos resultados.

**3. A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. A empresa ficou abaixo ou acima da meta no período apurado?**

A meta estipulada não foi batida. Valor médio de venda por mês (média das médias mensais) foi de R$ 247,61, em um período com 48 meses avaliados. Em todo o período, **NENHUM mês** ficou acima da meta estipulada. 
Isto abre para uma próxima etapa de análises.
- Meta não foi alcançada, mas qual o real motivo?
- É preciso reavaliar preço médio por pedido?
- Mix de produtos?
- Ou repensar e implementar uma nova estratégia de ticket médio.


**4. Qual categoria de produto apresentou maior lucro médio.**

1. Tecnologia — Lucro médio: R$ 418,55
2. Moveis — Lucro médio: R$ 371,70
3. Material de Escritório — Lucro médio: R$ 108,13

Tecnologia lidera lucro médio com 46,55% das vendas, com valor de $ 417,86. Pode ser prioridade para ações de upsell e campanhas de margem.

**5. Qual foi o comportamento da margem de lucro ao longo do tempo? Considerando que a margem de lucro como o lucro dividido pelo valor venda.**

Com a definição adotada, a margem aparece muito elevada porque o “custo” usado foi apenas o custo de envio — isto inflaciona a margem (já que falta o custo do produto). 
Em termos de tendência: a margem mensal foi relativamente estável (o gráfico mensal foi gerado), sem oscilações extremas, mas essa métrica NÃO substitui análise real de margem operacional até confirmarmos COGS. 

COGS = Cost of goods sold = custo das mercadorias vendidas.


---

📌 *Este relatório é parte do meu portfólio de projetos em Análise de Dados, utilizando Excel para tratamento de dados, e Power Bi para exploração e visualização da base de dados.  
