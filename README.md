# PESSOA API

1 - clone o projeto usando o comando "git https://github.com/rafaelgibam/PESSOA_API.git"
2 - ABRA A SUA IDEIA E IMPORTE O PROJETO PARA SUA WORKSPACE
3 - CONFIGURE SUA IDE PARA APONTAR PARA JDK8
4 - EXECUTE O COMANDO MVN CLEAN & INSTALL
5 - EXECUTE O PROJETO E USE!


- LINK DO PROJETO EM PRODUÇÃO -> http://apipessoa.herokuapp.com/api/v1/

- PARA ACESSAR OS RECURSOS DA API VOCÊ PRECISA ESTÁ AUTENTICADO COM UM TOKEN PARA OBTER ESSE TOKEN VOCÊ PRECISAR FAZER UMA REQUISÃO NO ENDPOINT
  /auth/login PASSANDO NO CORPO DA REQUISÃO OS VALORES {"username": "admin", "password": "admin" }

- COM O TOKEN VOCÊ VAI PASSAR EM TODAS AS REQUISÕES NO HEADER "Authorization Bearer {Seu Token}"
