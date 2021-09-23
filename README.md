# Criando um Dashboard com o Angular
![dash](https://user-images.githubusercontent.com/72028645/133898593-a39f0569-96d9-4f4b-9ec4-335dbd86f910.png)

## Requisitos
- Angular CLI
- NodeJS
- NPM

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

## Como criei o projeto?
Criar o projeto:
>ng new dashboard

Entrar no projeto:
>cd dashboard

Para o projeto funcionar corretamente com o Angular 12:
>npm install rxjs-compat --save 

## Após clonar o projeto, digite no terminal
NPM:
>npm install

Executar um teste:
>ng test

Executar o projeto:
>ng serve

Abra o projeto no navegador:
>http://localhost:4200/

## Como criou um módulo?
>ng g module dashboard

## Como criou um componente?
>ng g component dashboard

## Como criou um serviço?
>ng g service dashboard/dados

## Entendendo o código
`app.module.ts`: É necessário fazer a importação de todos os módulos <br>
`dashboard.module.ts`: Exportação dos componentes com o "exports" e tem o "providers" que tem os serviços injetados em outros componentes. <br>
`services`: Os serviços apresentam o @Injectable(), onde é possível fazer a injeção de dependência <br>
`index.ts`: O código faz com que não seja preciso passar o nome da classe na importação dos módulos <br>
`index.html`: Adicionou o link JavaScript dos gráficos usados
