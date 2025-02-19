# Projeto API - Integração com JSONPlaceholder

Este projeto tem como objetivo praticar requisições a uma API RESTful utilizando HTML, CSS, JavaScript e Cordova. Para simular interações reais com uma API, utilizamos o [JSONPlaceholder](https://jsonplaceholder.typicode.com), que fornece dados fictícios para testes.

## Funcionalidades

O aplicativo permite:

- **Consultar um Post pelo ID**: Exibe os detalhes de um post, como título, corpo e ID do usuário.  
- **Listar Comentários do Post**: Mostra os comentários associados a um post específico.  
- **Excluir um Comentário pelo ID**: Simula a exclusão de um comentário na API.  

## Tecnologias Utilizadas

- **HTML5**: Estrutura da interface.  
- **CSS3 + jQuery Mobile**: Estilização e responsividade.  
- **JavaScript**: Manipulação da interface e chamadas à API.  
- **Cordova**: Empacotamento para dispositivos móveis.  

## Endpoints Utilizados

- `GET /posts/{id}` - Obtém um post pelo ID.  
- `GET /comments?postId={id}` - Obtém os comentários de um post.  
- `DELETE /comments/{id}` - Simula a exclusão de um comentário.  
