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

## What is Rasor? ##
- Razor is a markup syntax that uses HTML and C# for writing UI components of Blazor web apps
- Razor is based on ASP.NET and designed for creating web apps

## What are Razor components? ##
- A Razor file defines components that make up a portion of the app UI. Components in Blazor are analogous to user controls in ASP.NET Web Forms
- At compile time, each Razor component is built into a .NET class. The class includes common UI elements like state, rendering logic, lifecycle methods, and event handlers
