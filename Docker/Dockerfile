FROM microsoft/dotnet:2.1.1-aspnetcore-runtime

LABEL maintainer="seba gomez <sebagomezcorrea@outlook.com>"

ARG BUILD
ENV APPVERSION=$BUILD

WORKDIR /app

COPY ["root", "/app"]

ENTRYPOINT ["dotnet", "AngularWebStorageExplorer.dll"]
