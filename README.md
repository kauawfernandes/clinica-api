# Clínica API

API REST para gerenciamento de uma clínica médica, permitindo controle de pacientes, médicos e agendamentos de consultas.

## 🚀 Funcionalidades
- Cadastro, listagem, atualização e remoção de pacientes
- Cadastro e gerenciamento de médicos
- Agendamento de consultas com validações
- Relacionamento entre pacientes e médicos

## 🛠 Tecnologias
- Java
- Spring Boot
- Spring Data JPA
- MySQL

## 📦 Estrutura do projeto
- controller → endpoints da API
- service → regras de negócio
- repository → acesso ao banco de dados

## ▶️ Como executar

1. Clonar o repositório:

git clone https://github.com/kauawfernandes/clinica-api.git

2. Configurar o banco de dados no `application.properties`

3. Rodar o projeto:

./mvnw spring-boot:run

4. A API estará disponível em:

http://localhost:8080

## 📌 Próximas melhorias
- Autenticação com JWT
- Documentação com Swagger
- Testes automatizados

## 👨‍💻 Autor
Kauã Fernandes
