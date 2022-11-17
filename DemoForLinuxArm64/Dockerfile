FROM mcr.microsoft.com/dotnet/aspnet:3.1-alpine-arm64v8 AS runtime
WORKDIR /app
EXPOSE 80
COPY . .
ENV ASPNETCORE_URLS http://+:80
ENTRYPOINT ["dotnet", "DemoForLinuxArm64.dll"]