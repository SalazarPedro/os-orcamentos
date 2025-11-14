# Complemento de Ordens de Serviço — Sistema Web + Google Sheets

Este repositório contém a documentação completa de um sistema desenvolvido para uma empresa que precisava organizar Ordens de Serviço e gerar orçamentos automaticamente, de forma simples, rápida e de baixo custo.

O código principal (Google Apps Script + lógicas internas) **não está incluído por ser parte de um projeto comercial**, mas toda a arquitetura, funcionamento e conceitos estão documentados aqui.

---

## 🚀 Funcionalidades

### 🟦 1. Cadastro de Ordens de Serviço
- Nome do cliente  
- Endereço  
- Descrição da OS  
- Número da OS gerado automaticamente  
- Salvamento direto no Google Sheets  
- Geração de documento PDF da OS

### 🟩 2. Gerador de Orçamentos
- Busca automática de OS cadastradas  
- Campo de observações  
- Adição de materiais com autocomplete  
- Preços baseados em tabela no Google Sheets  
- Cálculo automático de:
  - Materiais  
  - Mão de obra  
  - Total final  
- Geração e salvamento do orçamento no Google Sheets  
- Criação automática do PDF do orçamento

---

## 🛠️ Tecnologias e Ferramentas

- **Google Apps Script** (backend + automações)
- **Google Sheets** (banco de dados)
- **HTML5, CSS3, JavaScript** (interface)
- **Google Drive API** (geração de documentos)

Mais detalhes técnicos estão na pasta [`/docs`](./docs).

---

## 📌 Arquitetura do Sistema

- O front-end (HTML/JS) roda em páginas WebApp do Apps Script.  
- O back-end manipula dados do Google Sheets.  
- Documentos de OS e Orçamentos são gerados automaticamente e armazenados no Google Drive.  

Veja o diagrama da arquitetura em:  
`/assets/diagram.png`

---

## 📄 Documentação Completa

- [Visão Geral do Projeto](./docs/overview.md)  
- [Tecnologias e Design Técnico](./docs/tech-stack.md)  
- [Estrutura das Planilhas](./docs/data-structure.md)  
- [Demonstração do Sistema](./docs/demo-links.md)

---

## 🔒 Sobre o Código

O código completo **não está incluído** porque este é um projeto comercial privado desenvolvido para uma empresa real.

Caso você queira entender a lógica usada ou implementar algo parecido, a documentação explica detalhadamente a estrutura e decisões técnicas.

---

## 📬 Contato

Se quiser saber mais sobre o sistema ou ver demonstrações privadas:  
**pedrosaraujo.ps@gmail.com**
