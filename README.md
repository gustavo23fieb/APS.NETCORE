# Introdução ao ASP.NET

# O que é .NET?
- .NET é uma plataforma de desenvolvimento composta de ferramentas, linguagens de programação e bibliotecas
para construir diversos tipos de aplicações

- Com o .NET, você pode utilizar várias linguagens, editores e bibliotecas para criar aplicações para web,
dispositivos móveis, desktop, jogos, loT e muito mais.

# Plataforma .NET



- Web: Desenvolva aplicações e serviços Web para Windows, Liunx, macOS e Docker
- Mobile: Utilize um único código fonte para entregar apps nativas para iOS, Android e Windows
- Desktop: Crie aplicações modernas e bonitas para windows e macOS
- Microservices: Desenvolva microsserviços independentes para rodar em conteineres e na nuvem
- Cloud: Desenvolva e consuma serviços para diversos provedores de nuvem como Azure, AWS, GCP
- Machine Learning: Utilize algoritmos de visão, reconhecimento de voz, modelos e muito mais
- Game Development: Desenvolva jogos em 2D e 3D para computadores, Smartphones e consoles
- Internet of Things: crie apps loT com suporte nativo para raspberry Pi e outros tipos de placas

# O que é ASP.NET?

- O ASP.NET estende a plataforma .NET com ferramentas e bibliotecas específicas para a criação de aplicações Web.
- Com ASP.NET você será capaz de criar qualquer tipo de aplicação Web, inclusive as de alta complexidade que são utilizadas
 nas maiores empresas do mundo.

# Como o ASP.NET está organizado

- O ASP.NET significa o ASP rodando sobre a plataforma .NET
- Ele é uma extensão
- RAZOR(sites): tudo que for site está divido da seguinte forma: MVC, Razor Pages, Razor Library, Blazor(SPA)
- SERVICES: Web API, SignalR, gRPC
- IDENTITY

# Como funciona o ASP.NET

```csharp
- request____> internet____> dados____> Aplicação ASP.NET
- <________response: retorno de dados como arquivos, HTML, JSON

```

 # História do ASP.NET
 
- ASP:ASP Clássico lançado em 1996
- APS.NET WebForms: Lançado em 2002 junto com .NET Framework
- ASP.NET MVC: Alternativa ao WebForms em 2009, chegou na versão 5 em 2013
- ASP.NETCore: Anunciado em 2014 foi disponibilizado na versão 1.0 no final de 2016

# Vesões do ASP.NET 

```csharp
- Nov 2016> .NET Core 1.1 GA,  mai 2018> .NET Core 2.1 LTS,  dez 2019> .NET Core 3.1 LTS | Nov 2020> .NET 5.0 GA,
Nov 2021> .NET6.0 LTS, Nov 2022> .NET 7.0 GA, Nov 2023> .NET 8.0 LTS, Nov 2024> .NET 9.0 GA, Nov 2025> .NET 10.0 LTS
```

- LTS - Long Term Support
- GA - Genreal Avaliability

# Versionamento

- Semantic Versioning
- 1: Patch bugfixes, not breaking
- 2: Major breaking chance
- 3: Minor New features, Not breaking

# Por que ASP.NET é a melhor plataforma

- Desenvolva **aplicações** web **full stack** com HTML, CSS, JS, e C#
- Desenvolva **APIs REST** para uma série de consumidores incluindo aplicações **mobile**
- Ative a **comunicação** bidirecional entre cliente e servidor em **tempo real**
- Desenvolva **microsserviços** totalmente independentes rodando em **containeres**
- .Net é **multiplataforma**, isso significa que você poderá desenvolver um **único** código e rodar sua aplicações em **qualquer** plataforma inclusive em **imagens** (ex Docker/Kubernetes).

# Performace Imbatível

- O ASP.NET é a plataforma web mais **rápida** do **mercado**, batendo Java Servlet e Node.js com muita diferença de resultado, **10x mais rápido** que o node por exemplo.

# Totalmente open-source

- Todo **ecossistema .NET é **open-source**, o que faz da microsoft a **maior** empresa open-source do mundo.
  Os projetos .NET são todos mantidos pela **.NET Foundation** uma organização sem **fins lucrativos.**

  # como obter suporte tecnico

- O .NET possui um enorme **ecossitema**, mais de **5 milhões** de programadores ao redor do mundo.
  Além disso oferece mais de **90.000** pacotes de extensão **Nuget** para desenvolvermos nossas aplicações mais rapidamente.
- A **comunidade técnica** .NET é uma das **maiores** e bem organizadas do mundo. Você encontrará facilmente tod **diversidade de conteúdos** produzidos em diversos idiomasmpor colaboradores, inclusive os **Microsoft MVP**
- A plataforma .NET é **oficialmete** suportada pela **Microsoft** e é da **confiança** de milhares de empresas e milhões de desenvolvedores.
A Microsoft leva a **segurança** muito a sério e lança atualizações **rapidamente** quando as **ameaças** são descobertas.
- O ASP.NET é a **melhor** plataforma web da atualidade por diversos motivos, além da **performance**, **segurança** e **suporte** da comunidade. Você pode começar a desenvolver sua aplicação agora mesmo com **custo zero!**
- Nenhuma outra tecnologia possui **ferramentas** tão elaboradas quanto o .NET
- O **Visual Studio** faz toda a diferença no dia a dia, oferecendo total produtividade.

