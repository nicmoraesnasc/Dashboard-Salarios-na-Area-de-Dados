# 📊 Dashboard de Salários na Área de Dados

![Preview do Dashboard](preview-dashboard.png)

Um **dashboard interativo** desenvolvido em **Python** com **Streamlit**, **Pandas** e **Plotly Express** para analisar e visualizar salários na área de dados.
O projeto permite filtrar informações, explorar métricas e visualizar gráficos dinâmicos para facilitar análises e apresentações.

---

## 📚 Sobre o Projeto

Este dashboard foi criado durante a **Imersão Python com Dados** da [Alura](https://www.alura.com.br/).
Nesta última aula da imersão, aprendi:

* Utilizar **Streamlit** para criar dashboards interativos.
* Desenvolver **interfaces simples** para visualização de dados.
* Aplicar **filtros dinâmicos** para explorar dados em tempo real.
* Gerar **gráficos interativos** diretamente no dashboard.

---

## 🚀 Tecnologias Utilizadas

* [Python](https://www.python.org/)
* [Streamlit](https://streamlit.io/)
* [Pandas](https://pandas.pydata.org/)
* [Plotly Express](https://plotly.com/python/plotly-express/)

---

## ⚙️ Funcionalidades

✅ **Filtros na barra lateral**

* Ano
* Senioridade
* Tipo de contrato
* Tamanho da empresa

✅ **Métricas principais (KPIs)**

* Salário médio
* Salário máximo
* Total de registros filtrados
* Cargo mais frequente

✅ **Visualizações interativas**

* Top 10 cargos por salário médio
* Distribuição de salários anuais
* Proporção de tipos de trabalho (remoto, híbrido, presencial)
* Salário médio de Cientista de Dados por país (mapa interativo)

✅ **Tabela detalhada dos dados filtrados**

---

## 📂 Estrutura do Código

O projeto é estruturado em um único arquivo principal que:

1. **Carrega os dados** a partir de um CSV hospedado no GitHub.
2. **Cria a interface do dashboard** com Streamlit.
3. **Aplica filtros** usando widgets na barra lateral.
4. **Exibe KPIs** para métricas principais.
5. **Gera gráficos interativos** com Plotly Express.
6. **Exibe tabela de dados detalhada** com os registros filtrados.

---

## 📊 Fonte dos Dados

Arquivo CSV hospedado no GitHub:
[**dados-imersao-final.csv**](https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv)

---

## ▶️ Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/nicmoraesnasc/Dashboard-Salarios-na-Area-de-Dados.git

# Acesse a pasta do projeto
cd Dashboard-Salarios-na-Area-de-Dados

# Instale as dependências
pip install streamlit pandas plotly

# Execute o dashboard
streamlit run app.py
```

---

## 🏆 Créditos

Este projeto foi desenvolvido com base nos ensinamentos de:

* **Guilherme Lima** — Tech Educator e Professor na Alura e na USP
* **Valquíria Alencar** — Instrutora de Data Science
* **Vinicius Caridá** — Especialista Executivo em Dados e IA no Itaú Unibanco
