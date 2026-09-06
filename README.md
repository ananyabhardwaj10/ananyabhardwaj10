## Hi there 👋

<!--
**ananyabhardwaj10/ananyabhardwaj10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
## Let me introduce myself
I am Ananya Bhardwaj. 
I am a BTech Computer Science Graduate with a focus on Backend Systems. I build APIs that are reliable, secure, and designed with real word concern in mind, like authentication, authorization, data integrity and clean architecture.

## Tech Stack
**Primary:** Go, PostgreSQL, REST APIs
**Tools & Infrastructure:** SQLC, Goose, JWT Authentication
**Currently Learning:** AWS (ECS, RDS, ECR), Redis, Docker

## Project List
### ShopFlow
An e-commerce backend API built in Go that is designed to demonstrate real world backend engineering: multi role authentication, transactional order processing, and scalable API design.
**Tech-Stack:** Go, PostgreSQL, SQLC, Goose, JWT, Docker (in progress) 
### Features
- JWT authentication with refresh token rotation and Argon2id password hashing
- Role based access control: customers, sellers, with middleware enforced route protection
- Seller onboarding with atomic transactions
- Product management with Pagination
- Cart management and transactional order placement with automatic stock reduction
- Order Item Status tracking per seller
### YourNotes
A backend notes management API build in Go - focused on clean CRUD design, secure authentication, and enforced business logic.
**Tech-Stack:** Go, PostgreSQL, SQLC, Goose, JWT, Docker
### Features
- Full CRUD operations for note management via a RESTful API
- JWT authentication with refresh token rotation for secure session handling
- Business logic constraint: maximum 3 pinned notes per user enforced at the handler level
- Type safe database interactions using SQLC with PostgreSQL
- Containerized with Docker, image published on Docker Hub
