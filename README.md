## 📌 Projeto de Menu

📖 Descrição
* Este é um backend simples para gerenciamento de um cardápio, desenvolvido com Spring Boot. O sistema permite a criação de itens com nome, preço e imagem, garantindo a persistência dos dados.
A princípio, os dados são armazenados no H2 Database para testes, e posteriormente serão migrados para MySQL, utilizando o Flyway para controle de versões do banco de dados.
O projeto final incluirá um frontend em React, que consumirá esta API.

--- 
### 🚀 Tecnologias Utilizadas
* Java 17
* Spring Boot
* Spring Data JPA
* H2 Database (temporário)
* MySQL (final)
* Flyway (migrações)
* Spring Web (para criar os endpoints)
* Lombok (para reduzir código boilerplate)

--- 

## 📡 Endpoints da API
* 1️⃣ Criar um novo item no cardápio

Método: POST
```
URL: /api/cardapio
Body (JSON):
jsonCopiarEditar{
  "title": "Hamburguer",
  "price": 25.99,
  "image": "https://exemplo.com/hamburguer.jpg"
}
```

* 2️⃣ Listar todos os itens
Método: GET
URL: /food
3️⃣ Buscar item por ID
Método: GET
URL: /food/id
