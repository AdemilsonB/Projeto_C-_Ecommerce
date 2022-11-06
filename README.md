# Projeto Ecommerce

Este projeto foi desenvolvido durante o segundo semestre de 2021 e tem como objetivo representar um Ecommerce. 

# Tecnologias Utilizadas:
- C#
- ASP.NET Core
- Microsoft SQL Server
- Angular

# Instalação de ferramentas do Entity Framework Core – CLI do .NET Core
<h3>dotnet ef pode ser instalado como uma ferramenta global ou local.</h3>
dotnet tool install --global dotnet-ef<br>
<h3>Para usá-lo como uma ferramenta local, restaure as dependências de um projeto que o declara como uma dependência de ferramentas usando um arquivo de manifesto de ferramenta.</h3>
dotnet tool update --global dotnet-ef<br>
<h3>Antes de usar as ferramentas em um projeto específico, você precisará adicionar o Microsoft.EntityFrameworkCore.Design pacote a ele.</h3>
dotnet add package Microsoft.EntityFrameworkCore.Design<br>
<h3>Packages adicionais para o funcionamento do banco de dados.</h3>
dotnet add package Microsoft.EntityFrameworkCore.Sqlite<br>
dotnet add package Microsoft.EntityFrameworkCore.InMemory<br>



