# 🍕 Sistema de Pedidos para Pizzaria

Este projeto consiste em um **sistema simples de pedidos para pizzaria**, desenvolvido em **PHP**, que permite aos clientes realizarem pedidos através de uma interface web e possibilita ao administrador acompanhar e gerenciar esses pedidos em tempo real.

O sistema funciona **localmente** e está conectado a um **banco de dados MySQL**, permitindo o armazenamento e controle das informações dos pedidos.

---

## 📌 Funcionalidades

### 🧑‍💻 Área do Cliente
A página **index** é destinada aos clientes que desejam realizar pedidos. Nela é possível:

- Escolher o **sabor da pizza**
- Selecionar o **tipo de massa**
- Escolher a **borda da pizza**
- Enviar o pedido para a pizzaria

Após o envio, o pedido é registrado no banco de dados para ser acompanhado pela administração.

---

### 🧾 Painel Administrativo
A página **dashboard** funciona como um **painel de controle para o dono da pizzaria**, permitindo gerenciar todos os pedidos realizados.

No painel é possível:

- Visualizar todos os pedidos
- Alterar o **status do pedido**
- Acompanhar o andamento da produção

Os pedidos podem ter os seguintes status:

- 🍳 **Em produção**
- 🚚 **Em entrega**
- ✅ **Finalizado**

- ## 🗄 Banco de Dados

O sistema utiliza **MySQL** para armazenar as informações dos pedidos.

O banco de dados é responsável por guardar dados como:

- Número do pedido
- Sabor da pizza
- Tipo de massa
- Tipo de borda
- Status do pedido
- Data do pedido

A conexão com o banco é realizada através de um arquivo de configuração dentro do projeto.
