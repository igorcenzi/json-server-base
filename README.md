## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth), existem 3 endpoints que podem ser utilizados para cadastro e 2 endpoints que podem ser usados para login.

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.


### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

### Products
GET /products
POSt /producs

Formato da requisição para cadastrar: 
`
{
  "name": "Tortinha",
  "description": "Uma tortinha bem gostosa",
  "price": "1.99" 
}
`

## Cart
GET /cart
POST /cart

Formato da requisição para adicionar ao carrinho:

`
{
  "productId": 1,
  "qty": 2
}
`
