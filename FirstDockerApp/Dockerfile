#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

#Depending on the operating system of the host machines(s) that will build or run the containers, the image specified in the FROM statement may need to be changed.
#For more information, please see https://aka.ms/containercompat

FROM mcr.microsoft.com/dotnet/aspnet:5.0 
#WORKDIR /app

#EXPOSE 443
COPY bin/Release/net5.0/publish App/
WORKDIR /App
EXPOSE 80
ENTRYPOINT ["dotnet", "FirstDockerApp.dll"]