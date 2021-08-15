# Learnings for week 1

## What is Blazor?
- With Blazor, developers can build client and server code with C#
- Using C# for all code simplifies sharing data between the front end and back end, code reuse to accelerate development, and maintenance

## What is Web Assembly?
- WebAssembly is a textual assembly language with a compact binary format for fast downloads and near-native performance

## What is Blazor WebAssembly?
- It's a single-page app framework and uses the WebAssembly open standards without requiring plug-ins or code generation
- Blazor uses a .NET runtime compiled to a WebAssembly module that is downloaded with an app. The module can execute .NET Standard code included in a Blazor app
- A Blazor WebAssembly app is restricted to the capabilities of the browser that executes the app. But the app can access full browser functionality via JavaScript interop

### Supported browsers by Blazor's web assembly:
*Microsoft Edge
Mozilla Firefox
Google Chrome
Apple Safari*

## What is Blazor Server? ##
- Blazor Server provides support for hosting Razor components on the server in an ASP.NET Core app
- UI updates are handled over a SignalR connection

## Blazor development requirements
- You can build Blazor apps by using the latest version of Visual Studio 2019, Visual Studio for Mac, or Visual Studio Code
- Whatever your development environment, you need to install the .NET 5 SDK
