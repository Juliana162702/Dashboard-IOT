# Dashboard IoT - Umidade e Temperatura

Um dashboard web para monitorar dados de temperatura e umidade coletados via ThingSpeak, utilizando Python, Flask e Plotly para visualização interativa.

---

## 🔍 Sobre o Projeto

Este projeto busca criar uma interface simples, responsiva e profissional para exibir dados em tempo real de sensores IoT conectados ao ThingSpeak. A aplicação consome a API pública do ThingSpeak, exibe os últimos valores de temperatura e umidade e apresenta gráficos interativos para análise histórica.

---

## 🚀 Funcionalidades

- Consulta e atualização automática dos dados do canal ThingSpeak.
- Exibição dos valores atuais de temperatura (°C) e umidade (%).
- Gráficos interativos construídos com Plotly (zoom, hover, etc).
- Layout responsivo e moderno, otimizado para desktop e mobile.

---

## 🛠 Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Requests](https://requests.readthedocs.io/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [ThingSpeak API](https://thingspeak.com/)

---

## 💻 Como Rodar Localmente

### Pré-requisitos

- Python 3 instalado ([download aqui](https://www.python.org/downloads/))
- Git instalado ([download aqui](https://git-scm.com/downloads))

### Passos

1. Clone o repositório:
    ```bash
    git clone https://github.com/Juliana162702/Dashboard-IOT.git
    cd Dashboard-IOT
    ```

2. Crie um ambiente virtual (opcional, mas recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Rode a aplicação:
    ```bash
    python app.py
    ```

5. Acesse no navegador:
    ```
    http://127.0.0.1:5000/
    ```

---

## 🔧 Configurações

- Para modificar o canal do ThingSpeak, altere as variáveis `THINGSPEAK_CHANNEL_ID` e `THINGSPEAK_API_KEY` no arquivo `app.py`.
- Ajuste `NUM_RESULTS` para controlar quantos registros serão carregados do ThingSpeak.

---

## 📁 Estrutura do Projeto

