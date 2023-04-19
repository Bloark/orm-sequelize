Passos para construção do projeto do zero

1. npm init
2. npm install express
3. npm install body-parser
4. node api/index.js // rodar servidor para teste
5. npm install --save-dev nodemon
6. npm install mysql2 (Banco de dados usado)
7. npm install sequelize@5.21.7 sequelize-cli@5.5.1
8. npm sequelize-cli init
9. criando aqruivo .sequelizerc
10. npx sequelize-cli model:create --name Pessoas --attributes nome:string,ativo:boolean,email:string,role:string (Criando as tabelas e campos).
11. npx sequelize-cli db:migrate (Migração da tabela gerada para o banco.)
12. exemplo de inserção de dados na tabela insert into pessoas (nome, ativo, email, role, createdAt, updatedAt) values (“Carla Gomes”, 1, “carla@carla.com”, “estudante”, NOW(), NOW());
13. npx sequelize-cli seed:generate --name demo-pessoa (Para popular uma tabela).
14. npx sequelize-cli db:seed:all (Migrar dados do seeders para tabela)
15. Defazendo o seeds
    1. npx sequelize db:seed:undo
    2. npx sequelize-cli db:seed:undo --seed nome-do-arquivo
    3. npx sequelize-cli db:seed:undo:all
16. npx sequelize-cli model:create --name Niveis --attributes descr_nivel:string (Criando outras Tabelas)
17. npx sequelize-cli model:create --name Turmas --attributes data_inicio:dateonly
18. npx sequelize-cli model:create --name Matriculas --attributes status:string 
19. npx sequelize-cli db:migrate (Após a criação das chaves estrangeiras) 
20. npx sequelize-cli seed:generate --name demo-nivel (Criar Seed para popular as tabelas)
21. npx sequelize-cli seed:generate --name demo-turmas (Criar Seed para popular as tabelas)
22. npx sequelize-cli seed:generate --name demo-matriculas (Criar Seed paraa popular as tabelas)
23. npx sequelize-cli db:seed:all (Popular as tebelas)
