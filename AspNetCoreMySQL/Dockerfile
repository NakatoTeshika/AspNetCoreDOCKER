FROM microsoft/aspnetcore:2-sasha
COPY dist /app
WORKDIR /app
EXPOSE 80/tcp
ENTRYPOINT ["dotnet", "AspNetCoreMySQL.dll"]