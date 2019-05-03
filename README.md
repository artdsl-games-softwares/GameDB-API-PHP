# GameDB-API-PHP

A API GameDB está disponível somente em Português do Brasil.

**The GameDB API is just avaliable in pt-BR(Brazilian) in this moment, we are working to bring the US version, you still can use the API for game names if you want.**

### O que é A GameDB ?

A GameDB API é um banco de dados com cadastros de diversos jogos contendo várias informações, tais como: Nome, abreviação, data de lançamento, plataformas, descrição, desenvolvedora, publicadora, genero, tema, pré-requisitos, dentre diversas outras...

### Pre-requisitos

- PHP 5.6.x ou Equivalente
- Token

### Requisição

A requisição pode ser feita diretamente pela URL chamando a API com os dados.

- *Remova as chaves {} quando for colocar o token, nome ou id do jogo.*
- *Espaços são validos com %20 (ASCII).*
- *Caso seja colocado uma parte do nome a API irá retornar os resultados de acordo com as letras digitadas:*
***Ex.*** *Caso você digite "The", a API irá retornar jogos como* ***The*** *Division, Grand* ***The****ft auto, dentre outros.*

Requisição por **NOME**
```
https://api.artdslsoftwares.com.br/gamedb/json/namesearch/{TOKEN}/{NOME_DO_JOGO}
```

Requisição por **ID**
```
https://api.artdslsoftwares.com.br/gamedb/json/idsearch/{TOKEN}/{ID_DO_JOGO}
```

*Caso você saiba o ID do jogo em nossa base de dados (disponível no arquivo JSON) pode fazer a requisição por ele, isso ajuda a economizar tráfego* :heart:
