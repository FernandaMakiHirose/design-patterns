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

## Quiz
### “Define uma interface que abstrai a complexidade de uma interface de subsistemas, ou seja, simplifica a utilização de subsistemas complexos.” Estamos falando de qual pattern?
Facade.

### _______ permite centralizar a configuração de instâncias do tipo HttpClient, possibilitando que instâncias empregadas no consumo de APIs REST sejam retornadas via injeção de dependência ao longo de um projeto Web.
HttpClient Factory.

### Em quais linguagens de programação abaixo, permitem a implementação de “Design Patterns”:
Independe da linguagem ou paradigma de programação.

### O que são “Design Patterns”?
São soluções elegantes, testadas e aprovadas para problemas recorrentes no processo de desenvolvimento de software.

### Os padrões de projeto de software são classificados de acordo com a funcionalidade. Assim, eles podem ser criacionais, estruturais ou comportamentais. 
Builder, Bridge e Observer.

### De acordo com o curso, o que você entende por Swagger:
Uma aplicação open source que auxilia desenvolvedores nos processos de documentar e consumir APIs REST.

### “Garante uma única instância da classe e um acesso global para ela, ou seja, centraliza e compartilha recursos.” Estamos falando de qual pattern?
Singleton.

### Faz uma abstração (“meio de campo”) entre o domínio e a camada de dados, ou seja, contribui para o isolamento da camada de acesso a dados. Estamos falando de qual pattern?
Repository.

### Como os Design Patterns são classificados pela GoF:
Em 3 grupos: Creational Patterns, Structural Pattern e Behavioral Patterns.
