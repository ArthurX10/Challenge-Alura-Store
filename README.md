# Alura Challenge - Análise de Dados da Alura Store

![Status](https://img.shields.io/badge/Status-Concluído-success)

## 1. 🎯 Visão Geral do Projeto

Este repositório contém a análise de dados desenvolvida para o **Challenge de Ciência de Dados da Alura**. O objetivo do projeto é analisar os dados de vendas, faturamento e métricas de clientes de quatro lojas fictícias da "Alura Store" para extrair insights de negócios, identificar padrões de desempenho e fornecer uma recomendação estratégica baseada em dados.

A análise foca em responder à seguinte pergunta de negócio: **"Qual loja apresenta o pior desempenho e deve ser considerada para fechamento, e quais ações podem ser tomadas para as lojas restantes?"**

## 2. 🛠️ Ferramentas Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
    * `pandas` para manipulação e tratamento dos dados.
    * `matplotlib` e `seaborn` para visualização de dados.
    * `Jupyter Notebook` como ambiente de desenvolvimento e análise.

## 3. 📊 Análise Exploratória de Dados e Insights

A análise foi dividida em várias métricas-chave para obter uma visão completa do desempenho de cada loja.

### 3.1. Desempenho Financeiro (Faturamento)

A métrica mais crítica para a saúde do negócio é o faturamento. A análise mostra uma clara disparidade entre as lojas.

![Análise de Faturamento](1000169235.png)

* **Loja 1:** Lidera com **R$ 1.534.305,12** (26.1% do total).
* **Loja 2:** R$ 1.488.459,06 (25.4% do total).
* **Loja 3:** R$ 1.464.025,03 (24.9% do total).
* **Loja 4:** Apresenta o menor faturamento, com **R$ 1.384.497,58** (23.6% do total).

**Insight:** A Loja 4 é a que menos contribui para a receita total, estando significativamente atrás da Loja 1.

### 3.2. Métricas de Cliente (Avaliação e Frete)

Analisamos se a experiência do cliente (custo de frete e avaliação) poderia justificar o desempenho do faturamento.

| Gráfico | Insight-Chave |
| :---: | :--- |
| ![Média de Avaliação](GRAFICOS/GRAFICO3.png) | **Avaliação:** Todas as lojas possuem avaliações excelentes e muito similares (entre 3.98 e 4.05). A Loja 1, que mais fatura, tem a *pior* avaliação (3.98), enquanto a Loja 3 tem a *melhor* (4.05). |
| ![Média de Frete](1000169239.png) | **Custo do Frete:** Há uma correlação inversa interessante. A **Loja 1** (maior faturamento) tem o frete mais caro (R$ 34.69). A **Loja 4** (menor faturamento) tem o frete mais barato (R$ 31.28). |

**Insight:** Um frete mais barato e uma boa avaliação (como na Loja 4) não estão se convertendo em maior faturamento. Inversamente, os clientes da Loja 1 estão dispostos a pagar um frete mais alto, indicando uma possível demanda mais forte ou um mix de produtos mais desejado.

### 3.3. Análise de Vendas (Categorias e Produtos)

Para entender a dinâmica das vendas, investigamos o volume por categoria e os produtos específicos mais e menos vendidos.

![Vendas por Categoria](1000169236.png)

* **Vendas por Categoria:** As categorias "móveis" e "eletrônicos" são as mais fortes em *volume* de vendas em todas as lojas. A Loja D (Loja 4) tem um volume de vendas alto nessas categorias (480 em móveis, 451 em eletrônicos), comparável ao das outras lojas.
* **Hipótese:** Se a Loja 4 vende um *volume* alto de produtos, mas tem o *faturamento* mais baixo, isso sugere fortemente que ela está vendendo produtos com **preço médio e margem de lucro mais baixos**.

![Produtos Mais e Menos Vendidos](1000169238.png)

* **Produtos Campeões:** A Loja 2 tem o produto mais vendido ("Iniciando em programação", 65 unidades). A Loja 3 tem o "produto campeão" mais fraco ("Kit banquetas", 57 unidades).
* **Menos Vendidos:** Todos os produtos menos vendidos têm um desempenho similar, com vendas entre 32 e 35 unidades.

## 4. 🏁 Conclusão e Recomendação Estratégica

Com base na análise de todos os KPIs, a recomendação estratégica é a seguinte:

### 🥇 Ação Recomendada: Fechamento da Loja 4

A **Loja 4** é a candidata recomendada para desinvestimento (fechamento).

**Justificativa:**
1.  **Menor Faturamento:** É a loja com a menor contribuição para a receita total (R$ 1.38M).
2.  **Ineficiência Operacional:** Apesar de ter vantagens competitivas claras (o frete mais barato e uma boa avaliação de clientes), ela não consegue converter isso em vendas.
3.  **Baixa Lucratividade (Hipótese):** A análise de vendas por categoria vs. faturamento sugere que a loja sobrevive de produtos de alto volume e baixa margem, tornando a operação menos lucrativa e mais difícil de escalar.

### 📈 Recomendações Adicionais

* **Loja 1 (A Vaca Leiteira):** É a loja que mais fatura, *apesar* de ter a pior avaliação e o frete mais caro.
    * **Ação:** Investir na otimização logística (redução de frete) e na melhoria da experiência do cliente (análise de causa-raiz da avaliação 3.98). Melhorias aqui têm o maior potencial de retorno financeiro.
* **Loja 3 (A Queridinha):** Tem a melhor avaliação de clientes (4.05) e um frete competitivo.
    * **Ação:** Seu faturamento é o segundo pior, e seu produto mais vendido é o mais fraco de todas as lojas. Recomenda-se uma revisão do *mix de produtos* e *estratégias de marketing* para capitalizar em cima da sua boa reputação.

## 5. Autor

**[Seu Nome Completo]**

* [LinkedIn](https://www.linkedin.com/in/seu-linkedin/)
* [GitHub](https://github.com/seu-usuario)
