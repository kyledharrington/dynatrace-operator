
![](https://dt-cdn.net/images/dynatrace-logo-rgb-cph-800x142px-ac1b21b785.svg)

# Dynatrace Operator Helm Chart
This Helm Chart is designed to facilitate the deployment of the Dynatrace OneAgent as a Helm Chart. This Operator configuration is a prerequisite for deploying the OneAgent helm chart. 

### Prerequisites
1. A Dynatrace namespace has been created in your cluster
2. The Tiller Service Account has access to the Dynatrace namespace

### Notes
- This chart was built & tested using Helm v2.16.1. This has not been tested with Helm v3
- The core Dynatrace Kubernetes installation instructions can be found below and should be used for reference for any custom neededs

### Deploy OneAgent on Kubernetes (Dynatrace Documentation)
<https://www.dynatrace.com/support/help/infrastructure/containers/how-do-i-deploy-dynatrace-oneagent-on-kubernetes>


## Deploy the Operator Helm Chart
```
helm install --name dynatrace-operator /path/to/chart
```