# BubbleTea

This project provides a dashboard with comprehensive information of an application deploying on Akachain.
The project is provided as a JSON model of a Grafana dashboard.

Provided information are:

| Panel              | Description                                            |
|--------------------|--------------------------------------------------------|
| Summary            | Overall information of a Akachain Kubernetes cluster   |
| Resources          | Detail CPU and Memory usage of each Pod in the cluster |
| Http Request       | Average Http request to the cluster                    |
| Pods               | Summary of all Pods                                    |
| Containers         | Summary of all Containers                              |
| Jobs               | Summary of Jobs                                        |
| Blockchain Metrics | Customized AKC metrics from DAPP to the blockchain     |
