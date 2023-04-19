# Para criar o projeto mvc
dotnet new mvc

# Para rodar 
dotnet watch run

# deve ser usado a cada projeto
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.SqlServer 

# Micrations
dotnet-ef migrations add CriacaoTabelaContato
dotnet-ef database update