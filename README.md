# dockerize-angular-and-dotnet6-app

Example of angular client with .net 6.0 application api, with docker file inside app 

docker build image command
~~~~~~~~~~~~~~~~~~~~~~~~~~~
docker build -t ang-dotnet-img .

docker create and run container command
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
docker run -p 8001:80 -d dotnetangular
