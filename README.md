# 📊 Dashboard de Performance de Vendas - Power BI

![Screenshot do Dashboard](<img width="1427" height="817" alt="Dashboard Business Sales2" src="https://github.com/user-attachments/assets/b28ce868-5647-43b2-8462-4759e32bf6d3" />
)

## 🎯 Objetivo do Projeto
Este dashboard foi desenvolvido para fornecer uma visão clara e estratégica dos indicadores de vendas . O foco principal é permitir que os gestores identifiquem tendências, monitorem metas e tomem decisões baseadas em dados reais de faturamento e margem

## 🛠️ Ferramentas e Tecnologias
*   **Power BI**: Construção dos visuais e interatividade.
*   **DAX (Data Analysis Expressions)**: Criação de métricas personalizadas (fórmulas).
*   **DAX Utilizadas**: **Total Sales = SUM('train'[Sales]),Total Profit = Total [Sales] * 0.25, Total Orders = DISTINCTCOUNT('train'[Order ID]),Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)**
*   **Power Query**: Limpeza, tratamento e modelagem dos dados (ETL).
*   **Linguagem**: Inglês(foi feito em inglês pois o arquivo excel já estava)

## 📈 Principais Indicadores (KPIs)
Para este projeto, estruturei os seguintes indicadores principais:
1.  **Total Sales (Faturamento):** Volume bruto de vendas no período.
2.  **Total Profit (Lucro):** Valor líquido após os custos operacionais.
3.  **Margin %:** "Lucro simulado com margem fixa de 25% para fins de demonstração visual".
4.  **Total Orders:** Quantidade total de pedidos processados.

## 💡 Insights Gerados (O que os dados dizem?)
*   Identificamos que a categoria **[Tecnologia]**  teve uma queda expressiva a partir de 2015 e em 2016 uma alta constante.
*   Houve um crescimento de **ano a ano** 
*   A maior quantidade de vendas foi na região oeste

## 📂 Como utilizar este repositório
1.  Baixe o arquivo `.pbix` presente neste repositório.
2.  Certifique-se de ter o **Power BI Desktop** instalado.
