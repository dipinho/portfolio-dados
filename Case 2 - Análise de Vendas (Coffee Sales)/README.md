## Contexto do Projeto - Análise de Vendas (Coffee Sales)

This dataset contains around 3,530 coffee sales transactions recorded in a cafe. It gives info about both customer and transaction details like time of purchase, method of payment, beverage type, and amount spent.

<p align="center">
<img width="600" height="400" alt="Kaggle_Logo svg" src="https://github.com/user-attachments/assets/37ac893a-b735-4d44-98fd-1e681bb34ff4" />
</p>

This dataset is available on Kaggle - https://www.kaggle.com/datasets/anassarfraz13/coffee-sales-dataset/data


Este conjunto de dados contém cerca de 3.530 transações de vendas de café registradas em uma cafeteria. Ele fornece informações sobre detalhes do cliente e da transação, como horário da compra, método de pagamento, tipo de bebida e valor gasto.

- Nesta análise usei apenas Microsoft Excel e Power BI

---

## Questões de Negócio

Os dados contabilizam transações de um ano de funcionamento da cafeteria, que contempla as datas de março de 2024 a março de 2025.
Realizei uma análise do cenário e os principais números disponível neste datasetpara responder algumas perguntas. Sendo elas:
### 1 - Hora com maior quantidade de vendas.
- Qual a hora com maior contagem de transações (contagem bruta)?

- Essa hora também é a que gera maior receita e maior ticket médio?

- O pico é consistente por dia da semana (ex.: sempre às 9h nas segundas)?

- Qual o lift do pico vs hora média (ex.: pico = 2× hora média)?

- Quais produtos mais contribuem para esse pico?

### 2 - Dia com maiores vendas (rentabilidade por tempo aberto ou sazonalidade.
- Qual dia da semana tem maior receita total e qual tem maior receita por hora de funcionamento?

- Existe sazonalidade semanal (ex.: quintas fracas todo mês)?

- Existem dias isolados (datas específicas) com picos/quedas (eventos/feriados)?

### 3 - Produto mais vendido.
- Qual produto tem maior unidade vendida? Qual gera mais receita?

- Qual é a participação cumulativa (Pareto) — 80/20?

- Produtos com alto volume, mas baixa margem (candidato para otimização de preço)?

### 4 - Método de pagamento mais utilizado
- Qual método tem maior número de transações e maior receita?
  
- Ticket médio por método (ex.: cartão > dinheiro)?
  
-	Há tendência de aumento do uso de um método ao longo do tempo?
  
### 5 - Total de vendas
-	Receita total no período e crescimento M/M ou W/W.

- Como está a concentração da receita (top 10 dias/produtos)

### 6 - Qual turno com mais lucro
- Qual turno (manhã/tarde/noite) gera maior receita e maior margem?


---

## 📊 Relatório Executivo — Análise dos Dados
### 1) Resumo Executivo 
- A empresa gerou lucro no período analisado. Lucro total (período): R$ 112.245,58.

- Faturamento médio mensal: R$ 9.353,80.

-	Mês de maior faturamento: março — R$ 15.891,64 naquele mês.

- Produtos: Detalhes a serem analisados, porém nenhum produto gerou prejuízo e todos têm margem positiva.

### 2) Interpretação estratégica 
Analisando o dataset e minerando os dados pude perceber que, em todas as horas do dia, de 6h a 22h que integra o funcionamento do estabelecimento, **10 horas da manhã** teve o maior pico de venda, também 10 horas da manhã foi constatado o maior lucro nas vendas. O ticket médio da hora com maior lucro é baixo em relação à média geral, o fluxo é ótimo, mas a rentabilidade unitária pode ser fraca. Ou seja: o volume de transações é alto, mas o faturamento médio por transação é pequeno. Isso mostra que o volume está impulsionando o faturamento, não o valor por venda. 10 horas da manhã pode ser boa para tráfego, mas ruim para margem.

<p align="center">
<img width="537" height="589" alt="image" src="https://github.com/user-attachments/assets/8e42aadc-5a20-4854-825b-7ac45ca414c4" />
</p>


**Terça feira** foi o dia com maior número de vendas, em quantidade e valor total de venda. Seu ticket médio esteve próximo do valor de média venda diária, não apresentando diferenças significantes.

<p align="center">
<img width="457" height="379" alt="image" src="https://github.com/user-attachments/assets/bd7ceaf2-ccf4-4c1f-98ae-00175c3e3bef" />
</p>

**Americano with Milk** foi o produto mais vendido, porém, **Latte** foi o produto com maior impacto no lucro. Importante analisar que Americano with Milk apresentou uma variação maior nos seus preços, mesmo sendo um produto de valor inferior o seu maior preço apurado é 0,98 centavos mais caro que o Latte mais barato. Isso PODE justificar a maior quantidade vendida em produtos. Enquanto isso Espresso foi o item menos vendido e com menos margem de lucro. Alerta ligado!

<p align="center">
<img width="510" height="613" alt="image" src="https://github.com/user-attachments/assets/04a2467c-e950-4f67-9485-1a47038e1c4d" />
</p>

**Cartão** foi o único método de pagamento utilizado em todas as transações, nenhuma transação foi concluída com algum outro tipo de meio.

<p align="center">
<img width="492" height="181" alt="image" src="https://github.com/user-attachments/assets/d150adf8-8cfb-4db8-ba87-e261eef52d9f" />
</p>

Na análise de turno que gera mais lucro, o turno da tarde vende mais produtos, porém no turno da noite é onde se concentra o maior valor de vendas, trazendo assim um ticket médio maior. 

<p align="center">
<img width="514" height="287" alt="image" src="https://github.com/user-attachments/assets/db83264b-868c-45f5-9b6e-2da7873eab81" />
</p>

Finalizando a primeira parte da análise, março segue como o mês de maior venda e faturamento, mas conta com um detalhe importante:  março é o mês de aniversário da cafeteria, o aumento das vendas pode ter sido resultado de alguma campanha de marketing, pois nos meses de OUT, NOV, DEZ e JAN a movimentação da cafeteria estava em baixa. Alerta ligado para a sazonalidade.

<p align="center">
<img width="457" height="585" alt="image" src="https://github.com/user-attachments/assets/04e6971d-3311-4aea-8e3e-8b0b5077d00f" />
</p>

--



---

## Conclusão
Em breve atualizações sobre a análise, com finalização do dashboard no Power BI, para facilitar a visualização dos dados e otimizar nas tomadas de decisões.


---

📌 *Este relatório é parte do meu portfólio de projetos em Análise de Dados, utilizando Excel para tratamento de dados, e Power Bi para exploração e visualização da base de dados.  
