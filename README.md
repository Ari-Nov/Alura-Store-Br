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

   <img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/2e6c930f-48d8-4a79-919a-a2ee8d0aaf86" />

3. **Vendas por categoria**
   - Ranking dos produtos mais e menos vendidos por loja.
   - Análise de concentração de vendas em categorias específicas.

   <img width="1189" height="575" alt="image" src="https://github.com/user-attachments/assets/a3ecfce4-eea0-44ed-8514-53c396fca4a9" />


4. **Custos logísticos**
   - Comparação do custo total e médio de frete.
   - Avaliação da eficiência logística.

5. **Avaliação dos clientes**
   - Comparativo das notas médias por loja.
   - Identificação de pontos fortes e fracos na satisfação do cliente.

 <img width="193" height="187" alt="image" src="https://github.com/user-attachments/assets/9c1cbe25-01dd-452b-9149-0365be432169" />

6. **Análise geográfica**
   - Mapeamento das vendas por localização.
   - Uso de mapas de calor para visualizar a distribuição geográfica.

   <img width="474" height="480" alt="image" src="https://github.com/user-attachments/assets/7a12ebfb-c39b-4042-90a4-f359ef48c27b" />


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
