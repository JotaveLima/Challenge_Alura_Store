# 🛍️ Alura Store – Análise de Desempenho de Lojas

## 📌 Propósito do Projeto

Este projeto tem como objetivo analisar o desempenho de quatro lojas da rede **Alura Store** a fim de identificar **qual unidade apresenta os piores resultados operacionais e financeiros** e, portanto, **deve ser considerada para fechamento estratégico**.

A análise foi baseada em dados fictícios de vendas e considerou os seguintes critérios:

- Faturamento total da loja  
- Categorias mais e menos vendidas  
- Produtos mais e menos vendidos  
- Média das avaliações dos clientes  
- Custo médio de frete  

O projeto foi desenvolvido com foco em **análise exploratória**, **comparações entre métricas-chave** e **tomada de decisão baseada em dados**.

---

## 📁 Estrutura do Projeto

alura-store/
│
├── loja_1.csv # Dados da Loja 1
├── loja_2.csv # Dados da Loja 2
├── loja_3.csv # Dados da Loja 3
├── loja_4.csv # Dados da Loja 4
│
├── Alura_Store_Analise.ipynb # Notebook com a análise completa
├── README.md # Este arquivo


---

## 📊 Exemplos de Gráficos e Insights Obtidos

Abaixo estão alguns exemplos de análises realizadas:

- **Tabela comparativa de indicadores**:

| Loja   | Faturamento Total | Frete Médio | Avaliação Média | Produto Mais Vendido     |
|--------|-------------------|-------------|------------------|---------------------------|
| Loja 1 | R$ 1.534.509,12   | R$ 34,69    | 3,98             | TV Led UHD 4K             |
| Loja 4 | R$ 1.384.497,58   | R$ 31,28    | 3,99             | Cama Box                  |

- **Gráficos:**
  - Barras comparando faturamento total entre as lojas
  - Torta da distribuição de produtos por categoria
  - Barras das categorias mais e menos vendidas

**Insight principal:**  
A **Loja 4** apresentou o **menor faturamento**, menor rotatividade de categorias, produtos menos vendidos e avaliação média inferior a outras unidades. **Foi recomendada para fechamento.**

---

## ⚙️ Instruções para Executar o Projeto

1. **Clone o repositório ou baixe os arquivos:**

```bash
git clone https://github.com/seu-usuario/alura-store.git
cd alura-store

Instale os pacotes necessários:

O projeto usa apenas bibliotecas padrão. Mas você pode instalar o pandas caso ainda não tenha:

pip install pandas

Abra o notebook em seu ambiente Jupyter:

jupyter notebook

Execute o notebook Alura_Store_Analise.ipynb

O notebook carrega os datasets, realiza as análises e exibe os indicadores principais em forma de tabela.

📬 Contato
Projeto desenvolvido para fins educacionais e de análise de dados com Python.
Feito por João Vitor Lima
Linkedin: https://www.linkedin.com/in/joao-victor-lima-dev/
