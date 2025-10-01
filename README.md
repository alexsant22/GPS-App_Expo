# GPS App

Um aplicativo simples para exibir a localização atual do usuário (latitude e longitude).

## Funcionalidades

- Solicita permissão para acessar a localização do dispositivo.
- Exibe a latitude e a longitude atuais do usuário.
- Permite que o usuário atualize sua localização com um botão.

## Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Location](https://docs.expo.dev/versions/latest/sdk/location/)

## Como Executar o Projeto

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 12 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/gps-app.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd gps-app
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```

### Executando o Aplicativo

Para iniciar o aplicativo, execute um dos seguintes comandos:

- Para iniciar o Metro Bundler:
  ```bash
  npm start
  ```
- Para executar em um dispositivo Android ou emulador:
  ```bash
  npm run android
  ```
- Para executar em um dispositivo iOS ou simulador:
  ```bash
  npm run ios
  ```

Depois de iniciar o Metro Bundler, você pode escanear o código QR com o aplicativo Expo Go (disponível para [Android](https://play.google.com/store/apps/details?id=host.exp.exponent) e [iOS](https://apps.apple.com/us/app/expo-go/id982107779)) para executar o aplicativo em seu dispositivo.

## Licença

Este projeto é licenciado sob a licença 0BSD. Consulte o arquivo `LICENSE` para obter mais detalhes.
