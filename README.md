# Desafio Técnico

## Full Stack

Que coisa boa te encontrarmos nesta etapa! Criamos um exercício de desenvolvimento para analisar seus conhecimentos e níveis de habilidades.

Este exercício compreende uma das etapas de avaliação das pessoas candidatas para vaga de Full Stack Developer.

O desafio consiste em criar um client e uma API, que responde as funcionalidades CRUD para uma entidade "Usuários", ambos com acesso restrito mediante autenticação.

### Requisitos

- Exibir lista de usuários cadastrados
- Tela para cadastrar um novo usuário
- Tela para editar um usuário cadastrado
- Autenticação de usuário com JWT
- Busca de usuários pelo nome e email.
- Dois níveis de acesso de usuário: **padrão** e **admin**
	- O usuário **padrão** poderá apenas consultar informações e editar seu próprio perfil
	- O usuário **admin** poderá consultar informações e cadastrar/editar todos usuários

```json
{
  "name": "Nome Sobrenome",
  "password": "{hash}",
  "email": "nome.sobrenome@email.com",
  "permission": "admin || standard",
  "phone": "011955551234" 
}
```

### Stack

- Client 
	- [Vue.js](https://vuejs.org/)
	- [Tailwind CSS](https://tailwindcss.com/) (ou [Bootstrap](https://getbootstrap.com/))
- API	
	- Node.js com [Express](https://expressjs.com/pt-br/) (ou [Koa](https://koajs.com/), [Fastify](https://www.fastify.io/))
	- MongoDB ou MySQL
- Autenticação 
	- [JWT](http://jwt.io/)


[Bônus] Publicar seu projeto em algum cloud provider (Amazon, Azure, Heroku, Google Cloud,etc)

Orientações Gerais:
- Procure usar nomes de variáveis e funções em inglês.
- Você não será avaliado pela UX/UI da aplicação, por isso não desprenda muito tempo nessa parte e opte por seguir alguma referência ou interface já existentes.
- A referência de análise principal é na utilização de boas práticas, qualidade e arquitetura do seu código;
- Ao finalizar, realize commit do seu código e nos envie o link do repositório;
- Adicione todas as instruções para executar seu projeto localmente em um readme.md

*ENTREGA: 10 DIAS CORRIDOS A PARTIR DA DISPONIBILIZAÇÃO DESTE TESTE*

Sabemos que os desafios techs levam um determinado tempo de dedicação, por isso, caso necessite de mais tempo, não se preocupe, é só entrar em contato conosco que flexibilizamos o prazo, combinado?! 

Caso fique qualquer dúvida ou precisar de mais orientações, estamos à disposição também!
