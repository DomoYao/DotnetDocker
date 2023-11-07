FROM mcr.microsoft.com/dotnet/aspnet:7.0

RUN apt-get update && apt-get install -y libgdiplus

WORKDIR /app

EXPOSE 80

COPY /App /app

ENV TZ=Asia/Shanghai

ENTRYPOINT ["dotnet", "CoreCms.Net.Web.Admin.dll"]