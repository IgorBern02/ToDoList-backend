# ToDoList-backend

Backend simples para gerenciamento de tarefas, criado para servir como API REST para o projeto frontend [ToDoList](https://github.com/IgorBern02/ToDoList).

## Funcionalidades

- CRUD completo de tarefas (Criar, Ler, Atualizar, Deletar)
- Persistência dos dados em arquivo JSON (usando `json-server`)
- API REST simples e fácil de consumir pelo frontend
- Permite gerenciamento local e rápido para desenvolvimento e testes

## Tecnologias utilizadas

- Node.js
- json-server (simula backend REST com JSON)

## Como usar

### Pré-requisitos

- Node.js instalado (versão recomendada 14+)
- Git para clonar o repositório

### Passos para rodar localmente

1. Clone este repositório:
```bash
git clone https://github.com/IgorBern02/ToDoList-backend.git
cd ToDoList-backend
```


2. Instale as dependências:
```bash
npm install
```


3. Inicie o servidor backend:
```bash
npm start
```

O backend estará rodando em http://localhost:3001 (ou na porta configurada).

### Endpoints principais
GET /tasks - lista todas as tarefas
POST /tasks - cria uma nova tarefa
PUT /tasks/:id - atualiza a tarefa com o id especificado
DELETE /tasks/:id - remove a tarefa com o id especificado

### Integração com frontend
Este backend foi desenvolvido para ser usado com o projeto frontend ToDoList. No frontend, configure a URL base para apontar para o endereço onde o backend estiver rodando (por padrão http://localhost:3001).

### Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.
