Cria uma instância do Docker
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

Executa a correção e estilização do código
yarn eslint --fix src --ext .js
