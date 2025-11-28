# 💾 Modelagem de Banco de Dados 

## 🎯 Sobre o Projeto e a Disciplina

Este diretório armazena todos os artefatos de modelagem de dados desenvolvidos para a disciplina de **Modelagem de Banco de Dados**, parte integrante do primeiro semestre.

O projeto visa demonstrar a proficiência na tradução de regras de negócio em um modelo de dados robusto e normalizado, culminando na geração de scripts SQL para implementação em um Sistema Gerenciador de Banco de Dados (SGBD) relacional.

**Objetivos Alcançados:**
* Análise detalhada das regras de negócio do cenário proposto.
* Criação dos Modelos Conceitual, Lógico e Físico.
* Aplicação correta das formas normais (1FN, 2FN e 3FN) para garantir a integridade dos dados.

---

## 🏗️ Estrutura do Repositório

O conteúdo está organizado por etapas de modelagem para facilitar a navegação e o entendimento:

| Diretório | Conteúdo Principal | Descrição |
| :--- | :--- | :--- |
| **`01_Documentacao/`** | Regras de Negócio, Relatório de Normalização. | Documentos que fundamentam as escolhas de design e a análise de requisitos. |
| **`02_Modelos_Diagramas/`** | Diagramas MCD (Conceitual) e MLD (Lógico). | Arquivos visuais (`.png`, `.mwb`, `.drawio`) que representam a estrutura de dados. |
| **`03_Scripts_SQL/`** | `MFD_Estrutura.sql`, `DML_Dados.sql`, `Consultas_Exemplos.sql`. | Scripts executáveis para criação da base de dados e manipulação de dados. |

---

## 🛠️ Tecnologias e Pré-requisitos

Para visualizar os modelos e executar os scripts, você precisará das seguintes ferramentas:

* **SGBD Relacional:** MySQL, PostgreSQL, SQL Server (Recomendado: MySQL).
* **Cliente SQL:** MySQL Workbench, PgAdmin, DBeaver ou similar.
* **Ferramenta de Modelagem:** MySQL Workbench ou outra que suporte o formato dos diagramas.

---

## 🚀 Guia de Execução (SQL)

Siga os passos abaixo para montar o banco de dados em seu ambiente local:

1.  **Acesse o Cliente SQL:** Abra sua ferramenta de administração (ex: MySQL Workbench) e conecte-se ao SGBD.
2.  **Crie o Esquema:** Execute o comando `CREATE DATABASE [NomeDoSeuBanco];` (Use o nome que preferir para o banco de dados do projeto).
3.  **Crie a Estrutura (DDL):**
    * Abra e execute o arquivo **`03_Scripts_SQL/MFD_Estrutura.sql`**. Este script cria todas as tabelas, chaves primárias e chaves estrangeiras.
4.  **Insira os Dados (DML):**
    * Abra e execute o arquivo **`03_Scripts_SQL/DML_Dados.sql`**. Este script populará as tabelas com um conjunto de dados para teste.
5.  **Validação:**
    * Execute as consultas de exemplo disponíveis em **`03_Scripts_SQL/Consultas_Exemplos.sql`** para verificar se as relações e os dados foram inseridos corretamente.

---
