# 🛒 Análise de Desempenho das Lojas – AluraStore

Este projeto foi desenvolvido como parte do **Challenge de Data Science da Alura**, com o objetivo de auxiliar o Senhor João na **tomada de decisão sobre qual loja deve ser vendida**. O trabalho envolveu **exploração de dados reais de vendas**, análise de **indicadores de desempenho comercial e logístico**, e geração de visualizações para embasar uma decisão estratégica.

---

## 📌 Objetivo do Projeto

Analisar os dados de vendas de quatro lojas (Loja 1, 2, 3 e 4) e recomendar, com base em evidências, **qual loja apresenta o desempenho mais fraco** e, portanto, deve ser vendida. 

---

## 🧰 Tecnologias Utilizadas

- Python 3.10+
- Jupyter Notebook / Google Colab
- Bibliotecas:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `folium`
  - `numpy`

---

## 📊 Etapas da Análise

### 1. Importação e Consolidação dos Dados
- Importação de 4 arquivos `.csv` com os dados de vendas por loja
- Criação de uma coluna `Loja` para identificação
- Junção de todos os dados em um único DataFrame (`dados`)

### 2. Faturamento Total por Loja
- Agrupamento por loja e soma da coluna `Preço`
- Visualização com gráfico de barras horizontal e rótulo em formato `R$`

### 3. Categorias Mais Vendidas
- Agrupamento por `Categoria do Produto`
- Comparação da distribuição entre lojas

### 4. Avaliação Média dos Clientes
- Cálculo da média da coluna `Avaliação da compra`
- Comparativo entre as quatro lojas

### 5. Produtos Mais e Menos Vendidos
- Agrupamento por `Produto` e `Loja`
- Identificação dos campeões de venda e dos produtos com menor giro

### 6. Frete Médio por Loja
- Cálculo do frete médio por loja
- Gráfico de barras com destaque para variações

### 7. Análise Geográfica (Extra)
- Geração de **Heatmap interativo com Folium**
- Visualização da **distribuição espacial das vendas**

---

## 📝 Relatório Final

Ao final do projeto, foi produzido um relatório estruturado contendo:

- Síntese dos dados analisados
- Gráficos e visualizações interpretadas
- Recomendação clara: **Venda da Loja 4**
- Justificativa baseada em:
  - Menor faturamento
  - Maior custo médio de frete
  - Menor presença geográfica
  - Desempenho abaixo das demais

---

## 📎 Arquivos Disponíveis

- `Challenge_AluraStoreBr.ipynb` – Notebook com todas as análises
- `README.md` – Esta apresentação do projeto
---

## 🤝 Autor

## 📌 Observações Finais

Este projeto foi desenvolvido com fins educacionais e como simulação de um cenário de análise de negócios. Todos os dados são públicos, disponibilizados pela Alura.

