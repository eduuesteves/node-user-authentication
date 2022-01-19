# Arquitetura REST

## Microsservice

### CRUD DE USUÁRIOS

- GET /users
- GET /users/:uuid

Inserção do novo usuário

- POST /users

Alteração do usuário

- PUT /users/:UUID

Deletação do usuário

- DELETE /users/:uuid



### Autenticação

- POST /token
- POST /token/validate

## Código

    yarn
    |
    yarn init -y

## Typescript

    npm install -g typescript
    |
    tsc --init