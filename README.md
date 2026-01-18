# 🍽️ Cardápio Fullstack

Um sistema completo de gerenciamento de cardápio, permitindo **criar, listar, atualizar e deletar alimentos**.  
Desenvolvido como exemplo de integração **frontend/backend** com banco de dados relacional.

---

## 🛠 Tecnologias Utilizadas

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)
![React Query](https://img.shields.io/badge/React%20Query-FF4154?style=flat&logo=react-query&logoColor=white)

---

## 📂 Estrutura do Projeto

```bash
cardapio-fullstack/
├─ backend/ # Projeto Spring Boot
│ ├─ src/
│ ├─ pom.xml
│ └─ application.properties
├─ frontend/ # Projeto React + TypeScript
│ ├─ src/
│ ├─ package.json
│ └─ vite.config.ts
├─ .gitignore
└─ README.md
```
---

## 🖼️ Demonstração

Abaixo estão algumas telas do projeto:

![Tela Home](./demo/home.png)

![Adicionar Alimentos](./demo/modal.png)

---

## ⚙️ Funcionalidades

- ✅ Listar alimentos  
- ✅ Adicionar novos alimentos  
- ✅ Editar informações de alimentos existentes  
- ✅ Deletar alimentos  

---

## 💻 Como Rodar Localmente

### 1️⃣ Backend

```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
```
O backend estará disponível em http://localhost:8080.

```bash
cd frontend
npm install
npm run dev
```
O frontend estará disponível em http://localhost:5173.

Certifique-se de que o backend esteja rodando para que o frontend consiga fazer requisições.
---

## 📌 Observações

Projeto feito para fins educacionais e portfólio. </br>
Demonstra boas práticas de integração frontend/backend, CRUD completo e uso de banco de dados relacional.</br>
Ideal para demonstrar conhecimentos em React, TypeScript, Spring Boot e PostgreSQL.
