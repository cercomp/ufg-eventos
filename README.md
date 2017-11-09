[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/joserochadocarmo/ufg-eventos)

# \<ufg-eventos\>

Webcomponente de eventos da UFG - Universidade Federal de Goiás

[DEMO](https://joserochadocarmo.github.io/ufg-eventos)

Example Usage:

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="ufg-eventos.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html

### Instalação

Pra rodar você precisa de um HTTP Server, o Chrome tem uma extensão que resolve este problema de forma bem simples.

[Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)

Faça uma cópia do projeto para seu computador
```
git clone https://github.com/joserochadocarmo/ufg-eventos.git && cd ufg-eventos
```

Agora entre dentro da pasta do projeto execute o comando abaixo para criarmos uma imagem no docker.

```
docker build -t graphql-ufg .
```

Agora com a image criada é só rodar o projeto, com o seguinte comando na mesma pasta.

```
docker-compose up -d
```

Pronto, agora é só acessar pelo navegador, bem rápido né?

Acesse no seu navegador:
```
https://localhost:3000/
```
docker run --rm -v $(pwd):/home/node/app fresnizky/polymer-cli bower install --allow-root



O Graphql roda no endpoint /graphql:
```
https://localhost:3000/graphql
```

<ufg-eventos></ufg-eventos>
