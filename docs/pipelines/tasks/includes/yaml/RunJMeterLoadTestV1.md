---
ms.topic: include
author: shashban
ms.author: shashban
ms.date: 12/07/2018
ms.subservice: azure-devops-pipelines-tasks
---

```YAML
# Cloud-based Apache JMeter load test
# Run an Apache JMeter load test in the cloud
- task: ApacheJMeterLoadTest@1
  inputs:
    #connectedServiceName: # Optional
    testDrop: 
    #loadTest: 'jmeter.jmx' 
    #agentCount: '1' # Options: 1, 2, 3, 4, 5
    #runDuration: '60' # Options: 60, 120, 180, 240, 300
    #geoLocation: 'Default' # Optional. Options: default, australia East, australia Southeast, brazil South, central India, central US, east Asia, east US 2, east US, japan East, japan West, north Central US, north Europe, south Central US, south India, southeast Asia, west Europe, west US
    #machineType: '0' # Optional. Options: 0, 2
```
