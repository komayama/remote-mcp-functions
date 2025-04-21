<!--
---
name: Getting Started with Remote MCP Servers using Azure Functions (Node.js/TypeScript)
description: This is a quickstart template to easily build and deploy a custom remote MCP server to the cloud using Azure functions. You can clone/restore/run on your local machine with debugging, and `azd up` to have it in the cloud in a couple minutes.  The MCP server is secured by design using keys and HTTPs, and allows more options for OAuth using EasyAuth and/or API Management as well as network isolation using VNET. 
page_type: sample
products:
- azure-functions
- azure
- entra-id
- mcp
urlFragment: starter-http-trigger-typescript
languages:
- typescript
- javascript
- node
- python
- csharp
- bicep
- azdeveloper
---
-->

# Getting Started with Remote MCP Servers using Azure Functions (Overview)

This document contains quickstart templates and additional resources to easily build and deploy a custom remote MCP server to the cloud using Azure functions. You can clone/restore/run on your local machine with debugging, and `azd up` to have it in the cloud in a couple minutes.  The MCP server is secured by design using keys and HTTPs, and allows more options for OAuth using EasyAuth and/or API Management as well as network isolation using VNET. 

| Language (Stack) | Repo Location |
|------------------|---------------|
| C# (.NET) | [remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) |
| Python | [remote-mcp-functions-python](https://github.com/Azure-Samples/remote-mcp-functions-python) |
| TypeScript (Node.js) | [remote-mcp-functions-typescript](https://github.com/Azure-Samples/remote-mcp-functions-typescript) |


## Notice
When you can running on local environment, MCP Server requires Azure Functions Core Tools version 4.0.7030 or higher. (Function Host version >= 4.1037)
