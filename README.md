Projeto desenvolvido com base em uma demanda corporativa real de controle orçamentário para viagens, com foco em análise financeira e suporte à tomada de decisão, e consigo mostrar minha capacidade de transformar dados em informações fáceis de entender.

Ele serve para acompanhar e comparar gastos com passagens versus orçamento, identificando onde o dinheiro está sendo consumido:

Home: apresenta o total gasto, saldo disponível (valor e percentual) e os principais recortes por área (TI, RH, Financeiro…) e por fundo (Operacional, Projetos, Treinamento), ajudando a priorizar cortes ou ajustes de orçamento.

Mapa: permite explorar os destinos/cidades visitadas e a quantidade de viagens, facilitando enxergar padrões de deslocamento e concentrações de custo por localidade.

Navegação entre páginas feita por botões (Home/Mapa).

🛠️ Tecnologias:

<img width="280" height="100" alt="images" src="https://github.com/user-attachments/assets/dcf4a37c-eada-4a3c-a03c-c90a6f687660" />
<img width="160" height="200" alt="image" src="https://github.com/user-attachments/assets/eeba558f-796d-42e9-95ee-a9b849395488" />
<img width="170" height="230" alt="image" src="https://github.com/user-attachments/assets/619c66fc-e6a4-42c4-84c3-3a5b1014f541" />
<img width="200" height="220" alt="image" src="https://github.com/user-attachments/assets/87b8fc60-a799-48b2-bca5-e28b449b6b53" />



----------------------------------------------------------------------

🐍 Geração da Base de Dados

A base utilizada no dashboard foi criada via script em Python, com o objetivo de simular um cenário corporativo real de despesas com viagens.

O script foi responsável por:

Geração de áreas organizacionais

Definição de fundos orçamentários

Simulação de destinos

Distribuição de valores de passagens

Criação de datas de viagem

Os dados gerados foram exportados para Excel e posteriormente tratados no Power BI.
----------------------------------------------------------------------
📁 Fonte de Dados

Os dados utilizados são provenientes de planilha estruturada contendo:

Nome

Área alocada

Destino da viagem

Data da viagem

fundo

Valor da passagem

Situação

Os dados foram tratados no Power Query para:

Ajuste de tipos

Padronização de campos
----------------------------------------------------------------------
🏠 *Página Inicial (HOME)*

<img width="1341" height="752" alt="image" src="https://github.com/user-attachments/assets/67dad2ea-2d14-46c0-88d7-54a289d63da1" />

A Home apresenta uma visão executiva e consolidada do cenário financeiro das viagens corporativas, permitindo análise rápida do orçamento, identificação de desvios e suporte direto à tomada de decisão.

📊 Análises Principais

📌 Total gasto por Área Alocada

O gráfico de barras mostra a distribuição das despesas com passagens aéreas entre as áreas:
TI | Atendimento | Marketing | Vendas | Operações | Financeiro | RH | Jurídico | Compras.
Permite identificar setores com maior consumo, comparar níveis de despesa e detectar possíveis excessos.

🥧 Despesas por Fonte

O gráfico de pizza apresenta a divisão dos gastos entre:
Fundo Operacional | Fundo de Projetos | Fundo de Treinamento.
Facilita a análise do equilíbrio financeiro e da dependência de cada fonte.

📈 Indicadores Estratégicos (KPIs)

Total Gasto → Consolidação geral das despesas(Cálculo feito no excel)

Saldo Disponível → Valor restante do orçamento(Cálculo feito no excel)

% de Saldo → Indicador proporcional da saúde financeira


Esses indicadores oferecem uma leitura imediata da situação orçamentária.

📋 Tabela Gerencial por Fundo

Para cada fundo são exibidos:
Orçamento Total | Valor Utilizado | Saldo Disponível | % de Saldo Restante

Permite monitorar comprometimento financeiro, identificar risco de estouro orçamentário e avaliar eficiência na alocação dos recursos.

----------------------------------------------------------------------
🗺️ *Página Mapa*

<img width="1323" height="742" alt="image" src="https://github.com/user-attachments/assets/8ce03fc7-84ae-4f05-a7b3-c35b381de644" />

A página Mapa mostra, de forma visual e intuitiva, para onde as viagens corporativas estão sendo direcionadas.

Em vez de olhar apenas números em tabelas, aqui é possível enxergar os gastos distribuídos pelo território. Isso ajuda a entender quais cidades concentram mais deslocamentos e como o orçamento está sendo utilizado em cada região.

A ideia é simples: transformar dados financeiros em uma visão mais clara e contextualizada.

🌍 O que o mapa mostra

Cada bolha representa uma cidade de destino.

Quanto maior a bolha, maior o número de viagens realizadas

Ao selecionar uma cidade, é possível ver informações detalhadas

Os dados se ajustam conforme os filtros aplicados

Isso permite identificar rapidamente onde há maior concentração de viagens e onde o orçamento está sendo mais consumido.

💰 Informações por cidade

Ao clicar em um destino, são exibidos:

Quantidade de viagens realizadas

Valor total gasto

Fundo responsável pelo pagamento

Uma breve descrição do principal aeroporto da cidade

Essa última parte adiciona contexto ao dado, ajudando a entender a importância estratégica daquele destino.

🎯 Por que essa análise é importante?

A visualização geográfica facilita:

Identificar padrões de deslocamento

Comparar regiões com maior consumo de orçamento

Entender possíveis concentrações estratégicas

Apoiar decisões sobre alocação de recursos

Mais do que mostrar gastos, o mapa ajuda a contar a história por trás das viagens.


