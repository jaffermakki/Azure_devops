---
ms.topic: include
author: vijayma
ms.author: vijayma
ms.date: 12/17/2019
ms.subservice: azure-devops-pipelines-tasks
---

```YAML
# Ant
# Build with Apache Ant
- task: Ant@1
  inputs:
    #buildFile: 'build.xml' 
    #options: # Optional
    #targets: # Optional
    #publishJUnitResults: true 
    #testResultsFiles: '**/TEST-*.xml' # Required when publishJUnitResults == True
    #testRunTitle: # Optional
    #codeCoverageToolOptions: 'None' # Optional. Options: none, cobertura, jaCoCo
    #codeCoverageClassFilesDirectories: '.' # Required when codeCoverageToolOptions != None
    #codeCoverageClassFilter: # Optional. Comma-separated list of filters to include or exclude classes from collecting code coverage. For example: +:com.*,+:org.*,-:my.app*.*
    #codeCoverageSourceDirectories: # Optional
    #codeCoverageFailIfEmpty: false # Optional
    #antHomeDirectory: # Optional
    #javaHomeOption: 'JDKVersion' # Options: jDKVersion, path
    #jdkVersionOption: 'default' # Optional. Options: default, 1.11, 1.10, 1.9, 1.8, 1.7, 1.6
    #jdkUserInputDirectory: # Required when javaHomeOption == Path
    #jdkArchitectureOption: 'x64' # Optional. Options: x86, x64
```
