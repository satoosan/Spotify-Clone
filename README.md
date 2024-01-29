# Spotify Imersão - Projeto Final

Este é o projeto final da Imersão Front-End da Alura, inspirado no visual do Spotify. Durante a imersão, foram abordados conceitos de HTML, CSS e JS, além de tópicos como CSS Grid, media queries e manipulação do DOM.

## Resumo das aulas 01 até a 05

**Aula 01** - HTML e CSS: Nesta aula, aprendemos os conceitos básicos de HTML e CSS. Criamos a estrutura básica de um site e estilizamos com CSS. Aprendemos sobre tags HTML, seletores CSS, propriedades de estilo e como aplicar estilos a elementos específicos.

**Aula 02** - Responsividade e Media Queries: Nesta aula, aprendemos sobre responsividade e como tornar nosso site adaptável a diferentes dispositivos e tamanhos de tela. Utilizamos media queries para aplicar estilos diferentes com base na largura da tela. Aprendemos a criar layouts responsivos e a tornar nosso site mais amigável para dispositivos móveis.

**Aula 03** - CSS Grid: Nesta aula, aprendemos sobre CSS Grid, uma poderosa ferramenta para criar layouts complexos e responsivos. Aprendemos a criar grids, definir áreas, alinhar elementos e criar layouts de várias colunas. Utilizamos o CSS Grid para criar um layout de cards no estilo do Spotify.

**Aula 04** - Manipulação do DOM com JavaScript: Nesta aula, aprendemos sobre manipulação do DOM (Document Object Model) usando JavaScript. Aprendemos a selecionar elementos do HTML, adicionar e remover classes, alterar conteúdo e estilos dinamicamente. Utilizamos o JavaScript para adicionar interatividade ao nosso site, como exibir e ocultar elementos.

**Aula 05** - Consumindo uma API com JavaScript: Nesta aula, aprendemos a consumir uma API usando JavaScript. Utilizamos o fetch para fazer requisições HTTP e receber dados de uma API fake. Aprendemos a exibir os dados recebidos no nosso site e a criar uma funcionalidade de busca para filtrar os resultados.

## Instalação

1. Clone o repositório: `https://github.com/satoosan/Spotify-Clone.git`
2. Instale as dependências: `npm i json-server -g `
3. Inicie o servidor JSON: `json-server --watch api-artists/artists.json`
4. Abra o arquivo `index.html` no seu navegador.

## Funcionalidades

- Criação de layouts complexos usando CSS Grid.
- Responsividade com media queries.
- Manipulação do DOM com JavaScript.
- Funcionalidade de busca utilizando uma API fake.

## Como utilizar

1. Faça uma busca digitando o nome de um artista na caixa de pesquisa.
2. Os resultados serão exibidos na seção de artistas.
3. Clique em um artista para ver mais detalhes.

## Exemplo de JSON

```json
{
  "artists": [
    { "id": 1, "name": "Foo Fighters", "genre": "Rock", "urlImg": "https://i.scdn.co/image/ab67616100005174c884df599abc793c116cdf15" },
    { "id": 2, "name": "Michael Jackson", "genre": "Pop", "urlImg": "https://i.scdn.co/image/ab676161000051740e08ea2c4d6789fbf5cbe0aa" },
    { "id": 3, "name": "Emicida", "genre": "Hip Hop", "urlImg": "https://i.scdn.co/image/ab67616100005174908b4b4bc90e1518b68b4068" },
    { "id": 4, "name": "Chitãozinho e Xororó", "genre": "Sertanejo", "urlImg": "https://i.scdn.co/image/ab676161000051744606c59411c57f7b49588be4" },
    { "id": 5, "name": "Mc Coringa", "genre": "Funk", "urlImg": "https://i.scdn.co/image/ab67616d00001e02fe8f6dd361ad0f12b88c7f56" },
    { "id": 6, "name": "Arlindo Cruz", "genre": "Samba", "urlImg": "https://i.scdn.co/image/ab67616100005174181873f93056642d7b340839" },
    { "id": 7, "name": "Caetano Veloso", "genre": "MPB", "urlImg": "https://i.scdn.co/image/ab67616100005174e98de50f36cf1aa4bf047757" }
  ]
}
```

## Créditos

Projeto desenvolvido durante a Imersão Front-End da Alura.

Instrutores: [Guilherme Lima](https://www.linkedin.com/in/guilherme-lima-458925178/), [Fernanda Degolin](https://www.linkedin.com/in/fernandadegolin/) e [Mayara Cardoso](https://www.linkedin.com/in/mayara-cardoso-556a45162/)
