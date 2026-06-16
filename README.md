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
