# Visão Geral

Este documento explica o funcionamento geral do sistema, que é dividido em duas partes: criação de OS e geração de orçamentos.

## 1. Cadastro de OS

O usuário preenche:

- Nome do cliente  
- Endereço  
- Descrição do serviço  

O sistema gera automaticamente o número da OS e salva tudo no Google Sheets.  
Depois, cria um documento da OS contendo todas as informações e com espaço para anotações de campo.

## 2. Geração de Orçamento

O usuário busca uma OS já cadastrada e pode:

- Adicionar observações  
- Inserir mão de obra  
- Adicionar materiais com autocomplete baseado em uma tabela
- Ver o total atualizado automaticamente
- Editar, caso precise adicionar algo a algum orçamento já feito

O orçamento é salvo no Google Sheets e um documento é gerado automaticamente.

Caso queira ver mais de como funciona:

[Tecnologias Utilizadas] (tech-stack.md)
[Estrutura da Planilha] (data-structure.md)
[Links de Demonstração] (demo-links.md)
