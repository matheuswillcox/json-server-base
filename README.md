# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

/users
/skills
/libraries

### Cadastro

POST /register 

Campos obrigatórios para cadastro são email e password. 


### Login

POST /login 

você receberá de volta um token que tem duração de 1 hora

### Users

POST /users

Você precisa ser o dono para ler e escrever

### Skills

POST /skills

Você precisa estar logado para ler.
Para fazer um Post você precisa passar nome, nível e seu userId 

### Libraries

GET /libraries

Todos tem acesso através de um Get das Libraries