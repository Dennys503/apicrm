# API DE CLIENTES (CRM)
- API usando JSON-SERVER Y React JS. CRM 

# CREDITOS A 
- Juan Pablo De la torre Valdez
- CURSO DE UDEMY "REACT LA GUIA COMPLETA"


# ENTORNO JSON-SERVER
# INSTALANDO JSON-SERVER REF 
- URL de referencia: https://www.npmjs.com/package/json-server)
- npm install -g json-server
# INICIAR JSON-SERVER
-json-server --watch db.json --port 4000
# EJEMPLO DE db.json
- [
{
"nombre": "Dennys Valenzuela",
"empresa": "IntroSoft Sv",
"email": "email@gmail.com",
"telefono": "0125454545454",
"notas": "El cliente necesita un sistema post",
"id": 6
},
- {
"nombre": "Alisson Camila",
"empresa": "Baby Word",
"email": "camila@gmail.com",
"telefono": "5255254545",
"notas": "El cliente necesita bicicletas",
"id": 7
}
]
# ESTANDAR DE ENDPOINT
- GET    /clientes
- GET    /clientes/1
- POST   /clientes
- PUT    /clientes/1
- PATCH  /clientes/1
- DELETE /clientes/1

# ENTORNO REACT
- npm install
- npm run dev
- http://localhost:3000/clientes


