# 🏦 Sistema Bancário em Python (Orientado a Objetos)

Este projeto é uma refatoração de um sistema bancário simples, inicialmente estruturado de forma procedural, agora 
seguindo os princípios da **Programação Orientada a Objetos (POO)** com base em um diagrama UML.

## 📌 Funcionalidades

- Cadastro de clientes (Pessoa Física)
- Criação de contas bancárias (Conta Corrente)
- Depósitos e saques com controle de limite
- Geração de extrato
- Listagem de contas
- Histórico de transações
- Limite de saques diários por conta

## 🧱 Estrutura de Classes

- `Cliente` (superclasse)
  - `PessoaFisica` (subclasse)
- `Conta` (superclasse)
  - `ContaCorrente` (subclasse com limite e controle de saques)
- `Transacao` (classe abstrata)
  - `Deposito` (subclasse)
  - `Saque` (subclasse)
- `Historico` (armazena transações da conta)

## 📷 Diagrama UML (base para implementação)

> Este projeto foi desenvolvido com base em um diagrama UML com herança, encapsulamento e abstração aplicados corretamente.

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
