# 🛒 EzApp Store

**EzApp Store** é uma plataforma modular desenvolvida para conectar comércios locais e seus consumidores, oferecendo uma solução completa com microsserviços independentes, aplicações mobile e web, mensageria e infraestrutura moderna.

Este repositório serve como ponto central de referência pública para todos os serviços da organização.

---

## 🧱 Estrutura da Plataforma

A EzApp Store é dividida em microsserviços organizados por domínio, utilizando uma arquitetura limpa, escalável e de fácil manutenção.

### 🔧 Back-end (Microsserviços)

| Repositório | Descrição |
|-------------|-----------|
| [`ez-authuser-service`](https://github.com/ezapp-store/ez-authuser-service) | Lida com login, registro, JWT, refresh, etc |
| [`ez-user-service`](https://github.com/ezapp-store/ez-user-service) | Dados do usuário, perfil, permissões |
| [`ez-product-service`](https://github.com/ezapp-store/ez-product-service) | Lida com produtos, categorias, etc |
| [`ez-establishment-service`](https://github.com/ezapp-store/ez-establishment-service) | Dados de estabelecimento |
| [`ez-city-service`](https://github.com/ezapp-store/ez-city-service) | Dados de cidade, estado e país |
| [`ez-notification-service`](https://github.com/ezapp-store/ez-notification-service) | E-mail, push, notificações assíncronas |
| [`ez-service-registry`](https://github.com/ezapp-store/ez-service-registry) | Responsável por registrar e descobrir os microsserviços da aplicação |

---

### 🖥️ Front-end

| Repositório | Descrição |
|-------------|-----------|
| [`ez-front-web`](https://github.com/ezapp-store/ez-front-web) | Aplicação web para usuários finais, consumindo as APIs via navegador |
| [`ez-front-mobile`](https://github.com/ezapp-store/ez-front-mobile) | Aplicação mobile, conectando aos serviços via REST |

---

### ⚙️ DevOps

| Repositório | Descrição |
|-------------|-----------|
| [`ez-devops`](https://github.com/ezapp-store/ez-devops) | Centraliza os arquivos Docker, Compose e scripts para rodar os microsserviços localmente |

---

## 🚀 Tecnologias Utilizadas

- **Java + Spring Boot**
- **Flutter**
- **PostgreSQL**
- **RabbitMQ**
- **Docker & Docker Compose**
- **GitHub Actions (CI/CD)**
- **Arquitetura orientada a microsserviços**

---

## 📌 Sobre

EzApp Store foi pensado para digitalizar o comércio local, permitindo que cada parte da aplicação evolua de forma independente, com foco em modularidade, desempenho e experiência do usuário.

---

## 🤝 Contribuindo

Este projeto é mantido de forma privada no momento, mas será aberto para colaborações no futuro. Fique à vontade para acompanhar os repositórios e a evolução da plataforma.
