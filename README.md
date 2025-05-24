# Levantamento de Requisitos - Escola Data Science (Alura)

Este projeto visa estruturar e organizar os dados da empresa para torná-los mais acessíveis e facilitar a localização de informações críticas. Abaixo estão os requisitos e detalhes essenciais do projeto.

---

## 📌 **Objetivos Principais**
- Tornar a base de dados mais acessível para todas as partes envolvidas no negócio.
- Facilitar a busca e recuperação de informações cadastradas.

---

## 📂 **Fontes de Dados**
- Dados atualmente armazenados em **planilhas**.

---

## 💾 **Dados Armazenados**
### **Clientes**
- Nome, CPF, telefones (obrigatoriamente 2), endereço completo, data de nascimento, e-mail.
### **Dados Bancários**
- Tipo de conta, saldo, número da conta, data de abertura.
### **Score de Crédito**
- Pontuação, justificativa, data da consulta, fonte.
### **Empréstimos**
- Valor, status, tipo (pessoal, consignado, com garantia), data de início, prazo, nome do cliente.
### **Pagamentos**
- Data da parcela, valor pago, status da parcela.
### **Colaboradores**
- Nome, CPF, telefone, salário, cargo, e-mail.
### **Departamentos**
- Número do departamento, nome, gerente.

---

## 🔄 **Processos de Negócio Integrados**
### **Clientes**
- Cadastro obrigatório de **2 telefones** e **1 e-mail**.
- Consulta automática de **score de crédito** ao cadastrar novo cliente.
- Criação automática de conta para novos clientes.
- Um cliente pode ter **múltiplas contas** (incluindo contas conjuntas) e **vários empréstimos**.
### **Empréstimos**
- Tipos disponíveis: pessoal, consignado, com garantia.
- Um empréstimo só pode ser vinculado a **um cliente por vez**, mas um cliente pode ter **vários empréstimos**.
- Cada empréstimo pode ter **múltiplas parcelas**.
### **Colaboradores**
- Vendedores são responsáveis por gerenciar dados de clientes.
### **Departamentos**
- Devem ter **no mínimo 2 colaboradores** para existir.
- Gerenciados por um colaborador específico.

---

## 📊 **Uso dos Dados no Dia a Dia**
- Geração de **relatórios para tomada de decisão**.
- Análise de perfil de clientes para melhorias estratégicas.
- Controle de **inadimplência** e acompanhamento de pagamentos.

---

## 🚀 **Expectativas de Crescimento**
- Adoção de **novas ferramentas tecnológicas**.
- Expansão para **abertura de filiais**.
- Inclusão de novos serviços (ex.: outros tipos de empréstimos).

---

## 🛠 **Desafios Atuais**
- Organização e padronização inadequada das planilhas.
- Dificuldade em **localizar informações de clientes**.
- Migração para novas ferramentas de armazenamento.

---

## ⚙️ **Instalação e Configuração**
_(Adicione aqui instruções para configurar o ambiente, dependências e como executar o projeto.)_

---

## 🤝 **Como Contribuir**
1. Faça um fork do repositório.
2. Crie uma branch com sua feature: `git checkout -b minha-feature`.
3. Envie um pull request com as alterações propostas.

---

## 📜 **Licença**
Este projeto está sob a licença [MIT](LICENSE).
