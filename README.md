# Projeto-web-

# ProjetoWeb - Cadastro de Usuário

Projeto simples em **ASP.NET Web Forms (VB.NET)** para cadastro de usuários com integração ao **SQL Server**.

---

## 📂 Estrutura

CREATE DATABASE ProjetoWebDB;
GO

USE ProjetoWebDB;
GO

CREATE TABLE Usuarios (
    Id INT PRIMARY KEY IDENTITY,
    Nome NVARCHAR(100) NOT NULL,
    Email NVARCHAR(100) NOT NULL UNIQUE,
    Senha NVARCHAR(100) NOT NULL
);













