# 📦 Análise de Atrasos em Entregas com PySpark e Databricks

## 📌 Descrição do Projeto

Uma empresa de logística quer analisar se as entregas estão sendo feitas dentro do prazo. Você tem um dataset com informações sobre as entregas e precisa calcular a taxa de atraso e identificar padrões nos atrasos.

Esse projeto tem como objetivo analisar a taxa de atrasos nas entregas de uma empresa, utilizando PySpark dentro do ambiente Databricks. Com os dados fornecidos, foi realizados cálculos de métricas importantes e identificamos padrões que podem ajudar na melhoria da eficiência logística.

## 📂 Estrutura do Dataset

O dataset contém informações sobre entregas realizadas, com as seguintes colunas:

#### Coluna: Descrição                         

#### ID_Entrega: Identificador único da entrega

#### Data_Pedido: Data em que o pedido foi realizado

#### Data_Entrega: Data em que a entrega foi realizada

#### Transportadora: Nome da transportadora responsável

#### Distancia_km: Distância percorrida para a entrega (em km)

#### Status: Status da entrega (Entregue ou Atrasado)

## 📊 Análises Realizadas

### 1️⃣ Contagem de Entregas e Atrasos

Objetivo: Descobrir quantas entregas foram feitas e quantas sofreram atrasos

### 2️⃣ Cálculo da Taxa de Atraso

Objetivo: Determinar a porcentagem de entregas atrasadas

### 3️⃣ Atrasos por Transportadora

Objetivo: Identificar quais transportadoras possuem maior número de atrasos

### 4️⃣ Relação entre Distância e Atrasos

Objetivo: Verificar se distâncias maiores estão associadas a mais atrasos.

## 📈 Conclusões

Depois das análises foi identificado uma taxa de atraso de 40% sendo as transportadoras B e C com 1 atraso cada uma e a transportadora A não possui atrasos.
Essas análises podem ajudar na otimização das entregas, escolhendo melhor as transportadoras e planejando rotas mais eficientes.

