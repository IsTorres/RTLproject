## Para rodar o projeto:

1. Clone o repositório
  * `git clone https://github.com/istorres/RTLproject.git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd RTLproject`

2. Instale as dependências:
  * `npm install`

3. Rode o comando para iniciar a aplicação:
  * `npm start`

## Testes

  - Haverá uma pasta chamada `./stryker` com diversos arquivos `nomeArquivo.conf.json`. Cada um deles é a configuração do avaliador para um requisito e ela **não deve ser alterada**. Rode o comando `npx stryker run ./stryker/nomeDoArquivo.conf.json` para testar aquele arquivo individualmente.

## Linter

  Para garantir a qualidade do código, vamos utilizar neste projeto os linters `ESLint` e `StyleLint`.
  Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível
  e de fácil manutenção! Para rodá-los localmente no projeto, execute os comandos abaixo:

  ```bash
    npm run lint
    npm run lint:styles
  ```
## Lista de requisitos
 - 1. Teste o componente `<App.js />`
 - 2. Teste o componente `<About.js />`
 - 3. Teste o componente `<FavoritePokemons.js />`
 - 4. Teste o componente `<NotFound.js />`
 - 5. Teste o componente `<Pokedex.js />`
 - 6. Teste o componente `<Pokemon.js />`
 - 7. Teste o componente `<PokemonDetails.js />`

### Projeto criado pela Trybe 
