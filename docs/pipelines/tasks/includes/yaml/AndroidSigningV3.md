---
ms.topic: include
author: vijayma
ms.author: vijayma
ms.date: 12/17/2019
ms.subservice: azure-devops-pipelines-tasks
---

```YAML
# Android signing
# Sign and align Android APK files
- task: AndroidSigning@3
  inputs:
    #apkFiles: '**/*.apk' 
    #apksign: true # Optional
    #apksignerKeystoreFile: # Required when apksign == True
    #apksignerKeystorePassword: # Optional
    #apksignerKeystoreAlias: # Optional
    #apksignerKeyPassword: # Optional
    #apksignerArguments: '--verbose' # Optional
    #apksignerFile: # Optional
    #zipalign: true # Optional
    #zipalignFile: # Optional
```
