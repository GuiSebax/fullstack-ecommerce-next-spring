# 🛒 Fullstack E-commerce - Next.js + Spring Boot

Este é um projeto fullstack de um e-commerce simples, desenvolvido com **Next.js (App Router)** no frontend e **Spring Boot** no backend. Ele simula uma loja virtual com funcionalidades como autenticação, listagem de produtos, carrinho de compras e checkout.

## 🚀 Tecnologias Utilizadas

### Frontend
- [Next.js 14 (App Router)](https://nextjs.org/)
- [React 18](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)
- [React Hook Form](https://react-hook-form.com/)

### Backend
- [Spring Boot 3](https://spring.io/projects/spring-boot)
- [Spring Security (JWT)](https://spring.io/guides/gs/securing-web/)
- [JPA / Hibernate](https://hibernate.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Swagger (OpenAPI)](https://swagger.io/tools/swagger-ui/)

## 📦 Funcionalidades

- [x] Cadastro e login de usuários
- [x] Autenticação com JWT
- [x] Listagem de produtos
- [x] Carrinho de compras
- [x] Checkout e pedidos
- [ ] Painel administrativo para cadastrar produtos

## 📁 Estrutura do Projeto

fullstack-ecommerce-next-spring/
├── backend-spring/ # Backend em Spring Boot
└── frontend-next/ # Frontend em Next.js


---

## 🛠️ Como rodar o projeto localmente

> É necessário ter: Node.js, Java 17+, PostgreSQL (ou Docker) instalado.

### 🔹 Backend

```bash
cd backend-spring
./mvnw spring-boot:run
```

### 🔹 Frontend


```bash
cd frontend-next
npm install
npm run dev
```

