# 🚀 Workshop Spring Boot 3 + JPA
<p align="center">
  <img src="https://img.shields.io/badge/Java-17+-blue" />
  <img src="https://img.shields.io/badge/OOP-Object%20Oriented-green" />
  <img src="https://img.shields.io/badge/Status-Concluído-success" />
</p>

---

## 📌 Sobre o projeto

Este projeto é uma **API RESTful desenvolvida com Java e Spring Boot**, com foco em boas práticas de desenvolvimento backend.

A aplicação permite realizar operações completas de CRUD, utilizando uma arquitetura em camadas bem definida, garantindo organização, escalabilidade e fácil manutenção.

---

## 🎯 Objetivo

O principal objetivo deste projeto é consolidar conhecimentos em:

* Desenvolvimento backend com Java
* Criação de APIs REST com Spring Boot
* Persistência de dados com JPA/Hibernate
* Estruturação de aplicações profissionais

---

## 🛠️ Tecnologias utilizadas

* **Java 17+**
* **Spring Boot 3**
* **Spring Data JPA**
* **Hibernate (ORM)**
* **Maven**
* **Banco de dados H2 (testes)**
* **PostgreSQL**
* **Postman (testes de API)**

---

## 🧠 Conceitos aplicados

* Arquitetura em camadas (Controller, Service, Repository)
* API RESTful
* Injeção de dependência
* Mapeamento objeto-relacional (ORM)
* Relacionamentos entre entidades:

  * OneToMany
  * ManyToOne
* Tratamento de exceções
* Separação de responsabilidades (SRP)

---

## ⚙️ Como executar o projeto

### 🔧 Pré-requisitos

* Java 17+
* Maven
* Git

---

### ▶️ Passo a passo

```bash
# Clonar o repositório
git clone https://github.com/oCauaAlves/workshop-springboot3-jpa.git

# Entrar na pasta
cd workshop-springboot3-jpa

# Executar o projeto
./mvnw spring-boot:run
```

---

## 🌐 Acesso à aplicação

Após iniciar, a API estará disponível em:

```
http://localhost:8080
```

---

## 🔗 Endpoints principais

### 👤 Usuários

| Método | Endpoint    | Descrição             |
| ------ | ----------- | --------------------- |
| GET    | /users      | Listar usuários       |
| GET    | /users/{id} | Buscar usuário por ID |
| POST   | /users      | Criar usuário         |
| PUT    | /users/{id} | Atualizar usuário     |
| DELETE | /users/{id} | Deletar usuário       |

---

## 🗄️ Estrutura do projeto

```
src
 ├── entities        # Entidades do sistema
 ├── repositories    # Interfaces JPA
 ├── services        # Regras de negócio
 ├── resources       # Controllers (API REST)
 └── config          # Configurações e inicialização
```

---

## 🧪 Testes da API

Você pode testar os endpoints utilizando:

* Postman
* Insomnia

💡 Recomendo criar uma collection com:

* POST /users
* GET /users
* PUT /users/{id}
* DELETE /users/{id}

---

## 📸 Demonstração (adicione prints aqui)

```markdown
![Exemplo](./assets/exemplo.png)
```

💡 Dica: tire prints do Postman ou da API rodando — isso chama MUITA atenção de recrutador.

---

## 🚀 Possíveis melhorias

* 🔐 Implementar autenticação com Spring Security + JWT
* ✅ Validações com Bean Validation
* 📄 Documentação com Swagger/OpenAPI
* ☁️ Deploy em cloud (Render, AWS, Railway)
* 🧪 Testes automatizados (JUnit)

---

## 📈 Diferenciais deste projeto

✔ Código organizado em camadas
✔ Uso de boas práticas do Spring Boot
✔ Estrutura pronta para projetos reais
✔ Base sólida para evolução (segurança, deploy, etc.)

---

## 👨‍💻 Autor

**Cauã Alves**

* 💼 GitHub: https://github.com/oCauaAlves
* 🔗 LinkedIn: (https://www.linkedin.com/in/caua-alves-2b634a276/)

---

## ⭐ Considerações finais

Este projeto faz parte da minha evolução como desenvolvedor backend, focado em construir aplicações robustas, escaláveis e alinhadas com o mercado.

Se este projeto te interessou, fique à vontade para explorar o código e contribuir 🚀
