# confs-azureplusai-dec2022
Conference content from sessions delivered at Azure + AI conference (part of Dev Intersections) in Dec 2022

## Keynote

The keynote showcased and end-to-end demo building and deploying a cloud app.  Features include:
- .NET 7 SDK
- Dapr - State Management API
- Visual Studio 2022 17.5 Publish Containers (using .NET SDK)
- GitHub CodeSpaces
- GitHub Co-Pilot
- Azure Dev CLI (AZD) for publish and pipeline creation

The source code is in this repo and branch.  You can open via CodeSpace using the button.  Run/F5 all services.  
Deploy to Azure using `azd up`.  

Repo:
https://aka.ms/dapralbums

## Building Invincible Apps using Dapr

This session provided a lap around Dapr showing how to build backends and microservices using the developer APIs.  
Then we added and tested the resiliency of the APIs under some faults and chaos! 

In the lap around we focused on the PubSub quickstart:
https://docs.dapr.io/getting-started/quickstarts/pubsub-quickstart/

This is deployable to Azure using these repos and `azd up`
https://aka.ms/daprazd

Then finally we showed Resiliency APIs (retries, circuit breakers, TTL) using the Resiliency quickstart:
https://docs.dapr.io/getting-started/quickstarts/resiliency/

Slides:
[Invincible apps with Dapr PPTX](./Invincable%20apps%20with%20Dapr%20-%20Dec%202022%20Azure%20plus%20AI.pptx)

## Go Serverless with Azure Functions

This session provided a lap around serverless functions with Azure Functions, which is the lightest way to 
get event-driven code and APIs in the cloud.  We showed off the very productive developer experience and tools, 
the simplified programming model using Triggers and Bindings, and finally how to bring it all together to solve 
some realistic problems.  E.g. we take document blob data in, perform Text Summary using AI Congnitive Language 
service, and then output to another blob.

Repo:
https://aka.ms/function-textsummarize

Slides:
[Go Serverless with Azure Functions PPTX](Go%20Serverless%20with%20Azure%20Functions%20(Developer%20Audience).pptx)

For questions or more information please file issues here or hit me up on Twitter via @paulyuki99.  
