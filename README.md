Tecnologias:

Linguagem de programação JAVA
Banco de dados em memória H2
Lombok Project
Spring Boot
Spring Data JPA
Linguagem SQL

GET:
Lista todas as categorias: http://localhost:8080/api/categorias/todas

Busca uma categoria: http://localhost:8080/api/categorias/buscar/{id}

Remove uma categoria: http://localhost:8080/api/categorias/delete/{id}

POST:
Salva uma categoria: http://localhost:8080/api/categorias/salvar

JSON: { "id":value, "descricao":"value" }

GET:
Lista todos os usuários: http://localhost:8080/api/usuários/todos

Busca um usuário: http://localhost:8080/api/usuários/buscar/{id}

Remove um usuário: http://localhost:8080/api/usuários/delete/{id}

POST:
Salva um usuário: "http://localhost:8080/api/usuários/salvar"

JSON: { "id":value, "email":"value@value", "nome":"value" }

Tarefas:

GET:
Lista todas as tarefas: http://localhost:8080/api/tarefas/todas

Busca uma tarefa: http://localhost:8080/api/tarefas/buscar/{id}

Remove uma tarefa: http://localhost:8080/api/tarefas/delete/{id}

Inicia uma tarefa: http://localhost:8080/api/tarefas/fazer/{id}

Finaliza uma tarefa: http://localhost:8080/api/tarefas/finalizar/{id}

POST:
Salva uma tarefa: http://localhost:8080/api/categorias/salvar

JSON: { "id":value, "tarefa":"value", "categorias":{"id":"value"}, "usuarios":[{"id":"value"}] }
