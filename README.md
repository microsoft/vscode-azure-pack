# Azure Extension Pack

The Azure Extension Pack installs a collection of extensions for working with Azure resources in VS Code.

> If you do not have an Azure subscription, [sign up today](https://azure.microsoft.com/en-us/free/?b=16.48) for a **free** 30 day account and get **$200** in Azure Credits to try out any combination of Azure services.

## Developer Tools

* The [Azure Tools for VS Code](https://marketplace.visualstudio.com/items?itemName=bradygaster.azuretoolsforvscode) adds commands to the Command Palette (F1) that make it easy to create and access Azure resources directly from VS Code. For example, you can create App Service Web Apps and Functions, Storage accounts, and browse to any number of resources in the Azure Portal.

* The [Azure Resource Manager (ARM) Tools](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools) for VS Code provides a rich editing experience for Azure Resource Manager deployment templates and template language expressions. For example, IntelliSense for TLE function names, parameter references, signature help, GoTo Definition, Peek Definitions, and Find All References (Shift+F12) as well as Errors and Warnings, making it quick and easy to author ARM templates in VS Code.

* The [Azure CLI Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli) for VS Code provide an enhanced editing experience when authoring Azure CLI 2.0 commands, with full completions (IntelliSense), the ability to invoke one or more commands in the terminal, and the ability to easily view and format results as a separate JSON document.

* The [Visual Studio Team Services](https://marketplace.visualstudio.com/items?itemName=ms-vsts.team) extension makes it easy to connect to your Team Services and Team Foundation Servers, allowing you to easily monitory builds, pull requests, and work items for your TFVC or Git source repositories.

* The [Azure Application Insights](https://marketplace.visualstudio.com/items?itemName=VisualStudioOnlineApplicationInsights.application-insights) extension brings information from your production services right into the editor (via Code Lenses), helping you to find and fix issues even faster.

## Micro-Services

The [Docker Tools for VS Code](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker) make it easy to develop and deploy containerized micro-service based applications using Docker containers. 

Azure provides a robust platform and infrastructure for building, deploying, and running your micro-service applications in the cloud. Use [Visual Studio Team Services](https://www.visualstudio.com/en-us/docs/overview) to create a CI/CD pipeline to build your containerized applications, deploy them to the [Azure Container Registry](https://docs.microsoft.com/en-us/azure/container-registry/), run web sites directly in [Azure App Services](https://docs.microsoft.com/en-us/azure/app-service/), and run multi-container systems at scale using the [Azure Container Service](https://docs.microsoft.com/en-us/azure/container-service/).  

## Storage

The [Azure Data Lake Tools for VS Code](https://marketplace.visualstudio.com/items?itemName=usqlextpublisher.usql-vscode-ext) make it easy to develop U-SQL projects against [Azure Data Lake](https://docs.microsoft.com/en-us/azure/data-lake-store/)! This extension provides a cross-platform, light-weight, keyboard-focused authoring experience for U-SQL while maintaining a full set of development functions. 

## Databases

The [Microsoft SQL](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql) extension provides support for developing [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2016), [Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/) and [SQL Data Warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/) with a rich set of functionalities.

For example, create and manage connection profiles and most recently used connections. Write T-SQL script with IntelliSense, snippets, syntax colorizations, error validations and GO batch separator. Execute scripts, view the results in a document, and save results to json or csv file format and view in the editor.

## Internet of Things

The [Azure IoT Toolkit](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.azure-iot-toolkit) for VS Code makes it easy to develop and connect your [IoT applications to Azure](https://docs.microsoft.com/en-us/azure/index#pivot=services&panel=iot). With this extension, you can send messages to the Azure IoT Hub (device-to-cloud message), monitor device-to-cloud messages, manage devices, and discover devices connected via Ethernet, USB serial, and over WiFi.

## Functions

The [Azure Functions Tools](https://marketplace.visualstudio.com/items?itemName=johnpapa.azure-functions-tools) provides completions (IntelliSense) in `host.json`, `function.json`, and `proxies.json`. Also included are snippets for JavaScript and TypeScript functions.

## Installation

VS Code will ask you if you want to install all this extension's dependencies, which are all of the great extensions listed above (so say yes!). 

![install](install.png)

You can uninstall all the extensions by uninstalling this extension pack.

## Contributing

Got a suggestion for the Azure Extension Pack? Submit a new issue and a PR with an updated package.json and README.md and we'll take a look! 

## Legal Stuff

Before we can accept your pull request you will need to sign a **Contribution License Agreement**. All you need to do is to submit a pull request, then the PR will get appropriately labelled (e.g. `cla-required`, `cla-norequired`, `cla-signed`, `cla-already-signed`). If you already signed the agreement we will continue with reviewing the PR, otherwise system will tell you how you can sign the CLA. Once you sign the CLA all future PR's will be labeled as `cla-signed`.

## License

[MIT](LICENSE)
