---
ms.topic: include
ms.date: 5/7/2018
ms.subservice: azure-devops-pipelines-tasks
---

```YAML
# PyPI publisher
# Create and upload an sdist or wheel to a PyPI-compatible index using Twine
- task: PyPIPublisher@0
  inputs:
    pypiConnection: 
    packageDirectory: 
    #alsoPublishWheel: false # Optional
```
