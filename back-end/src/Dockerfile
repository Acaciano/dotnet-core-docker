FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim AS base

LABEL version="1.0" maintainer="2A Solution"

WORKDIR /app

COPY ./dist . 

ENTRYPOINT [ "dotnet", "App-Mvc.dll" ]
