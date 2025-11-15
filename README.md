📘 Pokédex — Projeto Web

Este é um projeto simples de Pokédex desenvolvido com HTML, CSS e JavaScript, utilizando a PokeAPI para listar os primeiros 151 Pokémon da região de Kanto.
O objetivo é treinar conceitos de consumo de API, manipulação de DOM e organização de código no front-end.

🧰 Tecnologias utilizadas

HTML5

CSS3

JavaScript (ES6+)

PokeAPI — https://pokeapi.co/

Normalize.css

Google Fonts (Roboto)

📁 Estrutura do Projeto
/
├── index.html
├── assets/
│   ├── css/
│   │   ├── global.css
│   │   └── pokedex.css
│   └── js/
│       ├── pokemon-model.js
│       ├── poke-api.js
│       └── main.js

🔍 Como funciona
📌 poke-api.js

Conecta na PokeAPI.

Busca os Pokémon de forma paginada.

Converte as informações da API para um modelo interno.

📌 pokemon-model.js

Define a classe Pokemon, usada como modelo de dados.

📌 main.js

Controla a listagem dos Pokémon.

Renderiza cada Pokémon na tela.

Implementa o botão "Load More" para carregar mais itens.

📌 pokedex.css e global.css

Estilos do layout.

Cores para cada tipo de Pokémon.

Grids responsivos para a listagem.

📚 Funcionalidades

✔️ Lista de Pokémon dinâmicos
✔️ Busca à PokeAPI
✔️ Layout responsivo
✔️ Cores de fundo por tipo
✔️ Botão "Load More"
✔️ Modelagem de dados com classe Pokemon


