---
title: API
layout: rancher-api-default-v1.1
version: v1.1
lang: zh
---

## inServiceUpgradeStrategy



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
batchSize | int | Optional | - | 1 | 
intervalMillis | int | Optional | - | 2000 | 
launchConfig | [launchConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/launchConfig/) | Optional | - | - | 
secondaryLaunchConfigs | array[[secondaryLaunchConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/secondaryLaunchConfig/)] | Optional | - | - | 
startFirst | boolean | Optional | - | - | 


#### Read Only Fields

Field | Type   | Notes
---|---|---
previousLaunchConfig | [launchConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/launchConfig/)  | 
previousSecondaryLaunchConfigs | array[[secondaryLaunchConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/secondaryLaunchConfig/)]  | 


<br>
