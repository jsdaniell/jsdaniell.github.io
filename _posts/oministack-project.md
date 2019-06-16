---
layout: post
title:  "Oministack - Consumindo API na Web e no Mobile"
date:   2019-06-14
excerpt: "Aplicação réplica ao Instagram que funciona consumindo API REST feita no back-end com Express.js, utilizando 'Schemas' como modelagem de dados no MongoDB, o front-end foi construído em React, e a versão mobile em React-Native. O projeto fez parte da semana oministack promovida pela Rocketseat."
project: true
tag:
- javascript
- nodejs 
- expressjs
- mongodb
- react
- react-native
- api-rest
- web
- mobile
comments: false
---

# Semana OminiStack

Utilização da stack MERN (MongoDB, Express, React, Node) feita durante a semana OminiStack promovida pela Rocketseat, o projeto envolve a criação de uma aplicação réplica ao Instagram, onde foram utilizados todos os elementos da stack, inclusive ainda ReactNative para criação da versão mobile da aplicação, visto que o consumo da API REST feita com Express.js em ambiente Node.js, é compartilhada entre a aplicação web e mobile.

# Implementação do Back-end

A implementação do back-end é feita em JavaScript em ambiente Node.js, possibilitando o fornecimento dos dados no lado do servidor com API.

## Dependências

```javascript
"dependencies": {
    "cors": "^2.8.5",
    "express": "^4.17.1",
    "mongoose": "^5.5.14",
    "multer": "^1.4.1",
    "sharp": "^0.22.1",
    "socket.io": "^2.2.0"
  },
```

Os recursos utilizados no ambiente de desenvolvimento envolvem o Node.js (servidor) e o gerenciador de pacotes Yarn, alternativa ao npm que oferece algumas vantagens, como armazenamento em cache de registros dos pacotes instalados, permitindo por exemplo que a instalação dos pacotes em máquinas terceiras aconteçam na mesma ordem que o projeto original.

[Alguns insights meus sobre o Node.js](https://jsdaniell.gitbook.io/source-code/nodejs)

[Mais informações sobre o projeto no GitHub](https://github.com/jsdaniell/oministack).