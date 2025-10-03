# Projeto de Análise de Dados — Case 1 XSales

A XSales é uma empresa fictícia de grande porte presente em 5 países: Alemanha, França, Canadá, EUA e Chile.  
Atende uma ampla cadeia de mercado, tendo como clientes desde pequenas empresas até multinacionais.  
A atividade principal da empresa é o oferecimento de **soluções para redes e comunicações em ambientes corporativos**.  

Em 2018 passou a oferecer serviços de vendas online E-Commerce porém sua maior estratégia de vendas ainda é através de pontos físicosnos países em que atua.

---

## Contexto do Projeto
Como Analista de Dados, recebi uma solicitação do Diretor Estratégico para realizar uma análise dos dados mais recentes de vendas da empresa.  
A base de dados disponibilizada contém informações de **set/2018 a dez/2019**.

---

## Questões de Negócio

1. A empresa analisada gerou lucro ou prejuízo no período?  
2. Qual faturamento médio mensal desta empresa?  
3. Qual mês foi registrado o período de maior faturamento da empresa?  
4. Qual é o valor total de descontos sobre as vendas no período?  
5. Qual país gera maior margem de lucro para a empresa em todo o período de análise?  
6. Qual país representa o maior faturamento da empresa em todo o período?  
7. Qual tipo de cliente representa o maior faturamento da empresa em todo o período?  
8. Qual tipo de cliente resulta em uma maior margem de lucro para a empresa?  
9. Algum produto gerou prejuízo para esta empresa no período analisado?  
10. Qual faturamento total e margem de lucro de cada produto?  

---

## Imagem do Dashboard de Vendas
<img width="1413" height="795" alt="Case 1 - Análise de Vendas" src="https://github.com/user-attachments/assets/c379766c-b399-436d-b5cf-1b58ef478120" />

---

## 📊 Relatório Executivo — Análise dos Dados

### 1) Resumo Executivo
- A empresa **gerou lucro** no período analisado.  
  **Lucro total (período): R$ 15.694.851,96**  
- **Faturamento médio mensal:** R$ 7.420.396,89  
- **Mês de maior faturamento:** out/19 — R$ 12.375.819,92  
- **Total acumulado de descontos:** R$ 9.205.248,24  
- **País com maior margem relativa:** Alemanha — **14,51%**  
- **País com maior faturamento absoluto:** EUA — **R$ 25.029.830,17**  
- **Produtos (total):** R$ 118.726.350,26  
  - Maior margem: **Produto 6 — 15,86%**  
  - Maior faturamento: **Produto 3 — R$ 33.011.143,95**  
- Nenhum produto gerou prejuízo — todos apresentaram margens positivas  
  (Produto 1 tem margem baixa de ~4,5%).  

---

### 2) Principais Números
- **Lucro total (período):** R$ 15.694.851,96  
- **Faturamento médio mensal:** R$ 7.420.396,89  
- **Mês pico:** out/19 — R$ 12.375.819,92  
- **Total descontos (acumulado):** R$ 9.205.248,24  
- **País com maior receita absoluta:** EUA — R$ 25.029.830,17  
- **País com maior margem:** Alemanha — 14,51%  
- **Produto com maior margem:** Produto 6 — 15,86%  
- **Produto com maior faturamento:** Produto 3 — R$ 33.011.143,95  

---

### 3) Interpretação Estratégica

- **Saúde financeira:** lucro positivo e consistente — sinal verde.  
  Contudo, o volume de descontos (≈ R$ 9,2M) é significativo, representando ~58% do lucro total. Sugere-se reavaliação urgente da política comercial.  

- **Geografia vs. margem:**  
  - EUA: maior faturamento absoluto, mas não a melhor margem.  
  - Alemanha: eficiência operacional superior, maior margem relativa.  
  Indica que volume nem sempre se traduz em maior rentabilidade.  

- **Produto vs. portfólio:**  
  - Produto 3: campeão em receita (carro-chefe em volumetria).  
  - Produto 6: maior margem (%) — mais lucrativo por real vendido.  
  - Produto 1: margem baixa (~4,5%), candidato a ajuste de preço/custo ou reposicionamento estratégico.  

- **Sazonalidade:** pico em out/19 pode estar ligado a campanha comercial, ciclo de demanda ou concentração contábil.  
  Vale investigar se é sazonalidade real ou evento isolado.  

- **Causalidade vs. correlação:** picos mensais precisam ser validados contra campanhas e registros fiscais para evitar falsas conclusões.  

- **Margens calculadas:** baseadas em divisão entre lucro e receita. Recomendável validar com contabilidade antes de decisões contratuais.  

---

##  Conclusão
A análise mostra que a **XSales apresenta solidez financeira**, mas precisa otimizar descontos e margens por produto e país 
Há espaço para aumentar lucratividade sem depender exclusivamente do crescimento de volume aproveitando melhor os produtos e mercados de maior eficiência.  

---

Este relatório é parte do meu portfólio de projetos em Análise de Dados, utilizando Excel para tratamento de dados, e Power Bi para exploração e visualização da base de dados.  
