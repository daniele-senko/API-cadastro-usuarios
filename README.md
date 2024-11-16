# API de Cadastro de Usuários - CRUD

Esta API permite realizar operações CRUD (Create, Read, Update, Delete) para gerenciar usuários. Foi desenvolvida utilizando **Node.js** e **Express** para o backend, com **MongoDB** (ou outro banco de dados) para armazenar os dados.

## Funcionalidades

| Funcionalidade        | Descrição                                                    |
|-----------------------|--------------------------------------------------------------|
| **Criar Usuário**      | Permite adicionar um novo usuário ao banco de dados.         |
| **Listar Usuários**    | Exibe a lista de todos os usuários cadastrados.             |
| **Editar Usuário**     | Atualiza as informações de um usuário existente.             |
| **Excluir Usuário**    | Remove um usuário do banco de dados.                         |
| **Validação de Dados** | Valida os dados do usuário antes de salvar ou atualizar.    |


## Tecnologias Utilizadas

| Tecnologia             | Descrição                                                    |
|------------------------|--------------------------------------------------------------|
| **Node.js**            | Ambiente de execução para JavaScript no lado do servidor.    |
| **Express**            | Framework para construção da API e roteamento.              |
| **MongoDB** (opcional) | Banco de dados NoSQL utilizado para armazenar os dados.     |
| **CORS**               | Middleware para permitir requisições de diferentes origens. |


## Endpoints da API

### `POST /usuarios`
Cria um novo usuário.

### `GET /usuarios`
Lista os usuários existentes.

### `PUT /usuarios/:id`
Edita usuários existentes.

### `DELETE /usuarios/:id`
Exclui usuários existentes.
___

**Request body:**
```json
{
  "id": "673460ce4a0811c054d10aa6"
  "name": "Nome do Usuário",
  "email": "email@dominio.com",
  "password": "senha123"
}
