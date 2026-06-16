### English

# CRUD Generator Skill for ChatGPT

A productivity-focused ChatGPT skill that automatically generates complete CRUD structures from a database table definition.

Instead of spending time creating repetitive boilerplate code such as:

* Entities
* DTOs
* AutoMapper Profiles
* Controllers
* Services
* Repositories
* Entity Framework Mappings
* FluentValidation Validators
* Interfaces
* Dependency Injection registrations

Simply provide a SQL table definition and follow the guided steps. The skill will ask a few questions about your preferences and then generate all required files ready to copy and paste into your project.

## Example Input

```sql
CREATE TABLE schema.organization (
    orga_cd_orgao bigint not null,
    orga_nm_orgao varchar(200),
    orga_cd_orgao_sup bigint,
    orga_dt_inicio_validade timestamp,
    orga_dt_fim_validade timestamp,
    orga_dt_exclusao timestamp
);
```

## Features

* Automatic Entity generation
* DTO generation (Request, Response, Create, Update)
* AutoMapper Profile generation
* Repository pattern implementation
* Service layer generation
* Controller generation
* FluentValidation generation
* Entity Framework Mapping configuration
* Soft Delete support
* Audit field support
* Clean Architecture friendly structure
* .NET 7 / .NET 8 compatible

## Why?

Most CRUD implementations contain a large amount of repetitive code that provides little business value but consumes valuable development time.

This skill automates the boring parts, allowing developers to focus on:

* Business rules
* Architecture decisions
* Performance improvements
* Security
* System integrations

## Goal

Reduce development time, eliminate repetitive manual work, and accelerate project delivery while maintaining consistent code structure and standards.

Feel free to customize the generated code according to your project's conventions and architecture.



### Portugues

# 🚀 Skill Geradora de CRUD para ChatGPT

Uma skill criada para automatizar a geração de CRUDs completos a partir da definição de uma tabela de banco de dados.

Em vez de gastar tempo criando manualmente dezenas de arquivos repetitivos, basta informar a estrutura da tabela e seguir o assistente passo a passo.

A skill fará perguntas sobre o que deseja gerar e, ao final, entregará todos os arquivos prontos para copiar e colar no projeto.

---

## 📋 O que ela pode gerar

* Entidades (Entity)
* DTOs (Request, Response, Create e Update)
* AutoMapper Profiles
* Controllers
* Services
* Repositories
* Interfaces
* Mapeamentos do Entity Framework
* FluentValidation
* Soft Delete
* Campos de Auditoria
* Injeção de Dependência
* Estrutura compatível com Clean Architecture

---

## 💡 Exemplo de entrada

```sql
CREATE TABLE schema.orgao (
    orga_cd_orgao bigint not null,
    orga_nm_orgao varchar(200),
    orga_cd_orgao_sup bigint,
    orga_dt_inicio_validade timestamp,
    orga_dt_fim_validade timestamp,
    orga_dt_exclusao timestamp
);
```

---

## ⚙️ Como funciona

1. Copie a Skill.
2. Cole no ChatGPT.
3. Informe a estrutura da tabela.
4. Responda às perguntas do assistente.
5. Receba todos os arquivos gerados.

A experiência foi projetada para funcionar como um assistente de desenvolvimento, guiando você por todas as etapas da criação do CRUD.

---

## 🎯 Objetivo

Todo desenvolvedor conhece aquela tarefa repetitiva que sempre aparece:

* Criar Entity
* Criar DTO
* Criar Repository
* Criar Service
* Criar Controller
* Criar Validator
* Criar Mapping

Esse processo normalmente consome tempo e raramente agrega valor ao negócio.

A proposta desta skill é automatizar esse trabalho repetitivo para que você possa focar no que realmente importa:

* Regras de negócio
* Arquitetura
* Performance
* Segurança
* Integrações
* Experiência do usuário

---

## ✅ Benefícios

* Redução significativa do tempo de desenvolvimento
* Padronização do código
* Menos erros de digitação e inconsistências
* Maior produtividade da equipe
* Geração rápida de código boilerplate

---

## 🛠 Compatibilidade

* .NET 7
* .NET 8
* Entity Framework Core
* AutoMapper
* FluentValidation
* Arquiteturas em Camadas
* Clean Architecture

---

## ⚠️ Observação

A skill foi criada para acelerar o desenvolvimento de código repetitivo. O código gerado pode e deve ser adaptado às necessidades e padrões do seu projeto.

Use a automação para economizar tempo e concentre seus esforços nos problemas que realmente exigem conhecimento e experiência.
