# 🏪 Alura Challenge - Análise de Dados da Alura Store

![Status](https://img.shields.io/badge/Status-Concluído-success)

## 1. 🎯 Visão Geral do Projeto

Este repositório apresenta a análise de dados desenvolvida para o **Challenge de Ciência de Dados da Alura**.  
O objetivo foi examinar os dados de vendas, faturamento e métricas de clientes de quatro lojas fictícias da **Alura Store**, a fim de gerar **insights acionáveis** e embasar uma **decisão estratégica de fechamento ou otimização operacional**.

> **Questão de negócio:**  
> *Qual loja apresenta o pior desempenho e deve ser considerada para descontinuação, e quais ações podem fortalecer as lojas restantes?*

---

## 2. 🛠️ Ferramentas Utilizadas

**Linguagem:** Python  
**Principais bibliotecas:**
```python
pandas     # manipulação e tratamento de dados
matplotlib # visualização de dados
seaborn    # visualização estatística
```
**Ambiente de desenvolvimento:** Jupyter Notebook  

---

## 3. 📊 Análise Exploratória e Principais Insights

A análise foi estruturada em torno de métricas financeiras e de experiência do cliente, permitindo avaliar o desempenho global de cada loja.

---

### 3.1. Desempenho Financeiro (Faturamento)

A métrica mais crítica para o negócio é o **faturamento**. Observa-se uma diferença clara entre as quatro lojas.

#### 📈 Faturamento Total por Loja
<img src="https://github.com/user-attachments/assets/6a27f65a-7927-4bc8-9cea-cc08ac710faf" width="1000" alt="Gráfico de Faturamento">

| Loja | Faturamento (R$) | % do Total |
|:----:|------------------:|------------:|
| Loja 1 | 1.534.305,12 | 26,1% |
| Loja 2 | 1.488.459,06 | 25,4% |
| Loja 3 | 1.464.025,03 | 24,9% |
| Loja 4 | **1.384.497,58** | **23,6%** |

**Insight:**  
A **Loja 4** é a menos lucrativa e tem a menor contribuição para o faturamento total, ficando bem atrás da Loja 1.

---

### 3.2. Métricas de Cliente (Avaliação e Frete)

Buscou-se entender se fatores como **avaliação média dos clientes** e **custo do frete** explicam o desempenho das lojas.

| Gráfico | Insight-Chave |
|:--:|:--|
| <img src="https://github.com/user-attachments/assets/2b82f706-f61d-40e9-a0bc-22f5b986767a" width="600" alt="Média de Avaliação"> | **Avaliação:** As lojas têm notas muito próximas (3.98 a 4.05). Curiosamente, a **Loja 1**, que mais fatura, possui a *pior avaliação (3.98)*, enquanto a **Loja 3** tem a *melhor (4.05)*. |
| <img src="https://github.com/user-attachments/assets/d0803aff-638c-42ff-88aa-d30cbdde2d65" width="600" alt="Média de Frete"> | **Custo de Frete:** A **Loja 1** (maior faturamento) tem o frete mais caro (R$ 34,69), enquanto a **Loja 4** (menor faturamento) tem o mais barato (R$ 31,28). |

**Insight:**  
Um frete mais barato e boas avaliações (como na Loja 4) **não garantem aumento nas vendas**. Já clientes da Loja 1 pagam fretes mais altos, indicando **demanda forte** ou **mix de produtos mais valioso**.

---

### 3.3. Vendas por Categoria e Produtos

#### 📊 Vendas por Categoria
<img src="https://github.com/user-attachments/assets/8736809b-8812-4e12-8332-6e75a3b54bea" width="1000" alt="Vendas por Categoria">

- As categorias **“móveis”** e **“eletrônicos”** dominam em volume de vendas em todas as lojas.  
- A **Loja 4** tem volumes altos, mas **preço médio e margem de lucro mais baixos**, o que explica seu faturamento inferior.

#### 🏷️ Produtos Mais e Menos Vendidos
<img src="https://github.com/user-attachments/assets/33c954a4-3811-4819-9424-d043678359b3" width="900" alt="Produtos Mais Vendidos">

- **Produto mais vendido:** “Iniciando em programação” (Loja 2, 65 unidades).  
- **Produto mais fraco:** “Kit banquetas” (Loja 3, 57 unidades).  
- Os produtos menos vendidos têm desempenho semelhante (32–35 unidades).

---

## 4. 🏁 Conclusão e Recomendação Estratégica

### 🥇 Loja Recomendada para Fechamento: **Loja 4**

**Motivos:**
1. **Menor faturamento absoluto** (R$ 1.38M, 23,6% do total).  
2. **Baixa conversão comercial**, mesmo com frete acessível e boas avaliações.  
3. **Margem de lucro possivelmente reduzida**, por atuar com produtos de baixo valor médio.

---

### 📈 Recomendações Adicionais

**Loja 1 – Loja Líder**  
- Maior receita, porém menor avaliação e frete mais caro.  
- **Ação:** Otimizar custos logísticos e melhorar experiência do cliente.

**Loja 3 – Loja Promissora**  
- Melhor avaliação entre todas, frete competitivo e boa reputação.  
- **Ação:** Revisar *mix de produtos* e *estratégias de marketing* para elevar o faturamento.

---

## 5. 👤 Autor

**[Seu Nome Completo]**  
Estudante de Ciência da Computação com foco em **análise de dados e visualização de informações**.  

🔗 [LinkedIn](https://www.linkedin.com/in/joaoarthurrodrigues-pontes/)  
💻 [GitHub](https://github.com/ArthurX10)
