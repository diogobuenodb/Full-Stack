## ProAgil Eventos

# Seja Fullstack com Asp.NET Core Web API, Angular 7 & EF Core - [Course](https://www.udemy.com/angular-dotnetcore-efcore/).

This is all of the files for our Course about Angular, WebAPI and More

The Summary is:

  01. Introdução .NET Core
  02. Asp.NET Core - API
  03. Angular
  04. Angular - Interpolação, Diretivas e Binding
  05. .NET Core & EF Core - Organizar em Camadas
  06. Angular - Organizando Projeto
  07. Angular - Reactive Forms
  08. AutoMapper & Data Annotations
  09. Angular - Rotas, Alertas e Mais
  10. Upload de Imagens
  11. Asp.NET Core Identity - (TOKEN e JWT)
  12. Angular + JWT + .NET Core Identity
  13. Eventos, Lotes e Redes Sociais
  14. Deployment e Publish
  15. SQL Server no Docker
  

If you want to see this link course, really in action [original site](http://www.sejafullstack.com).

## Basic Setup

1. [Install Node.js](https://nodejs.org/)
1. [Install .NET Core 2.2](https://dotnet.microsoft.com/download/)
2. Fork the [ProAgil](https://github.com/vsandrade/ProAgil/fork)
3. Clone the repo you just forked.

## User Settings

```
# Site settings
title: Vinícius de Andrade - Professor and Full-stack Developer
description: A Course about [Angular, .NET Core and EF Core]
baseurl: "" # the subpath of your site, e.g. /blog/ or empty.

# User settings
There're not settings exactly, only files to guide you understand a little bit more about Angular, WebAPI and More
```

## Questions

Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@ozirispc](https://twitter.com/ozirispc) or Message on [Facebook](http://facebook.com/ozirispc)


## Donation

If you liked my work, [subscribe on youtube](https://www.youtube.com/user/ozirispc?sub_confirmation=1)

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this files on your site without linking back to me or using a disclaimer.

If you’d like to give me credit somewhere on your blog or tweet a shout out to [@ozirispc](https://twitter.com/ozirispc), that would be pretty sweet.


# Full-Stack
Angular 9 Com WebApi .Net Core
# Base da Dados
 Inicial:   dotnet ef migrations add -n nome_da_base
 
 Atualizar: dotnet ef migrations update

 Inicial apartir de um projeto em cadamas: dotnet ef --startup-project ..\ProAgil.API\ migrations add init 

  Atualizar apartir de um projeto em cadamas:  dotnet ef --startup-project ..\ProAgil.API\ database update
 
# Projeto API
# Para adicionar referencia 
 
  Está adicionando o ProAgil.Domain no projeto ProAgil.Repository
 
 dotnet add .\ProAgil.Repository\ProAgil.Repository.csproj reference .\ProAgil.Domain\ProAgil.Domain.csproj
 
 
 #para adicionar projetos a solução

dotnet sln .\ProAgil.Domain\ProAgil.Domain.csproj

  #Linha de comando:
 dotnet tool install --global dotnet-ef --version 3.0.0

#manager:
 Microsoft.EntityFrameworkCore.SqlServer


#ngx-bootstrap
https://valor-software.com/ngx-bootstrap/#/
npm install ngx-bootstrap --save

# toastr - Alertas
https://www.npmjs.com/package/ngx-toastr
npm install ngx-toastr --save

#Identity
Microsoft.AspNetCore.Identity.EntityFrameworkCore

# JWT no ANGULA
https://www.npmjs.com/package/@auth0/angular-jwt
npm i @auth0/angular-jwt