# CRUD-ANGULAR
Um simples projeto mostrando um CRUD de produtos feito em Angular.


## Instale as dependências via terminal:
npm install


## Iniciando o projeto
- Abra 2 terminais, um para o Backend e outro para o Frontend;
- Em cada terminal acesse as pastas Frontend e Backend pelo o comando cd
- Em cada terminal inicie o projeto pelo o comando npm start


## Abra via server de desenvolvimento para rodar o Backend
http://localhost:3001/products


## Abra via server de desenvolvimento para rodar o Frontend
http://localhost:4200/


## Comandos básicos para a criação de novas funções no projeto
### BACKEND

#### criando o package.json dentro do backend
cd backend
npm init -y

#### instalando a dependencia do server no backend
npm i json-server

#### rodando o projeto dentro da pasta beackend
npm start


### FRONTEND
#### para voltar para a pasta "crud"
cd ..

#### instalando o pacote angular
npm i -g @angular/cli

#### criando a pasta frontend completa
ng new frontend --minimal

#### iniciando o frontend na web
cd front
npm start

#### no angular.json
"inlineTemplate": false,
"inlineStyle": false,

#### adicionar um visual para tela (opcional)
ng add @angular/material

#### criar um componente (html, css e ts)
ng g c components/template/nomedocomponente

#### criar uma directive
ng g d directives/nomedadirective

#### criar uma tabela
ng generate @angular/material:table components/product/product-read2