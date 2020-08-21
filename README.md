Projeto criado para o desafio do módulo 3 da rocketseat, Fundamentos do React Native
Para este projeto foi utilizado um JSON server para rodar na porta :3333.

O objetivo desta aplicação é realizar a parte de listagem de produtos e a funcionalidade de
adicionar ao carrinho, incrementar e decrementar a quantidade de items no mesmo, armazenando também em um asyncStorage (cache para mobile)
de acordo com o layout: https://www.figma.com/file/VgK3hsmyGbqiGu9FdqfUzF/GoMarketplace?node-id=0%3A1

## Scripts disponíveis

Para rodar o projeto basta executar

### `yarn`

Para instalar as dependências da aplicação

### `yarn json-server server.json -p 3333`

Para startar o JSON server (FAKE API)

### `adb -s <device name> reverse tcp:3333 tcp:3333`

Presumindo que a sdk do android já esteja instalada na sua máquina, e que seu dispositivo esteja conectado,
habilitado modo desenvolvedor e depuração usb, e ao rodar adb devices, o dispositivo esteja como "device"

Este comando irá dizer que a porta 3333 encontrada no seu dispositivo android se equivale a porta 3333 do seu localhost

### `npx react-native react-android`

Roda a aplicação no seu emulador ou no seu dispositivo conectado (por padrão, porta 8081)

### `yarn test`

Para executar os testes necessários para a aplicação ser considerada criada com sucesso

## Fundamentos

Neste projeto foram colocados em prática os conhecimentos adquiridos no módulo 3 do Bootcamp,
foram apresentadas algumas funcionalidades novas do React Native como o conceito de Routes que é bem
diferente do React, assim como também o conceito de AsyncStorage,

- React-Native;
- ContextAPI;
- Typescript;
- AsyncStorage;
- Routes

## Observações

Muito perrengue para utilizar o Android Studio, emular pelo celular aparentou ser uma forma mil vezes mais fácil
