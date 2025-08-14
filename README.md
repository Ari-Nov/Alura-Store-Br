# 📊 Análise de Desempenho das Lojas – Alura Store

## 📌 Objetivo
Este projeto tem como objetivo analisar o desempenho de quatro unidades da **Alura Store**, avaliando métricas como faturamento, custo de frete, satisfação do cliente, mix de produtos e presença geográfica, a fim de recomendar qual loja deve ser vendida para viabilizar novos investimentos.

## 🗂️ Dados Utilizados
Os dados foram disponibilizados em formato CSV, separados por loja:
- **loja_1.csv**
- **loja_2.csv**
- **loja_3.csv**
- **loja_4.csv**

Cada base contém informações sobre:
- Categoria e produto vendido
- Quantidade e valor das vendas
- Custos de frete
- Avaliação de clientes
- Localização das vendas

## 🔍 Etapas da Análise
1. **Importação e limpeza dos dados**
   - Leitura dos arquivos CSV diretamente de um repositório online.
   - Remoção de valores nulos para manter consistência.

2. **Análise de faturamento**
   - Comparação do faturamento total entre as lojas.
   - Identificação de padrões e variações relevantes.

   ![Gráfico Faturamento](imagens/faturamento_total.png)

3. **Vendas por categoria**
   - Ranking dos produtos mais e menos vendidos por loja.
   - Análise de concentração de vendas em categorias específicas.

   ![Gráfico Mais Vendidos](imagens/produtos_mais_vendidos.png)

4. **Custos logísticos**
   - Comparação do custo total e médio de frete.
   - Avaliação da eficiência logística.

   ![Gráfico Frete](imagens/custo_frete.png)

5. **Avaliação dos clientes**
   - Comparativo das notas médias por loja.
   - Identificação de pontos fortes e fracos na satisfação do cliente.

   ![Avaliação Clientes](imagens/avaliacao_clientes.png)

6. **Análise geográfica**
   - Mapeamento das vendas por localização.
   - Uso de mapas de calor para visualizar a distribuição geográfica.

   ![Mapa de Calor](imagens/mapa_calor.png)

## 📈 Principais Insights
- **Loja 1** – Bom faturamento e boa reputação, forte presença em SP e BH.
- **Loja 2** – Operação equilibrada, presença forte no Sul e Sudeste.
- **Loja 3** – Alto faturamento, boa performance no Nordeste e Sudeste.
- **Loja 4** – Menor faturamento, piores avaliações e baixa performance em categorias estratégicas.

## 🏆 Conclusão e Recomendação
Recomenda-se **a venda da Loja 4**, pois apresenta:
- Menor retorno financeiro
- Baixa satisfação do cliente
- Ineficiências logísticas
- Menor contribuição estratégica para expansão da marca

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Pandas** – manipulação e análise de dados
- **Matplotlib / Seaborn** – visualização gráfica
- **Folium** – mapeamento geográfico
- **Jupyter Notebook** – desenvolvimento e documentação
