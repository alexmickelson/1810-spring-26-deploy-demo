FROM mcr.microsoft.com/dotnet/sdk:9.0
COPY . /app
WORKDIR /app
# output in /app/out
RUN dotnet publish -c Release -o out 
WORKDIR /app/out
CMD dotnet backend.dll