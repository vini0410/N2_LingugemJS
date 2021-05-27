# N2_LingugemJS

Atividade N2 de Linguagem de programação 3 da Faculdade Cesusc.
Para essa atividade foi utilizado o MongoDB Atlas como banco de dados e o envio das requisições foi feito por meio do Postman.
 
### Ambiente:
* Para configurar é preciso apenas utilizar o link da cluster com seu usuario e senha no arquivo .env do projeto.
* Para iniciar o código, é preciso fazer o download, abrir a pasta no VS Code, dentro do VS Code abrir um terminal e digitar "npm install", para instalar todas as dependencias (dotenv, express, mongoose, nodemon).
* Após todas as dependencias estarem instaladas, digitar "npm start" para iniciar a execução do app.js.
 
Com o servidor em funcionamento, utilize o Postman para fazer as requisições para a API utilizando a URL http://localhost:3000/

### Requisições: 
#### Usuario:
http://localhost:3000/users


* Listagem de usuário - GET - http://localhost:3000/users 
* buscar usuario por nome - GET - http://localhost:3000/users/<nome>
* criar novo usuario - POST - http://localhost:3000/users 
* deletar usuario por id - DELETE - http://localhost:3000/users/<id>

#### Sala:
http://localhost:3000/rooms

* Listagem de salas - GET - http://localhost:3000/rooms
* buscar sala por id - GET - http://localhost:3000/rooms/<id>
* criar nova sala - POST - http://localhost:3000/rooms
* modificar sala existente por id - PATCH - http://localhost:3000/rooms/<id>

Para criar e modificar classes, coloque as informações da classe no corpo da requisição como arquivo JSON como os exemplos a baixo:
 
 {
 
    "nome" : "Nome",
    "sobrenome" : "Teste"
 
}
 
 {
 
    "nome" : "sala de testes",
    "lotacao" : 628
 
}
