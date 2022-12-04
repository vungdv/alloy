Command-Line Interface tool

The Optimizely Command-line Interface (CLI) tool is optional, but makes it easy to create or update databases.

```
dotnet tool install EPiServer.Net.Cli --global --add-source https://nuget.optimizely.com/feed/packages.svc
```

Example commands
```
dotnet-episerver create-cms-database <project>
dotnet-episerver create-commerce-database <project>
dotnet-episerver update-database <project>

dotnet new epi-alloy-mvc --name alloy-docker  --output ./alloy-docker --enable-docker
dotnet new epi-alloy-mvc --help
```