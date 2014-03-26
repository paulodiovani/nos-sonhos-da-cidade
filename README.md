# Nos sonhos da cidade

> Um jogo narrativo sobre descobrimento, problemas sociais e realidades alternativas.

_"Nos sonhos da cidade"_ é a minha participação no [FVM2014](http://blog.diovani.com/post/78224829898/temas-e-metas-alternativas-para-o-fvm2014).

É um RPG de narrativa compartilhada e construção coletiva de cenário onde os jogadores criarão uma visão obscura de sua própria cidade (ou cidades), transformando lugares conhecidos e acontecimentos recentes  de seu meio em cenário e desafios para se divertirem.

## [Veja o site do jogo](http://paulodiovani.github.io/nos-sonhos-da-cidade/)

# RPG no _GitHub_

Decidi publicar este jogo no GitHub, me beneficiando do serviço de hospedagem de páginas, porque precisava publicá-lo num formato de website, e não como um blog.

Além disso, obviamente, a publicação no github facilita a colaboração e discussão com quem quiser ajudar. Então fiquem à vontade para [clonar o repositório](https://github.com/paulodiovani/nos-sonhos-da-cidade/) e me enviar suas modificações, ou então [abrir discussões](https://github.com/paulodiovani/nos-sonhos-da-cidade/issues).

## _Build with Wintersmith_

Este site está sendo gerado a partir dos fontes do repositório (_branch:_ `master`) com uso do [Wintersmith](http://wintersmith.io/) -- um gerador de sites feito em Node.js.

Para utilizá-lo, você previsa ter [Node.js](http://nodejs.org) e [Npm](http://npmjs.org) instalados em seu pc, e então instalar o _Wintersmith_ com:

    npm install -g wintersmith

A partir daí, basta entrar na pasta onde está o clone e executar `wintersmith preview` para servir o site na porta `8080`.

    git clone https://github.com/paulodiovani/nos-sonhos-da-cidade.git fvm2014-nos-sonhos-da-cidade
    cd fvm2014-nos-sonhos-da-cidade/
    wintersmith preview

Para gerar o HTML (caso, por exemplo, você faça um novo jogo com várias mudanças sobre o meu) o comando usado é o `wintersmith build`, que irá gerar o site em HTML na pasta `../fvm2014-nos-sonhos-da-cidade-out/`.

O _branch_ `gh-pages` do repositório que contém o HTML do site, gerado desta forma.

    cd fvm2014-nos-sonhos-da-cidade/
    wintersmith build
