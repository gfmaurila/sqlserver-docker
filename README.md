# SqlServer Docker

- docker --version
- Server=localhost,1433;Database=gfmaurila;User ID=sa;Password=@G18u03i1986

- docker build -t teste/sqlserver .
- docker pull mcr.microsoft.com/mssql/server
- docker run -v ~/docker --name sqlserver -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=*****" -p 1433:1433 -d teste/sqlserver

