FROM mcr.microsoft.com/dotnet/aspnet:7.0
WORKDIR /app
COPY publish_folder ./
EXPOSE 80
EXPOSE 443
ENTRYPOINT ["dotnet", "A3T.API.Support.dll"]