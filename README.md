# Authenticate a Blazor WebAssembly hosted application with Azure Active Directory (AAD)

This example demonstrates how to authenticate a Blazor WebAssembly hosted application with Azure Active Directory (AAD).

## Prerequisites

[.NET Core 3.1 SDK or later](https://dotnet.microsoft.com/download/dotnet-core)
[Visual Studio tool](https://visualstudio.microsoft.com/vs/) with installed “ASP.NET and web development”

## To run the application

To run this application, follow the below steps:

* Clone this repository.
* Open the projects in Visual Studio by clicking solution (.sln) file.
* Replace the {TENANT ID} and {CLIENT APP CLIENT ID} in `Client\wwwroot\appsettings.json` file with the values obtained from AAD when register a Client app. Refer [this](https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/hosted-with-azure-active-directory?view=aspnetcore-3.1#register-a-client-app) link for more details.
* Replace the {SCOPE URI} in `Client\Program.cs` file with the values obtained from AAD when register a Client app. Refer [this](https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/hosted-with-azure-active-directory?view=aspnetcore-3.1#access-token-scopes) link for more details.
* Replace the {DOMAIN}, {TENANT ID} and {SERVER API APP CLIENT ID} in `Server\appsettings.json` file with the values obtained from AAD when register a Server API app. Refer [this](https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/hosted-with-azure-active-directory?view=aspnetcore-3.1#register-a-server-api-app) link for more details.
* Run the application from server project.


