
<h1 align="center">
    <img alt="GoStack" src="https://i.ibb.co/kmBd6dD/teste.png" width="950px" />
</h1>

<h3 align="center">
  Desafio: Conceitos do NodeJS
</h3> 

<p align="center">
    <a href="https://rocketseat.com.br/gostack">
        <img alt="Custom badge" src="https://img.shields.io/static/v1?label=Rocketseat&message=GoStack%2011&color=green&style=plastic">
    <a/>
    <a href="https://github.com/Rocketseat/bootcamp-gostack-desafio-01">
        <img alt="Custom badge" src="https://img.shields.io/static/v1?label=Desafio&message=02&color=green&style=plastic">
    <a/>  
    <img alt="Custom badge" src="https://img.shields.io/static/v1?label=License&message=MIT&color=green&style=plastic">       
</p>
        
## Descrição
        
Aplicação para armazenar repositórios do seu portfólio, permite a criação, listagem, atualização e remoção dos repositórios, pemite também que os repositórios possam receber "likes".
  
## Instalação

Para instalar as dependencias do projeto execute:
```sh
$ yarn
```  

Para iniciar o servidor execute:
```sh
$ yarn dev
```  

Para executar os testes execute:
```sh
$ yarn test
```  

## Rotas

- **`POST /repositories`**: A rota recebe os campos `title`, `url` e `techs` dentro do corpo da requisição;

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: A rota altera apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota deleta o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota;

## Tecnologias  

  - Express
  - uuidv4
  - cors
  
  ---
[![LinkedIn][linkedin-shield]][linkedin-url]

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/marcotelles123/
