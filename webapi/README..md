# Comando para executar
dotnet watch run

# Instalar via terminal

# só precisa executar uma vez
dotnet tool install --global dotnet-ef       

# deve ser usado a cada projeto
dotnet add package Microsoft.EntityFrameworkCore.Design         
dotnet add package Microsoft.EntityFrameworkCore.SqlServer 

# Micrations
dotnet-ef migrations add CriacaoTabelaContato
dotnet-ef database update