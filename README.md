# Spotify Imersão - Projeto Final

Este é o projeto final da Imersão Front-End da Alura, inspirado no visual do Spotify. Durante a imersão, foram abordados conceitos de HTML, CSS e JS, além de tópicos como CSS Grid, media queries e manipulação do DOM.

Acesse o site por aqui: [Spotify CLone](https://spotify-imersao-alura.netlify.app/)

## Resumo das aulas 01 até a 05

**Aula 01** - Na primeira aula da Imersão Front-End, os instrutores revisaram conceitos básicos de HTML e CSS e introduziram o projeto do Spotify Clone. O foco da aula foi criar a parte de navegação lateral do site, também conhecida como barra lateral. Foram utilizadas tags HTML como ```<nav>, <ul>, <li> e <a>``` para criar a estrutura da barra lateral, e estilizadas com CSS para definir cores, tamanhos e posicionamento dos elementos. Além disso, também foi adicionado o logotipo do Spotify e ícones de menu utilizando a biblioteca de ícones Font Awesome.

**Aula 02** - Na aula 02 da Imersão Front-End, os instrutores continuaram a desenvolver a navegação lateral do Spotify Clone. Eles mostraram como criar a estrutura HTML e estilizar a barra lateral, adicionando o logotipo, os itens de navegação e a seção da biblioteca. Além disso, também foi adicionada a seção de criação de playlist. Foi utilizado o VSCode com o LiveServer para visualizar as alterações em tempo real.

**Aula 03** - Na aula 03 da Imersão Front-End, os instrutores continuaram a construir o Spotify Clone. Eles focaram em criar o menu superior do site, incluindo o input de busca. Além disso, abordaram conceitos como layout flexbox, pseudo-classes, responsividade e variáveis no CSS. Também aprenderam a dividir o código CSS em múltiplos arquivos para facilitar a manutenção. Foi uma aula bem prática e cheia de dicas para deixar o código mais organizado e eficiente.

**Aula 04** - Na aula 04, aprendemos sobre CSS Grid, que é uma técnica de layout que nos permite criar designs mais complexos e responsivos. Também vimos como usar media queries para tornar nosso site adaptável a diferentes tamanhos de tela. Além disso, aprendemos a manipular o DOM com JavaScript para adicionar interatividade à nossa página. Implementamos a funcionalidade de busca, consumindo dados de uma API fake criada com o json-server.

**Aula 05** - Na aula 05 da Imersão Front-End, os instrutores introduziram a biblioteca React, que é usada para criar componentes e construir aplicações front-end de forma mais organizada e eficiente. Eles mostraram como criar um projeto React usando o comando ```npx create-react-app <nome projeto>```. Também falaram sobre o conceito de VirtualDOM e como o React utiliza essa tecnologia para atualizar apenas as partes da página que foram modificadas, melhorando o desempenho da aplicação. Além disso, eles explicaram o que é JSX e como utilizá-lo para escrever código HTML dentro do JavaScript. Foi apresentado um exemplo de código de um componente de cabeçalho (Header) e seu estilo em CSS.

Aqui está o link para acessar o projeto em REACT
[Spotify-Clone](https://github.com/satoosan/Spotify-Clone/tree/main/spotify-react)

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
