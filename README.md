# IBOVESPA Historical Stocks Dashboard

Este projeto é um dashboard interativo desenvolvido em **Python** com **Streamlit**, que permite ao usuário visualizar a evolução dos preços históricos de ações que compõem o **Índice Bovespa (IBOVESPA)** desde 2010 até 2025.

---

## Objetivo

O objetivo principal deste projeto é fornecer uma ferramenta visual e interativa para análise de performance de ações da bolsa brasileira. O usuário pode:

- Filtrar os ativos que deseja visualizar;
- Definir um intervalo de tempo personalizado;
- Observar a evolução dos preços ao longo do tempo;
- Ver a performance percentual de cada papel no período selecionado.

---

## Tecnologias Utilizadas

- **[Python](https://www.python.org/)** – Linguagem principal.
- **[Streamlit](https://streamlit.io/)** – Framework para criação rápida de interfaces.
- **[pandas](https://pandas.pydata.org/)** – Manipulação e análise de dados.
- **[yfinance](https://pypi.org/project/yfinance/)** – Acesso a dados de mercado de ações via Yahoo Finance.

---

## Estrutura do Projeto

```
📦 analisando_acoes/
├── 📄 config.toml         # Configuração do design do dashboard
├── 📄 main.py             # Código principal da aplicação
├── 📄 IBOV.csv            # Lista de tickers das ações do IBOVESPA
├── 📄 requirements.txt    # Bibliotecas necessárias
└── 📄 README.md           # Documentação do projeto
```

---

## Como Executar o Projeto Localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/seuusuario/analisando_acoes.git
cd analisando_acoes
```

### 2. Criar e ativar um ambiente virtual (opcional, mas recomendado)

**Linux/macOS:**

```bash
python3 -m venv venv
source venv/bin/activate
```

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Executar a aplicação

```bash
streamlit run app.py
```

Depois disso, o navegador abrirá automaticamente com a aplicação rodando em `http://localhost:8501`.

---

## Arquivo `requirements.txt`

Abaixo as dependências necessárias para rodar este projeto (inclua isso no seu arquivo `requirements.txt`):

```
streamlit
pandas
yfinance
```

---

## Funcionalidades

- Visualização de gráfico de preços históricos  
- Filtro por múltiplas ações  
- Seletor de intervalo de datas com slider  
- Cálculo e exibição da performance percentual de cada ativo  
- Destaque visual para desempenho positivo (verde) e negativo (vermelho)

---

## Contribuições

Contribuições são bem-vindas!  
Sinta-se à vontade para abrir uma *issue*, sugerir melhorias ou enviar um *pull request*.

---

## Contato

- Email: [roberthsantana07@gmail.com](mailto:roberthsantana07@gmail.com)
- LinkedIn: [Roberth Santana](https://www.linkedin.com/in/roberthsantana/)
