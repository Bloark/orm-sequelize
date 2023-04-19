# ORM com NodeJS

O objetivo do projeto curso de Sequelize e ORM(Object/Relational Mapper)  com NodeJS e MySQL. Nesse curso, vamos escrever uma API para um sistema de controle de alunos e turmas de uma escola de inglês. Vamos partir de um diagrama de banco, onde as tabelas já estão dadas, e, a partir desses dados, escreveremos nossa API do zero.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

### 📋 Pré-requisitos

* body-parser: "^1.20.2",
* express: "^4.18.2",
* mysql2: "^3.2.0",
* path: "^0.12.7",
* sequelize: "^5.21.7",
* sequelize-cli: "^5.5.1"
* nodemon: "^2.0.21"
* Mysql instalado e configurado 
** Criar uma base de dados com o nome escola_ingles no mysql
* Criar o arquivo config.json e modificar os dados abaixo conforme a sua necessidade e colara o dados baixo dentro dele.
* Postman Utilizado para testes 

```
      {
        "development": {
          "username": "root",
          "password": "<digite a sua senha aqui>",
          "database": "escola_ingles",
          "host": "127.0.0.1",
          "dialect": "mysql",
          "operatorsAliases": false
        },
        "test": {
          "username": "root",
          "password": null,
          "database": "database_test",
          "host": "127.0.0.1",
          "dialect": "mysql",
          "operatorsAliases": false
        },
        "production": {
          "username": "root",
          "password": null,
          "database": "database_production",
          "host": "127.0.0.1",
          "dialect": "mysql",
          "operatorsAliases": false
        }
      }
```
* npx sequelize-cli db:seed:all (Popular as tebelas)


### 🔧 Instalação

* npm install
* npm start

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto


* [NPM](https://docs.npmjs.com/) - Gerenciador de dependencias
* [JavScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) - JavaScript
* [NPM](https://docs.npmjs.com/) - Gerenciador de dependencias
* [sequelize](https://sequelize.org/docs/v6/getting-started/) - ORM(Object/Relational Mapper) 
* [Mysql](https://dev.mysql.com/doc/) - ORM(Object/Relational Mapper) 

## ✒️ Autores

* **Desenvolvedor** - *Trabalho Inicial* - [Wildson Luiz](https://github.com/Bloark)

## 📄 Licença

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
![GitHub Org's stars](https://img.shields.io/github/stars/Bloark?style=social)
