---
layout: post
title:  "NodeShop"
date:   2019-06-10
excerpt: "Demonstração dos principais usos do framework Express e Core Módules do Node.js"
project: true
tag:
- javascript
- nodejs 
- expressjs
- pug
- ejs
- web
comments: false
---

# Node Shop

Aplicação de loja, utilizando implementação do framework Express.js abstraindo certa complexidade do Node.js pra que houvesse mais foco na lógica de negócio da aplicação, ainda foi utilizado a template engine **[pug](https://pugjs.org/api/getting-started.html)** pra implementação de página HTML dinâmica.


Demonstração de uso dos principais recursos e usos do framework Express executando em ambiente Node.js, foram utilizados diversos pacotes instalados via **npm**.

## Dependências do Projeto

```javascript
  "devDependencies": {
    "nodemon": "^1.19.1"
  },
  "dependencies": {
    "@types/express": "^4.16.1",
    "body-parser": "^1.19.0",
    "ejs": "^2.6.1",
    "express": "^4.17.1",
    "express-handlebars": "^3.1.0",
    "pug": "^2.0.3"
  }
  ```

### As dependências acima se referem as seguintes competências:

- Implementação do servidor construída em cima do framework Express.js (express)
- Recursos para melhor manipulação do corpo das requisições (body-parser)
- Template engine para criação de páginas web dinâmicas (ejs, pug, express-handlebars)

[Mais informações sobre o projeto no GitHub](https://github.com/jsdaniell/nodeshop).