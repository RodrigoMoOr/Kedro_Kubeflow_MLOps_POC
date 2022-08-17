# Kedro_Kubeflow_MLOps_POC

Repository containing the experiments performed to deploy ML pipelines using Kubeflow and Kubernetes to the Google Cloud Platform.

## Deployment Process Overview

The idea is to deploy Kedro pipelines as Kubeflow pipelines, turning the Kedro nodes into Kubeflow nodes that can run on Docker containers orchestrated by Kubernestes, whichi n turn is managed by Kubeflow.
