# API de Receitas

Este projeto consiste na implementação de uma API de Receitas utilizando ASP.NET. A API permite retornar todas as receitas disponíveis, adicionar, remover e atualizar as mesmas. Além disso, possibilita o cadastro, remoção, consulta e atualização de dados de usuários do aplicativo, bem como o cadastro e consulta de comentários nas receitas.

## Objetivos

O objetivo deste projeto é demonstrar habilidades em ASP.NET, integração com C#, arquitetura MVC e criação de controllers que recebem dados pelo corpo e pela URL da requisição. Além disso, é importante lançar códigos de retorno que respeitem o padrão do HTTP Status Code.

## Funcionalidades

### Receitas

- **GET /recipe**: Retorna todas as receitas disponíveis.
- **GET /recipe/:name**: Retorna detalhes de uma receita específica com base no nome.
- **POST /recipe**: Adiciona uma nova receita.
- **PUT /recipe**: Atualiza uma receita existente.
- **DEL /recipe/:name**: Remove uma receita com base no nome.

### Usuários

- **GET /user/:email**: Retorna informações de um usuário com base no email.
- **POST /user**: Adiciona um novo usuário.
- **PUT /user/:email**: Atualiza informações de um usuário existente.
- **DEL /user/:email**: Remove um usuário com base no email.

### Comentários

- **POST /comment**: Adiciona um novo comentário em uma receita.
- **GET /comment/:recipeName**: Retorna todos os comentários de uma receita específica com base no nome da receita.

## Como Utilizar

1. Clone o repositório para sua máquina local.
2. Instale as dependências utilizando o comando `npm install`.
3. Execute os testes unitários utilizando o comando `npm test`.
4. Analise os resultados dos testes para garantir que todas as funções estão funcionando corretamente.

## Contribuição

Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Clone o fork para a sua máquina local.
3. Implemente suas alterações ou novas funcionalidades.
4. Faça testes locais para garantir que tudo está funcionando conforme o esperado.
5. Faça push das suas alterações para o seu fork.
6. Envie um pull request para este repositório.

## Tecnologias Utilizadas

- ASP.NET
- C#
- MVC

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Email: [rdrigo019@gmail.com]

