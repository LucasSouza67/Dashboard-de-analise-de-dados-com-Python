# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é uma aplicação interativa desenvolvida em Python utilizando a biblioteca **Streamlit**. O objetivo é explorar e analisar dados salariais de profissionais da área de dados (Cientistas de Dados, Engenheiros de Dados, Analistas, etc.) ao redor do mundo.

## 🚀 Demo Online

Acesse a aplicação em produção aqui:  
👉 **[Dashboard de Salários - Streamlit](https://dashboard--dados-com-python.streamlit.app/)**

## 📋 Funcionalidades

- **Filtros Interativos**: Barra lateral para filtrar dados por Ano, Nível de Senioridade, Tipo de Contrato e Tamanho da Empresa.
- **KPIs em Tempo Real**: Visualização rápida de métricas como Salário Médio, Salário Máximo e Cargo mais frequente baseados nos filtros aplicados.
- **Visualização de Dados**:
  - Gráfico de barras com os Top 10 cargos por média salarial.
  - Histograma da distribuição de salários anuais (em USD).
  - Gráfico de pizza mostrando a proporção de trabalho remoto vs. presencial.
  - Mapa interativo (Choropleth) exibindo a média salarial por país.
- **Tabela de Dados**: Visualização detalhada dos registros filtrados.

## 🛠️ Tecnologias Utilizadas

- **[Python](https://www.python.org/)**: Linguagem principal.
- **[Streamlit](https://streamlit.io/)**: Framework para criação do dashboard web.
- **[Pandas](https://pandas.pydata.org/)**: Manipulação e análise de dados.
- **[Plotly Express](https://plotly.com/python/plotly-express/)**: Criação de gráficos interativos.

## 📦 Como Rodar Localmente

Siga os passos abaixo para executar o projeto na sua máquina.

### Pré-requisitos

Certifique-se de ter o **Python** instalado.

### 1. Clonar o repositório

```bash
git clone https://github.com/LucasSouza67/Dashboard-de-analise-de-dados-com-Python
cd Dashboard-de-analise-de-dados-com-Python
```

### 2. Instalar as dependências

Recomenda-se criar um ambiente virtual antes de instalar as dependências.

```bash
python -m venv .venv
```
Ative o ambiente virtual
```bash
.venv\Scripts\activate 
```
Intale as dependências presentes no arquivo requirements.txt 
```bash
pip install -r requirements.txt 
```

### 3. Execute a aplicação

```bash
streamlit run app.py
```

O navegador abrirá automaticamente no endereço `http://localhost:8501`.
