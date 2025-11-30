# 🏨 Projeto de Modelagem de Banco de Dados: Sistema de Gerenciamento de Hotel

Este repositório contém os scripts SQL e o Diagrama de Entidade-Relacionamento (DER) para o banco de dados de um sistema de gerenciamento hoteleiro. O projeto visa demonstrar a aplicação de conceitos de modelagem relacional e operações CRUD (Create, Read, Update, Delete) no MySQL.

## 📐 Diagrama de Entidade-Relacionamento (DER)

O modelo foi desenvolvido com base no seguinte diagrama, que define as entidades (Hospede, Quarto, Reserva, etc.) e seus relacionamentos (1:N, N:M).

![Diagrama de Entidade-Relacionamento do Projeto Hotel](Banco%20de%20dados%20hotel.jpg)

## 📋 Pré-requisitos

Para executar os scripts, você precisará ter instalado:

1.  **MySQL Server:** Versão 8.0 ou superior.
2.  **MySQL Workbench** ou qualquer cliente SQL de sua preferência (DBeaver, VS Code com extensão SQL).

## 🚀 Instruções de Execução

Siga a ordem dos scripts para montar o banco de dados corretamente, garantindo a integridade referencial.

### Ordem de Execução

1.  **Montar a Estrutura:**
    Execute o script `01_schema_creation.sql`. Ele cria o schema `hotel_db` e todas as 8 tabelas com suas chaves primárias e estrangeiras.

2.  **Popular os Dados:**
    Execute o script `02_data_population.sql`. Ele insere dados de exemplo (hóspedes, quartos, funcionários, reservas e serviços) nas tabelas.

3.  **Testar as Consultas:**
    Execute o script `04_advanced_queries.sql`. Este arquivo contém consultas `SELECT` complexas que demonstram o uso de `JOIN`, `WHERE`, `ORDER BY` e `LIMIT` para extrair informações do sistema.

4.  **Testar Operações CRUD:**
    Execute o script `03_crud_operations.sql`. Este arquivo contém exemplos de comandos `UPDATE` (modificação de dados) e `DELETE` (remoção de dados) com condições específicas.

## 📄 Conteúdo dos Scripts

| Arquivo | Descrição | Requisitos Atendidos |
| :--- | :--- | :--- |
| `01_schema_creation.sql` | Criação do esquema e das 8 tabelas. | Estrutura Completa |
| `02_data_population.sql` | Comandos `INSERT` para popular todas as tabelas principais. | Scripts SQL com comandos de INSERT |
| `03_crud_operations.sql` | 3 comandos `UPDATE` e 3 comandos `DELETE`, todos com cláusulas `WHERE`. | Scripts com UPDATE e DELETE |
| `04_advanced_queries.sql` | 5 consultas `SELECT` usando `JOIN`, `WHERE`, `ORDER BY` e `LIMIT`. | Scripts SQL com consultas SELECT |
| `Banco de dados hotel.jpg` | Imagem do Diagrama ER. | Referência Visual |
