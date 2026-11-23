# Goodswell — E-Commerce Order Management

A React order and inventory workspace backed by a Spring Boot API with transactional stock updates and AI reorder recommendations.

## Stack
React 19 + Vite; Java 17 + Spring Boot; Spring Security/JWT; Spring Data JPA; MySQL; Redis; Spring AI; Docker Compose.

## Local setup
Copy `.env.example` to `.env`, set database, Redis, and login values, and add `AI_API_KEY` for live AI recommendations. Run `docker compose up --build`, then open `http://localhost:5173`. API health: `http://localhost:8080/api/health`.

## Hosted demo
The GitHub Pages site is a frontend demo with sample orders and browser-local state. It is not connected to the Spring API yet. Full AI and persistent operations require a deployed API, MySQL/Redis services, and a private AI provider key.
