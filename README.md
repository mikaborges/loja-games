Loja de Games

📌 Sobre o Projeto

A Loja de Games é uma aplicação back-end desenvolvida em Java com Spring Boot, que tem como objetivo gerenciar um catálogo de produtos de uma loja de games. O projeto inclui a criação, leitura, atualização e exclusão de categorias e produtos.

🚀 Tecnologias Utilizadas

Java 17

Spring Boot

Spring Data JPA

Hibernate

Jakarta Validation

MySQL

Maven


 
 🛠 Endpoints da API

📌 Categoria Controller

GET /categorias → Retorna todas as categorias

GET /categorias/{id} → Retorna uma categoria pelo ID

GET /categorias/genero/{genero} → Retorna categorias filtradas pelo gênero

POST /categorias → Cria uma nova categoria

PUT /categorias → Atualiza uma categoria existente

DELETE /categorias/{id} → Deleta uma categoria pelo ID

📌 Produto Controller

GET /produtos → Retorna todos os produtos

GET /produtos/{id} → Retorna um produto pelo ID

GET /produtos/nome/{nome} → Retorna produtos filtrados pelo nome

POST /produtos → Cria um novo produto

PUT /produtos → Atualiza um produto existente

DELETE /produtos/{id} → Deleta um produto pelo ID