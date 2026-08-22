# Portfólio de Desenvolvimento Back-End & Web

[![Java](https://img.shields.io/badge/Java-17+-007396?logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![.NET 8](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Angular](https://img.shields.io/badge/Angular-17%2B-DD0031?logo=angular&logoColor=white)](https://angular.dev/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Devcontainers-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

> Olá! Sou desenvolvedor com foco principal em **Back-End** (Java/Spring Boot e C#/.NET 8) e boas práticas de Engenharia de Software.
> 
> Tenho experiência no desenvolvimento de aplicações web corporativas, construção de APIs RESTful, integração de serviços e modelagem de banco de dados. Valorizo o código limpo, a boa documentação e a aplicação prática de padrões de projeto para resolver problemas reais de negócio.

---

## 🛠️ Tecnologias & Habilidades

* **Back-End:** Java (17+), Spring Boot, C# (.NET 8 / ASP.NET Core), APIs RESTful, JPA/Hibernate, Entity Framework Core.
* **Front-End:** Angular (TypeScript), HTML5, CSS3, consumo reativo de APIs (RxJS), formulários reativos.
* **Bancos de Dados:** PostgreSQL, MySQL, modelagem relacional, consultas otimizadas e transações.
* **Arquitetura & Práticas:** Arquitetura em Camadas (Layered), Organização por Features, Autenticação JWT, Clean Code, Testes Automatizados (xUnit, Moq, Vitest).
* **Ferramentas & DevOps:** Docker, Devcontainers, Git/GitHub, GitHub Actions (CI/CD básico), Swagger/OpenAPI.

---

## 🏛️ Projetos em Destaque (Estudos de Caso)

| Projeto | Tecnologias Principais | Foco & Aprendizados Principais | Estudo de Caso |
| :--- | :--- | :--- | :--- |
| **01. Sistema de Gestão de P&D (SUFRAMA)** | Java 17, Spring Boot, Angular, MySQL | Processamento assíncrono (Google Drive API), tratamento de retries e controle de acesso multi-tenant via JWT. | 📖 [Ver Case Study](projects/01-suframa-pd-system/README.md) |
| **02. Hierarchical Team Management** | Java 17, Spring Boot, Devcontainers | Arquitetura em camadas, otimização de cache em memória para dados de mapas (GeoJSON) e documentação Swagger. | 📖 [Ver Case Study](projects/02-hierarchical-team-management/README.md) *(Repo Privado)* |
| **03. Gestão de Estoque & Faturamento** | .NET 8, PostgreSQL, Angular 22 | Desafio prático explorando microsserviços, controle de idempotência, prevenção de concurrency/race condition e 67 testes. | 💻 [Ver Código & README](https://github.com/CarlosHygor/Korp_Teste_CarlosHygor) *(Repo Público)* |

---

## 🔍 Detalhes dos Projetos

### 🏢 1. Automação e Gestão de Relatórios P&D (SUFRAMA)
* **Escopo:** Sistema web completo para automação e gestão de relatórios anuais de P&D exigidos pela SUFRAMA.
* **Atuação:** Atuação no Back-End (Spring Boot) e Front-End (Angular), desde a modelagem de requisitos até a arquitetura por *features*.
* **Pontos Chave:** Integração assíncrona (`@Async`) com a API do Google Drive usando *Retry com Backoff Exponencial* para upload de evidências sem travar a interface do usuário, e isolamento de permissões por projeto via JWT Customizado.
* 📄 **[Ler Documentação Completa do Projeto 1](projects/01-suframa-pd-system/README.md)**

---

### 🗺️ 2. Hierarchical Team Management System
* **Escopo:** Sistema para controle hierárquico de equipes em múltiplos níveis e exibição de dashboards analíticos com mapas.
* **Atuação:** Desenvolvimento Back-End em Java/Spring Boot com foco em arquitetura limpa em camadas.
* **Pontos Chave:** Padronização do ambiente via **Devcontainers** (Docker), otimização de leitura de arquivos pesados de mapa em memória para reduzir latência e abstração do contexto de segurança JWT com SOLID.
* 📄 **[Ler Documentação Completa do Projeto 2](projects/02-hierarchical-team-management/README.md)**

---

### 📦 3. Sistema de Gestão de Estoque e Faturamento (.NET 8 + Angular 22)
* **Escopo:** Projeto de desafio técnico para controle de produtos, estoque e faturamento de notas fiscais.
* **Atuação:** Full-Stack (Microsserviços em .NET 8 e SPA em Angular 22).
* **Pontos Chave:** Exploração de conceitos de microsserviços e resiliência (ação compensatória em caso de falha), proteção contra saldo negativo via *Row Locking* no PostgreSQL e suíte com 67 testes automatizados (backend C# e frontend Vitest).
* 💻 **[Acessar Código-Fonte & Documentação do Projeto 3](https://github.com/CarlosHygor/Korp_Teste_CarlosHygor)**

---

## 📬 Contato

- **LinkedIn:** [CarlosHygor](https://www.linkedin.com/in/carloshygor)
- **GitHub:** [@CarlosHygor](https://github.com/CarlosHygor)
- **Email:** carlos.feliix@hotmail.com
