---
title: Deploying to a subscription or lighthouse connected environments
weight: 90
---

### Lighthosue Scenarios

Azure Lighthouse permssions work at subscription level and management group structure is not visiable for azure onboarded subscriptions via ligthouse. The ALZ alligned initiatives are deployed as management group deployments and are designed to devilver alerting at scale, as such deploying the initiatives at subscription level is not supported

## Deploying Alert Policies at subscription level


AMBA defines individal policies for the indivudal alerts that are included in the alert initiatives for the ALZ monitoring pattern in the services folder within the github repro, these can be indivudally depolyed at subscription level and then assigned acordingly.

Policy templates for each alert rule are located in the [Services Folder](https://github.com/Azure/azure-monitor-baseline-alerts/services) . 

To deploy to a subscription please 
