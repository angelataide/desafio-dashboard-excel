# Desafio: Dashboard de Vendas em Excel

Este projeto é uma solução para o desafio de criar um dashboard de vendas interativo no Excel. O objetivo é transformar dados brutos de transações em um painel visual claro e funcional, permitindo a análise de performance e a tomada de decisões estratégicas.



## 📁 Estrutura do Arquivo Excel

O workbook (`.xlsx`) está organizado em quatro abas principais para seguir as melhores práticas de organização de dados:

1.  **D_Dashboard:** A camada de visualização final. Contém todos os gráficos, KPIs (Indicadores-Chave de Performance) e Slicers (Segmentação de Dados) para a interatividade.
2.  **C_Cálculos:** A camada de processamento. Esta aba contém as Tabelas Dinâmicas que servem como base para os gráficos do dashboard. Ela resume os dados da aba "Bases".
3.  **B_Bases:** A camada de dados brutos. Contém a tabela original com todas as transações de vendas, sem nenhuma formatação ou cálculo.
4.  **A_Assets:** A camada de suporte. Contém elementos visuais, como paletas de cores, logos, ícones e qualquer outro elemento de design usado para manter a consistência visual do dashboard.

## 📊 Dados Utilizados (Aba `B_Bases`)

Os dados brutos utilizados para a análise consistem em uma tabela de vendas com as seguintes colunas:

* **ID-Venda:** Identificador único da transação.
* **Data:** Data em que a venda ocorreu.
* **Vendedor:** O nome do vendedor responsável.
* **Região:** A localização da venda.
* **Produto:** O item vendido.
* **Valor:** O valor total da venda.
* **Custo:** O custo associado ao produto vendido.

## 🛠️ Ferramentas e Conceitos Aplicados

* **Tabelas Dinâmicas (Pivot Tables):** Usadas na aba `C_Cálculos` para agregar e resumir os dados brutos.
* **Gráficos Dinâmicos (Pivot Charts):** A principal ferramenta para criar as visualizações interativas no dashboard (ex: Vendas por Região, Lucro por Produto).
* **Segmentação de Dados (Slicers):** Utilizados no dashboard para permitir a filtragem dinâmica de todo o painel por Vendedor, Região ou Período.
* **Fórmulas:** Cálculos de KPIs (como Lucro, Margem e Ticket Médio) feitos a partir das Tabelas Dinâmicas.
* **Formatação Condicional:** (Opcional) Pode ser usada para destacar KPIs ou metas.

## 🚀 Como Usar

1.  Baixe o arquivo `.xlsx` deste repositório.
2.  Abra o arquivo no Excel.
3.  Navegue até a aba **D_Dashboard**.
4.  Utilize os filtros (Segmentação de Dados) na lateral para analisar os dados por diferentes perspectivas.
5.  Para atualizar o dashboard com novos dados, insira as novas informações na tabela da aba **B_Bases** e, em seguida, vá até a aba `C_Cálculos`, clique com o botão direito em uma Tabela Dinâmica e selecione **"Atualizar"**.
