# 🍔 Sistema de Controle — Lanchonete Ennius Muniz

Sistema desenvolvido em **Python** utilizando **SQLite** para realizar o cadastro e a consulta de produtos de uma lanchonete.

## 📌 Sobre o projeto

O projeto foi desenvolvido como atividade do curso **Técnico em Desenvolvimento de Sistemas — Senac**.

O sistema permite controlar produtos cadastrados no estoque de uma lanchonete, armazenando informações como:

* Nome do produto
* Preço
* Quantidade em estoque

Os dados são armazenados em um banco de dados **SQLite**, permitindo que continuem salvos mesmo depois que o programa é fechado.

## ⚙️ Funcionalidades

### 1. Cadastrar produtos

Permite cadastrar novos produtos informando:

* Nome
* Preço
* Quantidade em estoque

### 2. Consultar produtos

Exibe todos os produtos cadastrados no banco de dados, mostrando:

* Nome
* Preço
* Estoque

### 3. Sair do sistema

Encerra o programa e fecha a conexão com o banco de dados.

## 🛠️ Tecnologias utilizadas

* 🐍 **Python**
* 🗄️ **SQLite**
* 📦 Biblioteca `sqlite3`
* 💻 Terminal/Console


## 🗃️ Banco de dados

O projeto utiliza o **SQLite**, um banco de dados leve que não precisa de um servidor separado.

A tabela utilizada pelo sistema é:

```text
produtos
├── nome
├── preco
└── quantidade
```

## 🎯 Objetivo

O objetivo do projeto é praticar conceitos fundamentais de **Python, funções, estruturas de repetição, entrada de dados e integração com banco de dados SQLite**.

## 👨‍💻 Autor

**Talisson Alves Lima**

Projeto acadêmico desenvolvido no curso **Técnico em Desenvolvimento de Sistemas — Senac**.