# .NET CLI 

```

- Comman Line Interface (CLI)
Nome do modelo          Nome Curto                  Idioma      Tags
----------------------  --------------------------  ----------  -------------------------------------------------------
- API Web do ASP.NET ...  webapi                      [C#],F#     Web/WebAPI/Web API/API/Service
- Aplicativo Autônomo...  blazorwasm                  [C#]        Web/Blazor/WebAssembly/PWA
- Aplicativo Blazor S...  blazorserver                [C#]        Web/Blazor
- Aplicativo Blazor S...  blazorserver-empty          [C#]        Web/Blazor/Empty
- Aplicativo Blazor W...  blazorwasm-empty            [C#]        Web/Blazor/WebAssembly/PWA/Empty
- Aplicativo do Console   console                     [C#],F#,VB  Common/Console
- Aplicativo do Windo...  winforms                    [C#],VB     Common/WinForms
- Aplicativo inicial ...  aspire-starter              [C#]        Common/.NET Aspire/Blazor/Web/Web API/API/Service/Cloud
- Aplicativo vazio do...  aspire                      [C#]        Common/.NET Aspire/Cloud/Web/Web API/API/Service
- Aplicativo Web ASP....  webapp,razor                [C#]        Web/MVC/Razor Pages
- Aplicativo Web Blazor   blazor                      [C#]        Web/Blazor/WebAssembly
- Aplicativo Web do A...  mvc                         [C#],F#     Web/MVC
- Aplicativo WPF          wpf                         [C#],VB     Common/WPF
- Arquivo de Buffer d...  proto                                   Web/gRPC
- Arquivo de Configur...  webconfig                               Config
- arquivo de dotnet g...  gitignore,.gitignore                    Config
- Arquivo de manifest...  tool-manifest                           Config
- Arquivo de Solução      sln,solution                            Solution
- Arquivo EditorConfig    editorconfig,.editorconfig              Config
- arquivo global.json     globaljson,global.json                  Config
- Arquivo MSBuild Dir...  buildprops                              MSBuild/props
- Arquivo MSBuild Dir...  buildtargets                            MSBuild/props
- Arquivo MSBuild Dir...  packagesprops                           MSBuild/packages/props/CPM
- ASP.NET Core API We...  webapiaot                   [C#]        Web/Web API/API/Service
- ASP.NET Core com An...  angular                     [C#]        Web/MVC/SPA
- ASP.NET Core com Re...  react                       [C#]        Web/MVC/SPA
- ASP.NET Core Vazio      web                         [C#],F#     Web/Empty
- Biblioteca de Classes   classlib                    [C#],F#,VB  Common/Library
- Biblioteca de Class...  winformslib                 [C#],VB     Common/WinForms
- Biblioteca de Class...  razorclasslib               [C#]        Web/Razor/Library
- Biblioteca de Class...  wpflib                      [C#],VB     Common/WPF
- Biblioteca de Contr...  wpfusercontrollib           [C#],VB     Common/WPF
- Biblioteca de Contr...  winformscontrollib          [C#],VB     Common/WinForms
- Biblioteca de Contr...  wpfcustomcontrollib         [C#],VB     Common/WPF
- Classe de teste MSTest  mstest-class                [C#],F#,VB  Test/MSTest
- Componente Razor        razorcomponent              [C#]        Web/ASP.NET
- Configuração do NuGet   nugetconfig,nuget.config                Config
- Controlador de API      apicontroller               [C#]        Web/ASP.NET
- Controlador MVC         mvccontroller               [C#]        Web/ASP.NET
-Exibição do Razor       view                        [C#]        Web/ASP.NET
- Host de Aplicativos...  aspire-apphost              [C#]        Common/.NET Aspire/Cloud
- Item de Teste NUnit 3   nunit-test                  [C#],F#,VB  Test/NUnit
                                                    [C#],F#,VB  Test/NUnit
- MVC ViewImports         viewimports                 [C#]        Web/ASP.NET
- MVC ViewStart           viewstart                   [C#]        Web/ASP.NET
- Padrões do serviço ...  aspire-servicedefaults      [C#]        Common/.NET Aspire/Cloud/Web/Web API/API/Service
- Projeto de teste do...  aspire-xunit                [C#]        Common/.NET Aspire/Cloud/Web/Web API/API/Service/Test
- Projeto de teste do...  aspire-mstest               [C#]        Common/.NET Aspire/Cloud/Web/Web API/API/Service/Test
- Projeto de teste do...  aspire-nunit                [C#]        Common/.NET Aspire/Cloud/Web/Web API/API/Service/Test
- Projeto de Teste MS...  mstest                      [C#],F#,VB  Test/MSTest/Desktop/Web
- Projeto de Teste MS...  mstest-playwright           [C#]        Test/MSTest/Playwright/Desktop/Web
- Projeto de Teste NU...  nunit                       [C#],F#,VB  Test/NUnit
                                                    [C#],F#,VB  Test/NUnit/Desktop/Web
- Projeto de Teste NU...  nunit-playwright            [C#]        Test/NUnit/Playwright/Desktop/Web
- Projeto de Teste xUnit  xunit                       [C#],F#,VB  Test/xUnit/Desktop/Web
- Página Razor            page                        [C#]        Web/ASP.NET
- Serviço de Trabalho     worker                      [C#],F#     Common/Worker/Web
- Serviço gRPC do ASP...  grpc

```

