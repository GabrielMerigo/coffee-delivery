<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/glaubermatos/coffee-delivery?color=%2304D361&style=flat">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/glaubermatos/coffee-delivery?style=flat">
  
  <a href="https://github.com/glaubermatos/coffee-delivery/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/glaubermatos/coffee-delivery?style=flat">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=flat">
  
</p>

<h1 align="center">
    <img src="https://github.com/glaubermatos/assets/blob/main/coffee-delivery/cover.png" width="800px" />
    <br />
    <br />
</h1>


<h4 align="center"> 
	🚧  Desafio completo! 🚧
</h4>

## 🏁 Tópicos

<p>
 👉<a href="#-sobre-o-projeto" style="text-decoration: none; "> Sobre</a> <br/>
👉<a href="#-funcionalidades" style="text-decoration: none; "> Funcionalidades</a> <br/>
👉<a href="#-layout" style="text-decoration: none"> Layout</a> <br/>
👉<a href="#-animacoes" style="text-decoration: none; "> Animações</a> <br/>
<!-- 👉<a href="#-melhorias" style="text-decoration: none; "> Melhorias</a> <br/> -->
👉<a href="#-demonstracao" style="text-decoration: none"> Demonstração</a> <br/>
👉<a href="#-como-executar-o-projeto" style="text-decoration: none"> Como executar</a> <br/>
👉<a href="#-tecnologias" style="text-decoration: none"> Tecnologias</a> <br/>
👉<a href="#-autor" style="text-decoration: none"> Autor</a> <br/>
👉<a href="#-user-content--licença" style="text-decoration: none"> Licença</a>

</p>

## 💻 Sobre o projeto

**Coffee Delivery**

Desafio 5 da trilha de **React Native** do **Ignite**. 

O objetivo deste desafio é reforçar os **conceitos de Animações e Microinteração** no React Native.

O desafio proposto consiste em desenvolver do zero, toda a interface visual de um app de delivery de café, aplicando animações e microinterações, como:

- Animações com Reanimated
- Microinterações
- Feedback tátil e sonoro


<a name="-funcionalidades"></a>

## ⚙️ Funcionalidades

- [x] Splash screen animada;
- [x] Listagem dos cafés em destaque;
- [x] Listagem dos cafés por categoria;
- [x] Ver detalhes do café;
- [x] Adicionar um café no carrinho;
- [x] Adicionar items ao carrinho;
- [x] Remover items do carrinho;
- [x] Finalizar pedido;


## 🎨 Layout
Layout da aplicação **[Figma](https://www.figma.com/community/file/1245817631079079109/Coffee-Delivery-%E2%80%A2-Desafio-React-Native)**

---

<a name="-animacoes"></a>

## ⚙️ Animações
### Splash screen
- Animação de entrada
- Animação da logo
  
https://github.com/glaubermatos/coffee-delivery/assets/10993285/a0d1f4b3-ef20-4f13-9c1f-267c61875fce 

### Home

Na tela `Home` temos 5 tipos de animações implementadas:

- Entrada dos itens da listagem geral de cafés (listagem na horizontal).
- Entrada dos itens da listagem de cafés por categoria (listagem na vertical).
- Alteração do Header e da listagem geral de cafés no momento de scroll na listagem de cafés por categoria.
- Toast informando que o café foi adicionado ao carrinho.

https://github.com/glaubermatos/coffee-delivery/assets/10993285/b4eb97ba-c205-40f7-a3a6-cdf69f989430



### Carrinho

Na tela de adicionar um café ao carrinho temos 2 tipos de animações:

- Animação do tamanho do café selecionado.
- Animação da cor do botão, em caso o tamanho estar ou não selecionado.
- Remover item do carrinho a partir de um swipe.

https://github.com/glaubermatos/coffee-delivery/assets/10993285/0224170a-1c18-435a-afd3-8c5681438f81

https://github.com/glaubermatos/coffee-delivery/assets/10993285/b85b88f0-a184-4d62-828b-733a1806b055


### Pedido confirmado

Na tela de pedido confirmado temos 2 tipos de animações:

- Animação entrada do SVG.
- Animação de entrada dos textos.

https://github.com/glaubermatos/coffee-delivery/assets/10993285/0efdbedf-e082-4b02-aad3-ec30411dd930

---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [NPM](https://www.npmjs.com/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)


#### 🧭 Rodando a aplicação com expo

```bash

# Clone este repositório
$ git clone https://github.com/glaubermatos/coffee-delivery.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd coffee-delivery

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npx expo start

```


 ## 🛠 Tecnologias

Este é um projeto criado com o **[Expo](https://expo.dev/)**.
As seguintes ferramentas foram usadas na construção do projeto:

#### **App** ([React Native](https://pt-br.reactjs.org/) + [TypeScript](https://reactnative.dev/))

- **[Styled Components](https://styled-components.com/)**
- **[React Navigation](https://reactnavigation.org/)**
- **[Phosphor React Native Icons](https://phosphoricons.com/)**
- **[React Native Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/docs/)**
- **[React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/)**
- **[React Native Snap Carousel](https://github.com/meliorence/react-native-snap-carousel)**
- **[React Native Toast Message](https://github.com/calintamas/react-native-toast-message#readme)**
- **[Expo AV](https://docs.expo.dev/versions/latest/sdk/av)**
- **[React Native Async Storage](https://docs.expo.dev/versions/latest/sdk/async-storage)**

> Veja o arquivo [package.json](https://github.com/glaubermatos/coffee-delivery/blob/main/package.json)


#### **Utilitários**

- Editor: **[Visual Studio Code](https://code.visualstudio.com/)**
- Fontes: **[Baloo 2](https://fonts.google.com/specimen/Baloo+2)** | **[Roboto](https://fonts.google.com/specimen/Roboto)**

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).
