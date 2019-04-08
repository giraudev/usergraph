# usergraph
GraphQL and NodeJS
This repository shows how simple is graphQL and Node


Instructions:
- git clone git@github.com:giraudev/usergraph.git
- open the diretory
- terminal: node index.js

The app will run at port 3000.

Just for example:
- https://localhost:3000/user?query={user(id:2){id,name,age,knowledge{language,frameworks}}}
- https://localhost:3000/user?query={user(id:3){id,name,age,knowledge{language}}}
- https://localhost:3000/user?query={user(id:1){id,knowledge{language,frameworks}}}
- https://localhost:3000/user?query={user(id:1){id,name,age}}
- https://localhost:3000/user?query={user(id:2){id,name,age,knowledge{}}}
- https://localhost:3000/user?query={users{id,name,age,knowledge{language,frameworks}}}

reference: https://tableless.com.br/introducao-graphql-nodejs/
