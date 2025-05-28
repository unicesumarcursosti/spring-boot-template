
# 📘 Atividade Prática: Cadastro e Gerenciamento de Reviews Literárias

## 🎯 Objetivo

Desenvolver uma aplicação Spring Boot com JPA para realizar o CRUD da entidade `BookReview`, treinando habilidades de modelagem, persistência e exposição de endpoints RESTful.

O repositório de referência utilizado em sala de aula se encontra em: [https://github.com/rafael-labegalini/spring-boot-api.git](https://github.com/rafael-labegalini/spring-boot-api.git)

Ele possui todas as configurações necessárias e implementações para conseguir resolver o exercício.

---

## ✅ Requisitos

### 📌 Backend (Spring Boot + JPA)

1. Configurar o acesso ao banco de dados pelo Spring:
    - adicionar as configurações necessárias no `application.properties`

2. Criar a entidade `BookReview` com os seguintes campos e validações:
   - `bookTitle`: String
   - `reviewerName`: String
   - `reviewText`: String
   - `rating`: Integer
   - `recommended`: Boolean

3. Criar o repositório `BookReviewRepository`

4. Implementar as operações de **CRUD completo**:
   - Criar uma nova review
   - Listar todas as reviews
   - Buscar uma review por ID
   - Atualizar uma review existente
   - Deletar uma review

3. Todos os dados devem ser retornados em formato JSON.

---

## 📂 Entrega

- O projeto deve estar organizado em pacotes separados:
  - `entity`
  - `repository`
  - `controller`

- O código deve ser entregue pelo GitHub Education.

---

## 💡 Dicas

- Utilize `@RestController` e `@GetMapping`, `@PostMapping`, `@PutMapping` e `@DeleteMapping` para os endpoints.
- Use `@GeneratedValue(strategy = GenerationType.IDENTITY)` para o ID.
- O banco de dados H2 pode ser usado com o console habilitado para testes locais.

---

Boa prática e mãos à obra! 🚀
