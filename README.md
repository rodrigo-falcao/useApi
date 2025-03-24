# 🚀Forms Bootstrap com API

Este projeto é uma aplicação simples que utiliza **Bootstrap** para estilização e faz requisições a duas APIs: **ViaCEP** para buscar informações de endereço a partir de um CEP e **Open-Meteo** para obter a previsão do tempo com base em coordenadas geográficas.

## 📌Funcionalidades

1. **Busca de Endereço pelo CEP**:
   - O usuário insere um CEP no campo correspondente e clica no botão "Enviar".
   - A aplicação faz uma requisição à API [ViaCEP](https://viacep.com.br/) e exibe as informações de endereço, como rua, bairro, cidade e região.

2. **Previsão do Tempo**:
   - O usuário insere as coordenadas de latitude e longitude e clica no botão "Enviar".
   - A aplicação faz uma requisição à API [Open-Meteo](https://open-meteo.com/) e exibe:
     - A temperatura atual.
     - Se é dia ou noite, representado por "☀️Dia" ou "🌙Noite".

## 🛠️Tecnologias Utilizadas

- **HTML5**: Estrutura do projeto.
- **CSS (Bootstrap 5.3.3)**: Estilização responsiva.
- **JavaScript**: Lógica para requisições às APIs e manipulação do DOM.
- **APIs**:
  - [ViaCEP](https://viacep.com.br/): Para buscar informações de endereço.
  - [Open-Meteo](https://open-meteo.com/): Para obter a previsão do tempo.

## 📖Como Usar

1. **Busca de Endereço**:
   - Insira um CEP válido no campo "CEP" (formato: `00000-000`).
   - Clique no botão "Enviar".
   - O endereço será exibido nos campos de texto abaixo.

2. **Previsão do Tempo**:
   - Insira as coordenadas de latitude e longitude nos campos correspondentes.
   - Clique no botão "Enviar".
   - A temperatura atual e a indicação de dia ou noite serão exibidas.

## 📂Estrutura do Projeto

### Campos de Entrada

- **CEP**: Campo para inserir o CEP.
- **Latitude**: Campo para inserir a latitude.
- **Longitude**: Campo para inserir a longitude.

### Campos de Saída

- **Endereço**:
  - Rua
  - Bairro
  - Cidade
  - Região
- **Previsão do Tempo**:
  - Temperatura atual.
  - Indicação de dia ou noite.

### Botões

- **Enviar (CEP)**: Faz a requisição à API ViaCEP.
- **Enviar (Previsão do Tempo)**: Faz a requisição à API Open-Meteo.


🔹 **Projeto criado para aprendizado e prática!** 🚀 Sinta-se à vontade para contribuir ou sugerir melhorias. 😊

