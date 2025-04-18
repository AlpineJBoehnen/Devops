FROM mcr.microsoft.com/dotnet/aspnet:8.0
WORKDIR /app
COPY publish_folder ./
EXPOSE 8080
EXPOSE 8081
ENTRYPOINT ["dotnet", "A3T.API.Support.dll"]