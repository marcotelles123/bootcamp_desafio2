GoStack
Desafio: Conceitos do NodeJS
Custom badge Custom badge Custom badge

Descrição
Aplicação para armazenar repositórios do seu portfólio, permite a criação, listagem, atualização e remoção dos repositórios, pemite também que os repositórios possam receber "likes".

Instalação
Para instalar as dependencias do projeto execute:

$ yarn
Para iniciar o servidor execute:

$ yarn dev
Para executar os testes execute:

$ yarn test
Rotas
POST /repositories: A rota recebe os campos title, url e techs dentro do corpo da requisição;

GET /repositories: Rota que lista todos os repositórios;

PUT /repositories/:id: A rota altera apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;

DELETE /repositories/:id: A rota deleta o repositório com o id presente nos parâmetros da rota;

POST /repositories/:id/like: A rota deve aumentar o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota;

Tecnologias
Express
uuidv4
cors
