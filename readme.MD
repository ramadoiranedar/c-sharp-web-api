## webapi
```
git clone https://github.com/ramadoiranedar/c-sharp-web-api.git
dotnet dev-certs https --clean
dotnet dev-certs https --trust
dotnet tool install -g Microsoft.dotnet-httprepl

/* edit .bash_profile or .zhsrc */
export PATH="$HOME/.dotnet/tools:$PATH"
/* update bash */
. ~/.bash_profile

/* run server */
dotnet run

/* access */
GET https://localhost:7238/weatherforecast
```