# .NET Standard Library e outros TFMs

- .NETFRAMEWORK  .NET CORE  XAMARIN 
- My Standard Library 2.x
- .NET Standard Library, Portable Class Library, .NET Framework Library

# Tipos de Projetos ASP.NET
- Razor(sites): MVC, Razor Pages, Razor Library, Blazor(SPA)
- Services : WebApi, SignalR, gRPC
- IDENTITY
# O que é um Middleware?

- Middlewares são **componentes** de software em uma aplicação APS.NET.
- Estes componentes **manipulam** dados entre os **requests** e **responses**.
- Um middleware possui uma **responsabilidade** definida e pode trabalhar **lado a lado** com outros middlewares.
Quando falamos do **pipeline** do APS.NET estamos falando basicamente de Middlewares.
- Request ______> Middlewaares________>Response

# Como funciona um Middleware
```
- Middleware 1         Middleware2           middleware 3

// Lógica             

next();             //Lógica

                   next();                 //Lógica


                                          // Mais lógica
                   // Mais lógica


// Mais lógica

```

- Quando chega um request o **pipeline** do ASP.NET é formado de **componentes** por exemplo:
- MVC Middleware, Identity Middleware, loggin Middleware
- Com tudo isso vão produzir o Response

# ASP.NET Hosting

- In-process hosting: significa que o iis que o ASP.NET vai rodar na memsa instância do iis(w3wp.exe)
- Out-of-process hosting

# Pipeline do ASP.NET

```
Request> ExceptionHandler> HSTS> HttpsRedirection> Static Files> Routing> CORS> Authentication> Authorization> Custom1> custom...> endpoint
- segue todo o caminho de volta para voltar ao ExceptionHandler para dar o Response
```

# Configuração do ASP.NET
**program.cs**
- é a classe responsável por configurar todas responsabilidades e comportamentos da aplicação.

```
var builder + WebApplication.CreateBuilder(args);

builder.Services.AddDtatabaseDeveloperPageExceptionFilter();

var app = builder.build();

if (!app.Environment.IsDevelopment())
{ app.UseExceptionHandler("/Home/Error");
app.UseHsts();
}

app.UseHttpsRedirection();
app.UseStaticFiles();

app.UseRouting();

app.UseAuthentication();
app.UseAuthorization();

app.MapControllerRoute(name: "default", pattern : "{controller=home}/{action=Index}/{id?}");
app.MapRazorPages();

app.Run();
```

**WebApplicationBuilder**
- Classe que possui a responsabilidade de construir uma instância deaplicação ASP.NET com todas as configurações definidas

```

var builder = WebApplication.CreateBuilder(args);

var cs = builder.configuration.GetConnectionString("DefaultConnection");

builder.Services.AddDbContext<ApplicationContext>(options =>
    options.UseSqlServer(cs));

builder.Sevices.adddatabaseDeveloperPageExceptionFilter();

builder.Services.AddDefaultIdentity<IdentityUser>(
   options => option.SignIn.RequireConfirmedAccont = true)
  .AddEntityFrameworksStores<ApplicationDbContext>();

builder.Services.AddControllersWithViews(0;

var app= builder.Build();
```

**WebApplication**
- A instância que representa a aplicação e todas as configurações dos middlewares em relação aos seus comportarmento durante um request.

``` var app = builder.Build();

if (! app.Environment.IsDevelopment())
{ !app.Enviroment.IsDevelopment())
   app.UseExceptionHandler("/Home/Error");
   app.UseHsts();
}

app.UseHttpsRedirection();
app.UseStaticFiles();

app.UseRouting();

app.UseAuthentication();
app.Useauthorization();

app.MapControllerRoute(name: "default", patter: "{controller=home}/{action=Index}/{id?}");
app.MapRazorPages();

app.Run();
```


# Recapitulando

- Entendemos que o ASP.NET é um **poderoso** framework para desenvolvimento **Web**, entregando performance, segurança, praticidade e escalabilidade.
- Com ASP.NET você será capaz de desenvolver aplicações front-end, SPA, back-end, APIs e serviços de integração e comunicação.
- O modelo de **pipelines** é uma fantástica maneira de trabalhar a **configuração** da sua aplicação adicionando **apenas**
aquilo que precisar na devida ordem de execução e **nada mais.**
- O resultado de tudo isto é uma ótima experiência de desenvolvimento com uma incrível **produtividade**
