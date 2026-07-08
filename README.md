# Smart Finance

> 🚧 **Status:** Em desenvolvimento

---

# Sobre o Projeto

O **Smart Finance** é um projeto de portfólio desenvolvido com o objetivo de simular um sistema utilizado em empresas reais.

O foco não é apenas implementar funcionalidades, mas aplicar boas práticas de engenharia de software, arquitetura distribuída, segurança, comunicação entre serviços e processamento assíncrono.

O projeto será desenvolvido de forma incremental, onde cada etapa introduz uma nova tecnologia ou conceito conforme ele se torna necessário.

---

# Objetivos

* Desenvolver uma aplicação Full Stack
* Integrar serviços escritos em Java e Python
* Aplicar autenticação e autorização com Spring Security
* Utilizar bancos SQL e NoSQL
* Implementar comunicação síncrona e assíncrona entre serviços
* Integrar APIs externas
* Conteinerizar toda a aplicação
* Realizar deploy em ambiente de produção

---

# Tecnologias Planejadas

### Backend

* Java
* Spring Boot
* Spring Security
* Spring Data JPA
* FastAPI

### Frontend

* React
* TypeScript
* Tailwind CSS

### Banco de Dados

* PostgreSQL
* MongoDB
* Redis

### Arquitetura

* RabbitMQ
* Spring Cloud Gateway
* Docker
* Docker Compose

---

# Roadmap de Desenvolvimento

## Sprint 0 — Planejamento

* [ ] Levantamento de requisitos
* [ ] Modelagem do domínio
* [ ] Definição da arquitetura
* [ ] Diagramas

---

## Sprint 1 — Backend Java

* [ ] Configuração do projeto
* [ ] CRUD de usuários
* [ ] CRUD de contas
* [ ] CRUD de categorias
* [ ] CRUD de transações

---

## Sprint 2 — Segurança

* [ ] Spring Security
* [ ] JWT
* [ ] Controle de acesso

---

## Sprint 3 — Frontend

* [ ] Tela de Login
* [ ] Dashboard
* [ ] Gestão financeira

---

## Sprint 4 — Serviço Python

* [ ] API com FastAPI
* [ ] Processamento de dados financeiros

---

## Sprint 5 — Integração Java ↔ Python

* [ ] Comunicação REST entre serviços

---

## Sprint 6 — Mensageria

* [ ] RabbitMQ
* [ ] Processamento assíncrono

---

## Sprint 7 — Banco NoSQL

* [ ] MongoDB

---

## Sprint 8 — Cache

* [ ] Redis

---

## Sprint 9 — APIs Externas

* [ ] Cotação de moedas
* [ ] CEP
* [ ] Outros serviços

---

## Sprint 10 — API Gateway

* [ ] Spring Cloud Gateway

---

## Sprint 11 — Docker

* [ ] Dockerfiles
* [ ] Docker Compose

---

## Sprint 12 — Deploy

* [ ] Deploy da aplicação
* [ ] Documentação de execução

---

# Estrutura Inicial

```text
smart-finance/
│
├── backend-java/
├── backend-python/
├── frontend/
├── docs/
└── README.md
```

---

# Organização do Repositório

Além do código-fonte, este repositório contará com documentação da evolução do projeto, incluindo:

* Diagramas de arquitetura
* Decisões arquiteturais (ADRs)
* Planejamento das sprints
* Fluxos de negócio

---

# Objetivo de Aprendizado

Este projeto será desenvolvido conforme novos conhecimentos forem sendo adquiridos. A ideia é estudar cada tecnologia antes de aplicá-la, simulando a evolução de um sistema real e registrando esse processo no repositório.

---

## Autor

**João Pedro**

Projeto desenvolvido para fins de estudo e composição de portfólio como Desenvolvedor Back-end Java.
