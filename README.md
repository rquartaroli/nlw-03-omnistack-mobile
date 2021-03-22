<h1 align="center">
    <img alt="Happy" title="Happy" src=".github/logo.svg" />
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#️-pré-requisitos">Pré-Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalação-e-iniciação-da-aplicação">Instalação e iniciação da aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=8257E5&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="Happy" src=".github/happy.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [SQLite](https://www.sqlite.org/index.html)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

OBS: Estão inclusas as tecnologias utilizadas no projeto como um todo. [Backend](https://github.com/rquartaroli/nlw-03-omnistack-backend), [Frontend](https://github.com/rquartaroli/nlw-03-omnistack-frontend) e Mobile.

## 💻 Projeto

O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz 💜

Projeto desenvolvido durante a terceira **NLW - Next Level Week** oferecida pela [Rocketseat](https://rocketseat.com.br/).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

## 🔖 Layout

Nos links abaixo você encontra o layout do projeto web e também do mobile. Lembrando que você precisa ter uma conta no [Figma](http://figma.com/) para acessá-lo.

- [Layout Web](https://www.figma.com/file/mDEbnoojksG4w8sOxmudh3/Happy-Web)
- [Layout Mobile](https://www.figma.com/file/X27FfVxAgy9f5IFa7ONlph/Happy-Mobile)

## ⚙️ Pré-requisitos

Para rodar essa aplicação, você precisará ter instalado as seguintes ferramentas [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). Além disto, é recomendado que tenha um bom editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

Você precisará também do [Expo](https://expo.io/), no caso do mobile.

## 🛠 Instalação e iniciação da aplicação

Após ter instalado o [Expo](https://expo.io/). Rode a aplicação

com [npm](https://www.npmjs.com/) :

```bash

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação irá abrir em seu browser na página do Expo Development

```

Ou com [yarn](https://yarnpkg.com/) :

```bash

# Instale as dependências
$ yarn install

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A aplicação irá abrir em seu browser na página do Expo Development

```

Aviso importante:

```bash

# Atenção: caso esteja em uma rede empresarial que utilize de proxy, você poderá ter problemas em executar a aplicação, às vezes é resolvido alterando a Connection de LAN para Tunnel, mas nada garante que isso irá funcionar 100%. Mas estando em uma rede doméstica/residencial irá funcionar normalmente.

# Caso vá testar com seu celular físico, instale o Expo nele e escaneie o qrcode que ele já irá começar a carregar.

# Caso esteja utilizando de um emulador, escolha a opção Run on Android device/emulator (em caso do aparelho ser Android) ou Run on iOS simulator (em caso do aparelho ser iOS). Lembrando que você também precisa ter o Expo instalado em seu emulador.

```

Para visualizar toda a aplicação em funcionamento, execute também o [Backend](https://github.com/rquartaroli/nlw-03-omnistack-backend) e [Frontend](https://github.com/rquartaroli/nlw-03-omnistack-frontend).

Em caso de estar utilizando a aplicação com o Backend em execução, sugiro que dê atenção aos itens abaixo:

```bash

#Atenção: Em caso de estar testando no aparelho físico, será necessário alterar a rota do arquivo api.ts dentro da pasta services que acessa o Backend, alterar a baseURL para o IP da sua máquina na rede, esse IP se encontra na página de execução do Expo, aquela que possui o qrcode, inclusive o endereço IP que você precisa inserir no lugar do 'http://localhost:3333', se encontra logo acima do qrcode, apenas copie o IP, a porta não é necessária. Para exibir as imagens corretamente, você terá que acessar os códigos do Backend e alterar a url da página images_view.ts que se encontra dentro da pasta src/views para o mesmo IP que você copiou anteriormente.

# OU

#Atenção: Em caso de estar utilizando emulador iOS, do jeito que esta já deverá funcionar a comunicação com o Backend normalmente. Mas caso esteja utilizando o emulador do Android, então execute o seguinte comando em seu terminal: adb reverse tcp:3333 tcp:3333  .Com isso você poderá executar a aplicação como ela já se encontra e ela também deverá funcionar normalmente com o Backend.

```

## :memo: Licença

Esse projeto está sob a licença [MIT](LICENSE.md).

---

Feito por Rafael Quartaroli através das aulas ministradas pela [Rocketseat](https://rocketseat.com.br/).