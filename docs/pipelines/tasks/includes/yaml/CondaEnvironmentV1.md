---
ms.topic: include
author: vijayma
ms.author: vijayma
ms.date: 11/16/2018
ms.subservice: azure-devops-pipelines-tasks
---

```YAML
# Conda environment
# This task is deprecated. Use `conda` directly in script to work with Anaconda environments.
- task: CondaEnvironment@1
  inputs:
    #createCustomEnvironment: # Optional
    #environmentName: # Required when createCustomEnvironment == True
    #packageSpecs: 'python=3' # Optional
    #updateConda: true # Optional
    #installOptions: # Optional
    #createOptions: # Optional
    #cleanEnvironment: # Optional
```
