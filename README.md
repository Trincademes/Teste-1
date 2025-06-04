# 🎓 Plataforma Escolar - Back-End ASP.NET

Este projeto é o back-end de uma plataforma escolar, desenvolvido em **ASP.NET Core**, com foco em segurança, autenticação moderna, testes automatizados e arquitetura escalável.

## 🚀 Tecnologias Utilizadas

### 🧠 Framework e Plataforma
- **ASP.NET Core 7+** – Framework principal para construção de APIs RESTful.
- **Entity Framework Core** – ORM para acesso e manipulação de dados.
- **AutoMapper** – Mapeamento automático entre entidades e DTOs.
- **FluentValidation** – Validação fluente e desacoplada de dados.
- **Swagger (Swashbuckle)** – Documentação interativa da API.

### 🔒 Segurança e Autenticação
- **ASP.NET Identity** – Gerenciamento completo de usuários, senhas e funções.
- **JWT (JSON Web Tokens)** – Autenticação baseada em tokens.
- **Role-based Authorization** – Controle de acesso por tipo de usuário (Aluno, Professor, Admin).
- **Authorization Policies** – Regras personalizadas para controle de permissões.
- **CORS & CSRF Protection** – Segurança entre domínios e proteção contra ataques.

### 🧪 Testes Automatizados
- **xUnit** – Estrutura para testes unitários.
- **Moq** – Biblioteca para simular dependências (mocking).
- **FluentAssertions** – Sintaxe mais expressiva para asserções.
- **WebApplicationFactory** – Criação de servidores de teste para APIs.
- **TestServer** – Testes de integração simulando chamadas HTTP reais.
- **Coverlet** – Análise de cobertura de testes.

### 🧩 Extras e Boas Práticas
- **Serilog** – Logging estruturado com suporte a diversos sinks (console, arquivo, banco).
- **MediatR** (opcional) – Implementação do padrão CQRS.
- **Repository Pattern + Unit of Work** – Organização e abstração do acesso a dados.
- **Clean Architecture** – Separação clara entre camadas: Domain, Application, Infrastructure e API.

---

## 📁 Estrutura de Projeto Recomendada