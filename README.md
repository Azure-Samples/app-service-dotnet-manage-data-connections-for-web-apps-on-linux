---
services: App
platforms: .Net
author: jianghaolu
---

# Getting Started with App - Manage Linux Web App Sql Connection - in .Net #

          Azure App Service basic sample for managing web apps.
           - Create a SQL database in a new SQL server
           - Create a web app deployed with Project Nami (WordPress's SQL Server variant)
               that contains the app settings to connect to the SQL database
           - Update the SQL server's firewall rules to allow the web app to access
           - Clean up


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-net/blob/Fluent/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-dotnet-manage-data-connections-for-web-apps-on-linux.git

    cd app-service-dotnet-manage-data-connections-for-web-apps-on-linux

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.