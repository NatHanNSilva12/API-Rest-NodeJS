# API RESTful de Livraria

Este projeto é uma API RESTful de uma livraria, desenvolvida em Node.js como parte dos estudos no Centro Paula Souza (Etec). A API permite realizar operações de CRUD (Criar, Ler, Atualizar e Deletar) em um banco de dados de livros.

## Funcionalidades

A API possui as seguintes funcionalidades:
- **Adicionar Livro**: Permite adicionar novos livros ao catálogo.
- **Consultar Livros**: Recupera a lista completa de livros ou detalhes de um livro específico.
- **Atualizar Livro**: Atualiza informações de um livro existente.
- **Remover Livro**: Remove um livro do catálogo.

## Tecnologias Utilizadas

- **Node.js**: Plataforma utilizada para o desenvolvimento do backend.
- **Express.js**: Framework para construção da API.
- **Nodemon**: Ferramenta utilizada durante o desenvolvimento para reiniciar automaticamente o servidor sempre que houver mudanças no código.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/NatHanNSilva12/API-Rest-NodeJS.git
    ```

2. Acesse o diretório do projeto:
    ```bash
    cd API-Rest-NodeJS
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Inicie o servidor:
    ```bash
    npm run dev
    ```

O servidor estará disponível em `http://localhost:3000`.

### Exemplo de Objeto Livro
```json
{
  "title": "O Senhor dos Anéis",
  "author": "J.R.R. Tolkien",
  "year": 1954,
  "genre": "Fantasia"
}

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar um problema.

Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Contato
Desenvolvedor: Nathan Silva
GitHub: https://github.com/NatHanNSilva12
Email: nathannssilva12@gmail.com
