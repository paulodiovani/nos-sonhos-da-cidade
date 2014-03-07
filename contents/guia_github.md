---
title: Guia do colaborador
author: Paulo Diovani Gonçalves
authorUrl: http://blog.diovani.com
template: default.jade
---

### Guia um pouco maior de como colaborar

Se você possui conta no GitHub e algum conhecimento da ferramenta, pode me ajudar a escrever e me enviar _pull requests_.

Primeiro, faça um _fork_ do repositório em `https://github.com/paulodiovani/nos-sonhos-da-cidade/`. Depois disso você pode clonar o repositório (lembre de trocar para o seu fork do repositório).

    git clone https://github.com/paulodiovani/nos-sonhos-da-cidade.git fvm2014-nos-sonhos-da-cidade

Este site está sendo gerado a partir dos fontes do repositório (_branch:_ `master`) com uso do [Wintersmith](http://wintersmith.io/) --  um gerador de sites feito em Node.js.

Para utilizá-lo, você previsa ter [Node.js](http://nodejs.org) e [Npm](http://npmjs.org) instalados em seu pc, e então instalar o _Wintersmith_ com:

    npm install -g wintersmith

A partir daí, basta entrar na pasta onde está o clone e executar `wintersmith preview` para servir o site na porta `8080`.

    cd fvm2014-nos-sonhos-da-cidade/
    wintersmith preview

Para gerar o HTML (caso, por exemplo, você faça um novo jogo com várias mudanças sobre o meu) o comando usado é o `wintersmith build`, que irá gerar o site em HTML na pasta `../fvm2014-nos-sonhos-da-cidade-ou/`.

O _branch_ `gh-pages` do repositório que contém o HTML do site, gerado desta forma.

    cd fvm2014-nos-sonhos-da-cidade/
    wintersmith build
