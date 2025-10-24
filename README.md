# Analise-Cohort
Criando uma Analise de Cohort usando Excel

## O Problema de Negócio:

A Store X é uma rede de supermercados com várias unidades físicas espalhadas por todo o país, com o objetivo de fornecer alimentos e comercializar os mais diversos produtos para consumo.
Recentemente, o time de gerentes da Store X identificou um desafio crescente: a retenção de clientes. 
A empresa percebeu que, embora as vendas continuem ocorrendo, a frequência de compras de clientes recorrentes tem diminuído.
O time de dados terá um papel fundamental na criação de indicadores que mostrem como os clientes interagem com a Store X ao longo do tempo. Essas análises vão gerar insights valiosos que permitirão à Store X entender os motivos que levam os clientes a diminuir suas compras ou a não retornar, além de oferecer soluções para melhorar a retenção. 
Questões como: "O que está fazendo com que os clientes deixem de comprar na Store X?", "Quais iniciativas podem reverter esse comportamento?", e "Como podemos aumentar a fidelidade dos nossos clientes?" serão respondidas a partir dos dados.

**O seu nome desafio como Analista de Dados é: Medir a retenção de clientes.**

### Premissas:

* 1 Definição do Fato:
  
  Coluna "Customer Id"
  

* 2 Definição das Dimensões
  
  | Coluna        |  Dimensão     |
  | ------------- |:-------------:|
  | Order Date    | Tempo         |
 



* 3 Combinação Fato-Dimensão:

  3.1 Quantidade de Clientes (Fato) que fizeram um novo pedido (Order Date) nos meses seguintes a partir da primeira compra (Order Date)

   ## Analise Descritiva:

   <div align="center">
  <img src="https://github.com/user-attachments/assets/e440d797-ab62-4ce7-8703-3b36e4ed9fca" />
  </div>

  <br>

* Mês de maior retenção:

Após realizar a análise de Cohort, identificamos que o maior índice de retenção ocorreu no Cohort  de **Abril de 2014**, com taxas de retenção **superiores a 80% no décimo segundo mês subsequente**. 
Esses resultados podem estar associados a campanhas promocionais específicas realizadas no início do ano, como liquidações de estoque.

* Meses de menor retenção:

Após realizar a análise de Cohort, identificamos que existem muitos meses com resultado **0%** em relação ao mês subsequente.

* Recomendação:

**Criar campanhas urgentes para melhorar o cenário.** 
**Campanhas personalizados, descontos para clientes recentes e programas de fidelidade.**


  
