
# Cronômetro Pomodoro - React Native

Este é um projeto simples desenvolvido em React Native que simula um cronômetro, inspirado na técnica Pomodoro. O cronômetro permite ao usuário iniciar e parar um timer, além de limpar o tempo registrado, oferecendo uma interface simples e interativa.

## Funcionalidades

- **Iniciar/Parar Timer**: O botão "VAI" inicia o cronômetro e muda para "PARAR" quando ativado.
- **Limpar Timer**: O botão "LIMPAR" zera o cronômetro e exibe o último tempo registrado.
- **Último Tempo**: Exibe o último tempo registrado quando o cronômetro é limpo.

## Tecnologias Utilizadas

- **React Native**: Framework para desenvolvimento de aplicativos móveis nativos.
- **JavaScript**: Linguagem utilizada para lógica de controle e manipulação de estados.
- **React**: Biblioteca para criação de componentes e gerenciamento de estados.

## Como Rodar o Projeto

### Pré-requisitos

- **Node.js**: Baixe e instale o Node.js a partir de [aqui](https://nodejs.org/).
- **Expo CLI**: Para rodar o projeto, instale o Expo CLI com o seguinte comando:
  npm install -g expo-cli


### Passos

1. Clone o repositório:

   git clone https://github.com/jefferson-barroso/Cronometro


2. Navegue até a pasta do projeto:
   cd cronometro-pomodoro


3. Instale as dependências:
   npm install


4. Inicie o projeto com Expo:
   expo start


5. Abra o aplicativo no seu dispositivo móvel utilizando o aplicativo **Expo Go** (disponível na App Store ou Google Play), ou emulador.

## Estrutura do Projeto

* **App.js**: Arquivo principal da aplicação, onde está a lógica do cronômetro e os componentes.
* **src/cronometro.png**: Imagem do cronômetro.

## Como Funciona

* O aplicativo exibe uma imagem de um cronômetro.
* Quando o usuário pressiona o botão "VAI", o cronômetro começa a contar e o botão muda para "PARAR".
* O botão "LIMPAR" reseta o cronômetro e exibe o último tempo registrado.

