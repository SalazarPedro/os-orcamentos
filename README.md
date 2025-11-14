# OS & Orçamentos – Sistema Web  
**OS & Budget Generator – Web System**

---

## Descrição Geral

Plataforma para criação e edição de Ordens de Serviço e orçamentos, automatizando cálculos de mão de obra e materiais com base em uma tabela de preços, com dados centralizados no Google Sheets.

Este projeto foi desenvolvido para uma empresa que precisava de uma solução simples, rápida e de baixo custo para organizar OSs e gerar orçamentos automaticamente, sem depender de sistemas complexos.  
O sistema é dividido em duas partes: **Cadastro de OS** e **Geração de Orçamento**.

---

## Funcionalidades

### **Cadastro de Ordens de Serviço**
- Nome do cliente  
- Endereço  
- Descrição  
- Número da OS gerado automaticamente  
- Geração automática do documento de OS

### **Gerador de Orçamentos**
- Buscar OS existente e visualizar seus dados  
- Adicionar ou editar observações  
- Adicionar materiais com autocomplete  
- Quantidade dos materiais editável  
- Cálculos automáticos:
  - Preço total dos materiais  
  - Mão de obra  
  - Total final  
- Salvar orçamento vinculado à OS  
- Gerar documento de orçamento  
- Registrar informações no Google Sheets  
- Backend totalmente integrado via Google Apps Script

---

## Tecnologias Utilizadas

- **HTML5** – interface do usuário  
- **CSS3** – estilização  
- **JavaScript** – lógica do front-end  
- **Google Apps Script** – backend e integração com planilhas  
- **Google Sheets** – banco de dados de materiais e registros  

---

## Como Funciona

### **1. Cadastro da OS**
1. O usuário acessa a página de criação de OS.  
2. Preenche:
   - Nome  
   - Endereço  
   - Descrição  
3. O sistema gera automaticamente o número da OS (ex: `001/2025`).  
4. A OS é salva no Google Sheets, ficando disponível para edição e geração de orçamento.  
5. Um documento de Ordem de Serviço é gerado e o link aparece na tela e na planilha.

### **2. Geração do Orçamento**
1. O usuário informa o número de uma OS já cadastrada.  
2. O sistema busca todas as informações da OS no Google Sheets.  
3. É possível adicionar ou editar observações.  
4. O usuário adiciona materiais e define quantidades (ou edita as existentes).  
5. Pode inserir o valor de mão de obra.  
6. O sistema calcula automaticamente:
   - Total dos materiais  
   - Mão de obra  
   - Valor final  
7. O orçamento é salvo na planilha em uma aba específica.  
8. Um documento final do orçamento é gerado e o link é exibido na tela.


---

## Overview

Platform for creating and editing Work Orders (WO) and budgets, automating labor and material calculations based on a price table, with all data centralized in Google Sheets.

This project was developed for a company that needed a simple, fast, and low-cost solution to organize Work Orders and automatically generate budgets without relying on complex systems.  
The system is divided into two parts: Work Order Registration and Budget Generation.

---

## Features

### Work Order Registration
- Client name  
- Address  
- Description  
- Automatically generated WO number  
- Generate a Work Order document  

### Budget Generator
- Search and view information from an existing Work Order  
- Add observations  
- Add materials with autocomplete  
- Automatically calculate:
  - Material costs  
  - Labor costs  
  - Total budget  
- Generate and save a budget linked to the WO  
- Generate a budget document  
- Record all data in a Google Sheets spreadsheet  
- Backend logic fully integrated through Google Apps Script  

---

## Technologies Used

- **HTML5** – user interface  
- **CSS3** – styling  
- **JavaScript** – front-end logic  
- **Google Apps Script** – backend and spreadsheet requests  
- **Google Sheets** – database for materials and records  

---

## How It Works

### 1. Work Order Registration
1. The user accesses the Work Order creation page.  
2. Fills in:
   - Client name  
   - Address  
   - Description  
3. The system automatically generates the WO number (e.g., 001/2025).  
4. The WO is saved in Google Sheets and becomes available for edits and budget creation.  
5. A Work Order document is generated, with the link displayed on screen and stored in the spreadsheet.  

### 2. Budget Generation
1. The user enters the number of an existing Work Order.  
2. The system retrieves all information from Google Sheets.  
3. The user may add observations or edit the retrieved information.  
4. The user adds materials and quantities, or updates existing ones.  
5. The user can input the labor cost.  
6. The system automatically calculates:  
   - Total materials  
   - Labor  
   - Final total amount  
7. The budget is saved in a dedicated tab in the spreadsheet, and a budget document is generated automatically.  
8. A link to the final budget document is displayed on screen.

---

## License

This project is released under the **MIT License**.
