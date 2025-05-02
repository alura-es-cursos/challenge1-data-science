# AluraStoreBr - Análise de Lojas Virtuais

Este projeto consiste na análise comparativa de dados de vendas de quatro lojas virtuais (Loja 1, Loja 2, Loja 3 e Loja 4), com o objetivo de ajudar o Sr. João a identificar qual loja ele deve manter ou vender com base em métricas de desempenho.

## 📁 Estrutura do Repositório

```
├── src/AluraStoreBr.ipynb   # Notebook com todo o processo de análise e visualizações
├── README.md            # Este arquivo de documentação
└── data/                # (Opcional) Pasta para armazenar datasets locais
```

## 🔍 Descrição do Projeto

1. **Importação e preparação dos dados**: Carregamento dos datasets via URLs CSV e união em um único DataFrame.
2. **Cálculo de métricas**:

   * Faturamento = Preço + Frete
   * Vendas por categoria
   * Avaliação média por loja
   * Produtos mais e menos vendidos
   * Frete médio por loja
3. **Visualizações** com Matplotlib:

   * Gráfico de barras para faturamento por loja
   * Gráfico de pizza para distribuição de tipos de pagamento
   * Gráfico de linha para evolução do faturamento ao longo do tempo
   * Gráficos adicionais para categorias, avaliações e frete
4. **Relatório em Markdown**: Resumo dos insights e recomendação final sobre qual loja vender.

## 🛠️ Como Executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/AluraStoreBr.git
   cd AluraStoreBr
   ```
2. Instale as dependências (recomendado usar ambiente virtual):

   ```bash
   pip install pandas matplotlib
   ```
3. Abra o notebook no Google Colab ou Jupyter:

   ```bash
   jupyter notebook AluraStoreBr.ipynb
   ```
4. Execute todas as células na ordem para obter as análises e gráficos.

## 📊 Resultados e Insights

* **Loja com maior faturamento**: Loja 1
* **Loja com melhor avaliação**: Loja 2
* **Loja com menor frete médio**: Loja 4
* **Produtos mais vendidos**: cômoda, carrinho de controle remoto, micro-ondas, bateria, cama king
* **Produtos menos vendidos**: Ciência da Computação com Python, guitarra, mochila, headset, celular ABXY

### ✅ Recomendação Final

> **Recomendamos que o Sr. João venda a Loja 4**, pois ela apresenta o **pior desempenho geral**: menor faturamento, avaliação apenas mediana e baixa relevância nas principais categorias de venda. Com isso, ele poderá focar seus esforços nas lojas mais lucrativas e bem avaliadas, maximizando suas chances de sucesso.

## 📝 Customizações

* Para alterar nomes ou URLs dos datasets, edite as primeiras células de importação.
* Ajuste filtros e agrupamentos conforme necessidade no notebook.
