# 💈 Agenda Barbearia

Sistema de agendamento de barbearia desenvolvido como projeto da disciplina de Programação Web — UEPB 2026.1.

## 📋 Sobre o projeto

Aplicação web simples para gerenciar agendamentos de uma barbearia, permitindo cadastrar clientes, barbeiros, serviços e horários.

## 🚀 Funcionalidades

- Cadastro de clientes
- Cadastro de barbeiros
- Cadastro de serviços
- Agendamento de horários (CRUD completo)

## 🗂️ Classes do domínio

- **Cliente** — id, nome, telefone, email
- **Barbeiro** — id, nome, especialidade
- **Servico** — id, nome, preço, duração
- **Agendamento** — id, cliente, barbeiro, serviço, data, hora, status

## 🔗 Relações entre as classes

- `Agendamento` se associa a `Cliente`
- `Agendamento` se associa a `Barbeiro`
- `Agendamento` se associa a `Servico`

## 🛠️ Tecnologias

- Node.js (http nativo — sem framework)
- HTML + Bootstrap 5
- JavaScript
