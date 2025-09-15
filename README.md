# 📝 Controle de Gastos

## 🌟 Descrição

Este projeto é uma aplicação de **Controle de Gastos Pessoais**, desenvolvida em **Java 21** com **Spring Boot** e Docker.  

A aplicação permite que o usuário:  
- 💰 Cadastrar despesas e receitas  
- 📊 Visualizar listagem de registros  
- ✏️ Editar registros existentes  
- ❌ Excluir registros  
- 🖥️ Navegar em uma interface SPA limpa, responsiva e prática  

O projeto utiliza banco de dados **PostgreSQL** no **Neon** e está disponível online via **Render**.

---

## 🛠 Tecnologias Utilizadas

| Camada        | Tecnologia                           |
|---------------|--------------------------------------|
| Back-end      | Java 21, Spring Boot                  |
| Banco de Dados| PostgreSQL (Neon)                     |
| Front-end     | SPA com htmx                          |
| Docker        | Containerização                       |
| Controle de versão | Git / GitHub                     |

---

## 📂 Estrutura do Projeto

- 📁 **controle-de-gastos/**  
  🌐 Aplicação principal com Spring Boot e SPA htmx  

- 📁 **Dockerfile**  
  🐳 Configuração do container Docker  

---

## 🔗 Acesso Online

Você pode acessar a aplicação em produção através do link:  

[🌐 Controle de Gastos no Render](https://controle-de-gastos-h7ls.onrender.com/)

---

## 🚀 Instalação e Execução Local

1. Clone o repositório:
````
git clone https://github.com/seu-usuario/controle-de-gastos.git
````

2. Entre na pasta do projeto:
````
cd controle-de-gastos
````

3. Build e Run usando Docker:
````
docker build -t controle-de-gastos .
docker run -p 8080:8080 controle-de-gastos
````

4. Acesse a aplicação no navegador:
```` 
http://localhost:8080
````

---

## 🔑 Variáveis de Ambiente

Configure as variáveis abaixo para conectar com o banco Neon:
````
SPRING_PROFILES_ACTIVE = prod
````
````
DB_USERNAME = neondb_owner
````
````
DB_PASSWORD = npg_mXr0sYPZ6aIW
````
````
DB_URL = postgresql://neondb_owner:npg_mXr0sYPZ6aIW@ep-late-bread-adlrm5t7-pooler.c-2.us-east-1.aws.neon.tech/neondb?sslmode=require&channel_binding=require
````

---

## 🎯 Funcionalidades

- 💰 Cadastro de despesas e receitas  
- 📋 Listagem de registros  
- ✏️ Edição de registros  
- ❌ Exclusão de registros  
- 🖥️ SPA responsiva e amigável  

---

## 👤 Autor

Ruan 
Curso de Análise e Desenvolvimento de Sistemas  
GitHub: [RuanTrindade](https://github.com/seu-usuario/controle-de-gastos)
