# Cardápio Fullstack CRUD

Um sistema completo de gerenciamento de cardápio, permitindo **criar, listar, atualizar e deletar alimentos**.  
Este projeto foi desenvolvido como exemplo de integração entre **frontend e backend**, com comunicação com banco de dados relacional.

---

## 🚀 Tecnologias utilizadas

### Backend
- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL

### Frontend
- React 18
- TypeScript
- Vite
- Axios
- React Query

---

## 📂 Estrutura do projeto

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

yaml
Copiar código

---

## ⚙️ Funcionalidades

- ✅ Listar alimentos
- ✅ Adicionar novos alimentos
- ✅ Editar informações de alimentos existentes
- ✅ Deletar alimentos

---

## 💻 Como rodar o projeto localmente

### 1. Backend
```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
O backend estará disponível em http://localhost:8080.

2. Frontend
bash
Copiar código
cd frontend
npm install
npm run dev
O frontend estará disponível em http://localhost:5173.

Certifique-se de que o backend esteja rodando para que o frontend consiga fazer requisições.

🖼️ Demonstração
Coloque aqui imagens ou GIFs do seu projeto funcionando.
Exemplo:



Dica: use ferramentas como ScreenToGif para criar GIFs mostrando o CRUD em ação.

📌 Observações
Projeto feito para fins educacionais e portfólio.

Demonstra boas práticas de integração frontend/backend e CRUD completo com banco de dados relacional.

