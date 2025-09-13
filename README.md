# Ecommerce-sistema-completo-mysql
sistema completo de e-commerce desenvolvido em MYSQL, incluindo modelagem de banco de dados, tabelas para produtos, estoque, clientes (PF,PJ) pedidos, pagamentos e entregas. o projeto contem scripts SQL para criação das tabelas, inserts de exemplo e queries de consulta, pronto para para estudo e pratica de desenvolvimento de banco de dados.
 📦 Projeto Banco de Dados - E-commerce

Este projeto tem como objetivo a modelagem e implementação de um *banco de dados relacional para um sistema de e-commerce*, desenvolvido como parte de um desafio acadêmico.  
Foram aplicados conceitos de *MER (Modelo Entidade-Relacionamento), **Modelo Relacional, **Modelo Lógico* e consultas SQL (DDL, DML e DQL).

---

## 🗂 Estrutura do Projeto

### 1. Modelo Entidade-Relacionamento (MER)
O diagrama foi criado no *DBDesigner*, representando as principais entidades e relacionamentos do sistema:

- Cliente (PF/PJ)  
- Endereço  
- Fornecedor  
- Produto  
- Estoque  
- Pedido  
- Pagamento  
- Entrega  

### 2. Modelo Relacional
As tabelas foram definidas com *chaves primárias, estrangeiras, constraints de integridade e regras de negócio*.

### 3. Modelo Lógico (SQL)
Implementação no *PostgreSQL* utilizando:
- CREATE TABLE (DDL)  
- INSERT INTO (DML)  
- SELECT (DQL)  

---

## 🛠 Tecnologias Utilizadas
- PostgreSQL  
- DBDesigner (para o MER e modelo relacional)  
- SQL  

---

## 📋 Estrutura das Tabelas

- *cliente* → armazena informações de pessoas físicas ou jurídicas  
- *endereco* → vinculado ao cliente, guarda os dados de localização  
- *fornecedor* → empresas fornecedoras dos produtos  
- *produto* → catálogo de itens disponíveis para venda  
- *estoque* → quantidade disponível de cada produto  
- *pedido* → informações de compras realizadas  
- *pagamento* → dados de pagamentos relacionados aos pedidos  
- *entrega* → status e prazos de envio dos pedidos  

---

## 💾 Execução

### 1. Criar o banco de dados
```sql
CREATE DATABASE ecommerce;
\c ecommerce;
