# 🏙️ Projeto Semestral - Estruturas de Dados I (2025)

Este repositório contém o projeto semestral da disciplina **Estruturas de Dados I**, que consiste no desenvolvimento de um **Simulador de Atendimento Inteligente em Situações de Emergência Urbana**. O objetivo é aplicar estruturas de dados clássicas em um cenário realista, visando eficiência, organização e tomada de decisão inteligente.

---

## 📘 Contexto

O sistema simula o atendimento de emergências (como SAMU, Bombeiros e Polícia) em uma cidade fictícia. Ele gerencia cidadãos, bairros e unidades de serviço, e responde a chamados em tempo real, organizando os atendimentos com base em critérios de gravidade e prioridade.

---

## 🎯 Objetivos Técnicos

- Aplicar estruturas de dados clássicas (filas, pilhas, árvores, hashing, listas cruzadas)
- Desenvolver incrementalmente um sistema funcional de simulação
- Utilizar algoritmos de busca e ordenação eficientes
- Produzir documentação técnica clara e modularizar o código

---

## 🧩 Funcionalidades Implementadas

### ✅ Fase 1 – Simulação Básica
- Cadastro de bairros (usando hashing)
- Cadastro de unidades de serviço (ambulância, polícia, etc.)
- Simulação de **filas** de atendimento por ordem de chegada

### ✅ Fase 2 – Histórico e Busca
- Armazenamento de histórico de atendimentos com **pilhas**
- Busca rápida de cidadãos e bairros com hashing
- Representação da cidade com **listas cruzadas** entre bairros e serviços

### ✅ Fase 3 – Priorização Inteligente
- Inserção de chamados em uma **árvore binária de busca** (BST)
- Priorização automática por gravidade usando **árvore AVL**
- Substituição de buscas sequenciais por estruturas balanceadas

---

## 🗃️ Estruturas de Dados Utilizadas

| Estrutura               | Aplicação                                           |
|-------------------------|-----------------------------------------------------|
| 🧺 Fila                  | Simulação da ordem de atendimento                   |
| 🧱 Pilha                 | Histórico de atendimentos                          |
| 🔑 Hashing              | Acesso rápido a cidadãos, bairros e unidades       |
| 🔗 Lista Cruzada         | Conexão entre bairros e serviços                   |
| 🌳 Árvore Binária        | Organização de ocorrências por ID ou data          |
| 🌲 Árvore AVL            | Priorização por gravidade com balanceamento        |

---

## 🛠️ Como Executar

1. Faça o clone ou download do projeto:
   ```bash
   git clone https://github.com/seu-usuario/trabalho-ed1-2025.git
