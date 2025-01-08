# To-Do List TypeScript

Aplicação para gerenciamento de tarefas utilizando Node.js com TypeScript, seguindo boas práticas e padrões de projeto.

## Sumário

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Status](#status)
- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Explicação](#explicação)
- [Como Usar](#como-usar)
- [Autor](#autor)

## Tecnologias Utilizadas

<div style="display: flex; flex-direction: row;">
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/ts.png" alt="Logo TypeScript" width="100"/>
  </div>
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/node.png" alt="Logo Node.js" width="100"/>
  </div>
  <div style="margin-right: 20px; display: flex; justify-content: flex-start;">
    <img src="img/mongodb.png" alt="Logo MongoDB" width="100"/>
  </div>
</div>

## Status

![Em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge)

## Descrição

Aplicação back-end para gerenciamento de tarefas, implementada com Node.js e TypeScript. Este projeto utiliza MongoDB para armazenamento de dados, e foi configurado com ESLint para garantir a qualidade do código.

## Funcionalidades

- Adicionar, editar e remover tarefas.
- Marcar tarefas como concluídas.
- Listar todas as tarefas ou filtrar por status.
- Persistência de dados em banco MongoDB.

## Explicação

Este projeto segue o modelo MVC (Model-View-Controller) para organizar a aplicação:

- **Model**: Gerencia a interação com o banco de dados MongoDB.
- **Controller**: Processa as requisições e respostas.
- **View**: Não se aplica neste projeto, sendo uma API back-end.

Adicionalmente, o TypeScript foi configurado para emitir código JavaScript ES2019 no diretório `dist`, utilizando ferramentas como `tsc-watch` para um fluxo de desenvolvimento ágil.

## Como Usar

1. Certifique-se de ter o Node.js (>=20.0.0) e MongoDB instalados.
2. Clone o repositório e instale as dependências:
   ```bash
   git clone <url_do_repositorio>
   cd <diretorio_do_projeto>
   npm install
   ```
3. Inicie o servidor:
   ```bash
   npm start
   ```
4. Acesse a API pela porta padrão (ex.: `http://localhost:3000`).

## Autor

Desenvolvido por Diego Franco

