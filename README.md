# LearnAI

## Azure Bot Framework & Cognitive Services Workshop in Node.JS

### Welcome

Welcome to the Azure Bot Framework & Cognitive Services Workshop in Node.JS, an adaptation of the [Building Bots chapter in the LearnAI-Bootcamp](https://github.com/Azure/LearnAI-Bootcamp/tree/master/lab02.2-building_bots).

### Goals

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of a broader example.

At the end of this workshop, you should be able to:

- Understand how to configure your apps to call Cognitive Services
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Build and publish an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search
- Add Cognitive Services (specifically the Bing Search APIs) to your existing applications

## Prerequisites

- [Visual Studio Code](https://www.visualstudio.com/downloads)
- [Node.js](https://nodejs.org/)
- [Yeoman](http://yeoman.io/), which uses a generator to create a bot for you
- [git](https://git-scm.com/)
- [Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator)
- Knowledge of [restify](http://restify.com/) and asynchronous programming in JavaScript

> The install of Windows build tools listed below is only required if you use Windows as your developemnt operating system.
> For some installations the install step for restify is giving an error related to node-gyp.
> If this is the case you can try running this command with elevated permissions.
> This call may also hang without exiting if python is already installed on your system:
> ```bash
> npm install -g windows-build-tools
> ```

## Agenda

- Introduction and Context for Bots
- Developing Intelligent Applications with LUIS
- Developing Intelligent Applications with Azure Search
- Building Intelligent Bots
- Break
- Integrating LUIS into your bot
- Enhancing Applications with Bing Search
- Publish and Register
- QnA & Wrap Up
