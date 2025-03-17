# 🏆 Desafio: Aprenda na Prática Programação Orientada a Objetos

Este repositório contém minha implementação do desafio **Aprenda na Prática Programação Orientada a Objetos**, disponível na plataforma **Digital Innovation One**. O objetivo foi aplicar os conceitos fundamentais de **POO (Programação Orientada a Objetos)** em Java, através de um projeto prático que envolve abstração, encapsulamento, herança e polimorfismo.

---

## 📌 Sobre o Projeto
Durante o desenvolvimento, modelei um **Bootcamp**, onde existem **cursos, mentorias e desenvolvedores** participando. O projeto foi estruturado da seguinte forma:

- **Classe Bootcamp** → Representa um bootcamp contendo cursos e mentorias.
- **Classe Curso** → Representa um curso com título, descrição e carga horária.
- **Classe Mentoria** → Representa uma mentoria com título, descrição e data.
- **Classe Dev** → Representa um desenvolvedor que pode se inscrever em um bootcamp, concluir conteúdos e acumular XP.

Essas classes se relacionam, aplicando os princípios da **POO**.

---

## 🚀 Tecnologias Utilizadas
- **Java JDK 11+**
- **Paradigma de Programação Orientada a Objetos (POO)**
- **IDE IntelliJ (ou VS Code)**
- **Git & GitHub**

---

## 🔹 Conceitos Fundamentais Aplicados
O projeto foi desenvolvido utilizando os principais pilares da Programação Orientada a Objetos:

🔹 **Abstração** → Definição dos atributos e métodos essenciais das entidades do domínio.

🔹 **Encapsulamento** → Organização do código para ocultar detalhes internos e expor apenas o necessário.

🔹 **Herança** → Compartilhamento de atributos e métodos entre classes relacionadas.

🔹 **Polimorfismo** → Capacidade de tratar objetos específicos como objetos genéricos.

---

## 📂 Estrutura do Projeto
```
📁 src/main/java/br/com/adrieloliveira/todolist/
│-- 📄 entity/Todo.java  # Classe que representa uma tarefa
│-- 📄 controller/TodoController.java  # Controller para gerenciar as tarefas
│-- 📄 repository/TodoRepository.java  # Interface para persistência de dados
│-- 📄 service/TodoService.java  # Regras de negócio
```

---

## ▶️ Como Executar o Projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/SEU_USUARIO/todolist-java.git
   ```
2. **Abra o projeto em uma IDE (IntelliJ, VS Code, Eclipse).**
3. **Configure um banco de dados MySQL e atualize o arquivo `application.properties`.**
4. **Compile e execute o projeto:**
   ```sh
   mvn spring-boot:run
   ```
5. **Acesse a API pelo navegador ou Postman:** `http://localhost:8080/todos`

---

## 🔗 Rotas da API

| Método  | Rota           | Descrição |
|---------|--------------|-----------|
| `GET`   | `/todos`     | Lista todas as tarefas |
| `POST`  | `/todos`     | Adiciona uma nova tarefa |
| `PUT`   | `/todos/{id}` | Atualiza uma tarefa pelo ID |
| `DELETE` | `/todos/{id}` | Deleta uma tarefa |

---

## 🎯 O que Aprendi
- Modelagem de classes no contexto da **POO**.
- Aplicação de **herança, encapsulamento e polimorfismo**.
- Implementação de uma API REST utilizando **Spring Boot**.
- Uso do **Spring Data JPA** para persistência de dados.
- Práticas de versionamento de código com **Git e GitHub**.

---

## 📜 Licença
Este projeto é de uso livre para estudos e melhorias. Fique à vontade para contribuir!

Se este conteúdo foi útil para você, deixe uma ⭐ e compartilhe! 🚀

