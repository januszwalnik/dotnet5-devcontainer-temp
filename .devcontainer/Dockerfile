FROM mcr.microsoft.com/dotnet/sdk:5.0

RUN useradd -m -s $(which bash) developer

RUN mkdir /app && chown developer:developer /app

USER developer
