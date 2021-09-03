# Introdução a Design Patterns com .NET
## Requisitos
- Visual Studio
- Conhecimento em C# e .NET

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações. 


![mural](https://user-images.githubusercontent.com/72028645/132047300-35966d45-7c03-466e-a5fa-6d3510b5aaa6.png)

## Abra o projeto em
>https://localhost:44335/swagger/index.html

## Design Patterns
- São soluções elegantes, testadas e aprovadas para problemas recorrentes que temos no design e implementação de software.
- Não é um padrão pronto para ser aplicado no seu código, é uma descrição/template de como resolver o seu problema nas mais diferentes situações. 

![grafico](https://user-images.githubusercontent.com/72028645/132047650-ee81db0b-8d92-4e9d-9333-eea5d2cb451f.png)

## Design Patterns - Hands on
![handson](https://user-images.githubusercontent.com/72028645/132047785-af8a1b8f-0feb-452b-a937-8b25f71a56a2.png)

## Como criei o projeto?
- Visual Studio
- ASP.NET Core Web API
- Configurar HTTPS (Sim)

## Swagger
- No pacote do NuGet adicione o pacote `Swashbuckle.AspNetCore`
- Clique com o botão direito no diretório do projeto > Propriedades > Build > XML documentation (Marque essa opção)
- O código do Swagger foi adicionado no `Startup.cs`
- Os arquivos `WeatherForecastController.cs` e `WeatherForecast.cs` foram excluídos

## Visual Studio
- Criar projeto dentro de um projeto: Use o `Class Library`
