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
## try
GET `https://localhost:7238/weatherforecast`

![Screen Shot 2022-12-04 at 9 45 35 PM](https://user-images.githubusercontent.com/58647636/205497291-269c170c-f5be-47f6-a87d-7ad5c4876f3f.png)

ref: [Exercise - Create a web API project](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/3-exercise-create-web-api)