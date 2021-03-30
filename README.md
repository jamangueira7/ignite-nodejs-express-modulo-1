<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-rodar">Como rodar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-rotas">Rotas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;
  </p>

<br>


# Ignite Node.js - I projeto

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) 
- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5) 
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) 
- [NodeJS](https://nodejs.org/en/) - v15.12.0

## 💻 Projeto

Esse projeto é um API para o CRUD de contas, fazer depositos, saques e pegar o saldo da conta.

## 🚀 Como Rodar

 - Clone o projeto.
 - Entre na pasta do projeto e rode o comando "npm install" para instalar as dependências.
 - Rode "npm run dev" para iniciar o servidor.
 - Para testar, acesse localhost:3333.
 
## 👩🏿‍💻 Rotas

- **`POST /account`**: Rota para cadastra uma conta; 
  
Envio
```
{
    "cpf": "33665544744",
    "name": "João Mangueira"
}
```

- **`GET /account`**: Rota para retornar dados da conta;
  
Envio no headers
```
{
    "cpf": "33665544744"
}
```
Retorno
```
{
    "cpf": "33665544744",
    "name": "João Mangueira",
    "id": "c534e18c-da87-4ce7-9c38-50eab5ddfe86",
    "statement": []
}
```

- **`POST /deposit`**: Rota para fazer um deposito;
Envio
```
{
    "description": "Transferência",
    "amount": 200.00
}
```

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## 📝 Licença

Esse projeto está sob a licença MIT.
