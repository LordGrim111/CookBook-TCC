# TCC CookBook — Site de Receitas com Integração de IA

Trabalho de Conclusão de Curso do Técnico em Desenvolvimento de Sistemas do Colégio Pedro II.

O TCC é um site que atende a todo e qualquer tipo de demanda em relação a receitas de comida. No projeto, o usuário acrescenta todos os ingredientes que possui e recebe receitas de acordo com os ingredientes informados, podendo escolher entre várias opções o que gostaria de cozinhar. O objetivo é facilitar o dia a dia — desde a dúvida do almoço de amanhã até aquele almoço de domingo com a família.

## Tecnologias

- **Front-end:** React
- **Back-end:** PHP
- **Banco de dados:** MySQL
- **IA:** inicialmente Llama, posteriormente API do Google

## Funcionalidades

- Usuário informa os ingredientes que possui
- Busca de receitas compatíveis via IA
- Exibição das receitas geradas na tela, com opção de escolha entre elas
- Armazenamento das receitas geradas no banco de dados

## Como executar

**Pré-requisitos:**
- [XAMPP](https://www.apachefriends.org/) (Apache + MySQL)
- [Node.js](https://nodejs.org/) versão 16 (versão exigida pelo projeto — veja `.node-version`)
  
**Back-end (PHP + MySQL):**
1. Copie a pasta `TCC` e cole no `htdocs` do XAMPP (`C:\xampp\htdocs`).

**Front-end (React):**
1. Abra um terminal na pasta `treact`.
2. Rode `npm install` para instalar as dependências do projeto (React, Tailwind CSS e demais bibliotecas listadas em `package.json`).
3. Rode `npm start` para iniciar o front-end em modo de desenvolvimento.
4. Acesse `http://localhost:3000` no navegador.

## Meu papel no projeto

Fui responsável pelo **back-end em PHP** e pela **integração com a API de IA**, incluindo o envio das requisições e o tratamento das respostas para exibição e armazenamento.

## Time

Projeto desenvolvido em grupo, como parte do TCC do curso técnico.
