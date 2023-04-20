
## Commerce

Commerce é um projeto para fixação dos aprendizados iniciais com MongoDB. Utilizando alguns dados do cardápio do McDonalds, para consultar e atualizar informações.

As querys estão separadas em arquivos, conforme requirido para avaliação da Trybe.
## Apredizados com este projeto

- MongoDB
- Docker

## Instalação

Caso queira instalar o projeto e dar uma olhada mais de perto.

```bash
1. Clonando o projeto
  git clone git@github.com:WillianDutra/mongodb-commerce.git

2. Entrando na pasta
  cd mongodb-commerce

3. Instalando as dependências
  npm install

4. Iniciando docker
  docker-compose up -d

5. Crie uma conexão na extensão do MongoDB com a URL:
  mongodb://localhost:27017

6. Entrando no container
  docker exec -it MongoDB bash

7. Importando os dados
  mongorestore -d commerce /assets/produtos/produtos.bson

```
Agora é só entrar nos arquivos e rodar o código.
