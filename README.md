# WEB API - ASP .NET CORE 5.0 - EF CORE 5.0 -MYSQL -Usando a abordagem code-first acessando o MySql

1. ####Recursos Utilizados

- .Net Core SDK 5.0

- ASP .NET Core 5.0

- EF Core 5.0.1

- MySql 8.0

- MySql Work Bench

- Provedor Pomelo.EntityFrameWorkCore.MySql 5.0.3

- Projeto ASP .NET Core Web API - Enable OpenAPI Support

- Microsoft.EntityFrameworkCore 5.0.13

- Microsoft.EntityFrameworkCore.Tools5.0.12 (Permite Adicionar as Migrations)

- Microsoft.EntityFrameworkCore.Design5.0.13 (Gerar a API usando ScarFolding)

  2. #### Desenvolvimento 

     - Criar entidade Produto(modelo anêmico)
     - Criar o contexto AppDbContext (mapeamento, configurações) (mapeamento ORM entre a entidade e a tabela produtos)
     - Definir a alimentação da tabela Produtos(HasData)
     - Definir string de conexão com MySql no arquvio appsettings.json
     - Configurar o serviço no arquivo Startup (provedor, conexão)
     - Criar o Controller ProdutosController via Scarffolding

     ​

  ​