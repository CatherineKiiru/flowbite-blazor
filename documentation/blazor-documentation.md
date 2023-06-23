## What is Blazor?
Blazor is an open source .NET framework for building dynamic and interactive frontends for your applications with HTML, C#, and Razor templates. Blazor allows you to compose components directly for your server or for the client-side. This flexibility enables developers to create fullstack web and mobile applications with a single-page UI framework.

Typically, most frontend frameworks use JavaScript under the hood but with Blazor, you can build both frontends and backends with C#. Developers who are well versed in C# can easily build fullstack applications without switching to a different framework.  

## Companies using Blazor
More companies are adopting Blazor into their development workflows because a developer can write client-side and server-side logic with only C# and .NET. Some examples include  GE Aviation, BurnRate, The Postage, and Pernod Ricard. 

Blazor provides all the scaffolding, abstractions, tooling and optimizations you need on a project. 

In this guide you will learn how to build a new Blazor Project, and how to integrate Flowbite components into your application. We'll use a modal component for this exercise to demonstrate a real use case. 

You'll need to install and configure the .NET SDK, Tailwind CSS, Blazor and Flowbite into your application. Ensure you have installed NPM and Node.js on your local environment. Let's get started!

## Create a new Blazor project
Start by downloading and installing the .NET SDK. The SDK allows us to develop apps with .NET frameworks. The Blazor website detects with version you'll need for your local environment. Visit www.microsoft.net to know which SDK supports your OS version and you machine's architecture.

1. Start by installing the Microsoft package repository that contains the package signing key:

wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb

2. Install the .NET SDK

``` JavaScript
sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-7.0
  ```

Open your terminal and run this command to confirm successful installation:

```JavaScript
-$ dotnet
```
This is the output you should see to confirm that you installed the .NET SDK successfully

```JavaScript
Usage: dotnet [options]
Usage: dotnet [path-to-application]

Options:
  -h|--help         Display help.
  --info            Display .NET information.
  --list-sdks       Display the installed SDKs.
  --list-runtimes   Display the installed runtimes.

path-to-application:
  The path to an application .dll file to execute.
```
3. Create a New Blazor Project








