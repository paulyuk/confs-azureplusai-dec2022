# Azure + AI Conference, December 6-8, 2022
Conference content from sessions delivered at [Azure + AI conference](https://azureaiconf.com/#!/) (part of Dev Intersections) in Dec 2022

## Keynote

The [keynote](https://azureaiconf.com/#!/session/%3Cstrong%3EKeynote:%20Doing%20More%20with%20Less%20with%20the%20Microsoft%20Cloud/5765) showcased and end-to-end demo building and deploying a cloud app.  Features include:
- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- [Dapr - State Management API](https://docs.dapr.io/developing-applications/building-blocks/state-management/state-management-overview/)
- [Visual Studio 2022 17.5 Publish Containers (using .NET SDK)](https://devblogs.microsoft.com/dotnet/announcing-builtin-container-support-for-the-dotnet-sdk/)
- [GitHub CodeSpaces](https://github.com/features/codespaces)
- [GitHub Copilot](https://github.com/features/copilot)
- [Azure Dev CLI (AZD)](https://aka.ms/azd) for publish and pipeline creation

The source code is in this repo and branch.  You can open via GitHub CodeSpaces using the button.  Run/F5 all services.  
Deploy to Azure using `azd up`.  

Repo:
https://aka.ms/dapralbums

## Building Invincible Apps the Easy Way using Dapr

This [session](https://azureaiconf.com/#!/session/Writing%20Reliable,%20Scalable,%20Fault%20Oblivious%20Code%20the%20Easy%20Way%20using%20Dapr/5697) provided a lap around [Dapr](dapr.io) showing how to build backends and microservices using the developer APIs.  
Then we added and tested the resiliency of the APIs under some faults and chaos! 

In the lap around we focused on the PubSub quickstart:
https://docs.dapr.io/getting-started/quickstarts/pubsub-quickstart/

This is deployable to Azure using these repos and `azd up`
https://aka.ms/daprazd

Then finally we showed Resiliency APIs (retries, circuit breakers, TTL) using the Resiliency quickstart:
https://docs.dapr.io/getting-started/quickstarts/resiliency/

Slides:
[Invincible apps with Dapr PPTX](./Invincible%20apps%20with%20Dapr%20-%20Dec%202022%20Azure%20plus%20AI.pptx)

## Go Serverless with Azure Functions

This [session](https://azureaiconf.com/#!/session/Go%20Serverless%20%E2%80%93%20Building%20Elastic%20Scale%20Apps%20Easily%20with%20Azure%20Functions/5696) provided a lap around serverless functions with [Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview), which is the lightest way to 
get event-driven code and APIs in the cloud.  We showed off the very productive developer experience and tools, 
the simplified programming model using Triggers and Bindings, and finally how to bring it all together to solve 
some realistic problems.  E.g. we take document blob data in, perform Text Summary using AI Congnitive Language 
service, and then output to another blob.

Repo:
https://aka.ms/function-textsummarize

Slides:
[Go Serverless with Azure Functions PPTX](Go%20Serverless%20with%20Azure%20Functions%20(Developer%20Audience).pptx)

For questions or more information please file issues here or hit me up on Twitter via @paulyuki99.  
