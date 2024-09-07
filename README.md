<div align="center">
    <h1>Amazon Web Scraper Project</h1>
    
  <div align="center">
      <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"></a>
      <a href="#"><img alt="BeautifulSoup" src="https://img.shields.io/badge/BeautifulSoup-FFD700?style=for-the-badge&logo=beautifulsoup&logoColor=black"></a>
      <a href="#"><img alt="Requests" src="https://img.shields.io/badge/Requests-FF6F00?style=for-the-badge&logo=requests&logoColor=white"></a>
  </div>

  <h3>Rastreador de Dados do IMDb</h3>

  <p>O projeto envolve a criação de um web scraper para extrair informações sobre os filmes listados no Top 250 do IMDb. Utilizando BeautifulSoup e Requests, o scraper coleta dados como título, ano de lançamento, duração, e classificação dos filmes.</p>
</div>

## <a name="table">Sumário</a>

1. [Introdução](#introdução)
2. [Web Scraping](#web-scraping)
3. [Funcionamento](#funcionamento)
4. [Motivação/Objetivo](#motivação-objetivo)
5. [Contexto](#contexto)
6. [Limitações](#limitações)
7. [Fontes](#fontes)

## <a name="introdução">Introdução</a>

<body>
    <p style="text-align: justify;">
        Este projeto visa criar um web scraper em Python para extrair dados dos filmes listados no Top 250 do IMDb. Utilizando as bibliotecas BeautifulSoup e Requests, o código faz uma requisição à página do IMDb, recupera informações como título, ano de lançamento, duração e classificação dos filmes, e as armazena em um arquivo CSV. O scraper também é configurado para verificar periodicamente e atualizar o arquivo CSV com as informações mais recentes.
    </p>
</body>

## <a name="web-scraping">Web Scraping</a>

O processo de web scraping é realizado utilizando as seguintes bibliotecas:

- **BeautifulSoup**: Para parsear e extrair dados do HTML.
- **Requests**: Para realizar requisições HTTP e recuperar o conteúdo da página.

## <a name="funcionamento">Funcionamento</a>

- **Coleta de Dados**: O scraper acessa a página dos 250 melhores filmes no IMDb e extrai informações como título, ano de lançamento, duração e classificação.
- **Armazenamento**: Os dados extraídos são armazenados em um arquivo CSV.
- **Atualização Periódica**: O scraper é configurado para verificar periodicamente a página e atualizar o arquivo CSV com as informações mais recentes.

## <a name="motivação-objetivo">Motivação/Objetivo</a>

- **Análise de Tendências:** Identificar padrões e tendências nos filmes mais bem avaliados, como gêneros populares e diretores de destaque.
- **Recomendação de Filmes:** Utilizar os dados para criar sistemas de recomendação personalizados baseados nas preferências dos usuários e nas características dos filmes.
- **Insights de Mercado:** Comparar o desempenho dos filmes com outros indicadores, como bilheteira, para entender o impacto das avaliações do IMDb.

## <a name="contexto">Contexto</a>

O projeto se insere na crescente demanda por análises de dados no setor de entretenimento. O IMDb é uma fonte confiável de informações sobre filmes, e seu Top 250 representa uma seleção dos filmes mais bem avaliados pela comunidade.

## <a name="limitações">Limitações</a>

- **Limitações de Escopo:** O scraper foca exclusivamente na lista dos Top 250 filmes, sem abordar outras listas, dados sobre elenco, ou detalhes de enredo.
- **Interpretação dos Dados:** As avaliações do IMDb refletem as opiniões dos usuários e podem não representar a qualidade objetiva dos filmes.

## <a name="fontes">Fontes</a>

- **IMDb Top 250 Movies** (link)
- **Storytelling with Data: A Data Visualization Guide for Business Professionals** (livro)
