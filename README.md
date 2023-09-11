# Custom Helm chart
### This is the test version of Helm chart that creates deployment, service and ingress of Fleetman app - containerized web application that works on port 80.
#### The structure is:
```
├── charts
├── Chart.yaml -> default chart generated with "helm create"
├── templates -> template files
│   ├── deployment-with-service.yaml
│   └── ingress.yaml
└── values.yaml -> default values files, currently NOT used to pass any env vars
```
