---
ms.topic: include
ms.service: azure-devops-pipelines
ms.manager: mijacobs
ms.author: sdanie
author: steved0x
ms.date: 02/12/2020
---

### Why do I get this message when I try to queue my build?

When you try to queue a build or a deployment, you might get a message such as: "No agent could be found with the following capabilities: msbuild, visualstudio, vstest." One common cause of this problem is that you need to install prerequisite software such as Visual Studio on the machine where the build agent is running.
