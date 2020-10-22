# Express + NodeJS
Nosso exemplo de API utilizando com o Express

## Instalação do Express

```sh
$ npm init

$ npm install --save express
```
$ npm install --save sequelize

$ npm install -D sequelize-cli

$ npm install --save mysql2

$ npx sequelize init

config - Configuração do banco de dados, (Conexão)
migration - Migração são alterações estruturais no banco de dados.
models - Modelo faz referências a tabela no banco de dados.

```sh
$ npx sequelize-cli model:generate --name=Client --attributes name:string,cpf:string,email:string,phone:string

$ npx sequelize-cli db:migrate

```