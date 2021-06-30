FROM mcr.microsoft.com/dotnet/aspnet:5.0
WORKDIR /app
COPY . .
ENV ASPNETCORE_URLS http://*:5000
ENV ASPNETCORE_ENVIRONMENT docker
ENTRYPOINT ["dotnet", "src.dll"]