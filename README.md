# Getting started

* ensure to be logged in with your account on a docker registry (e.g. DockerHub)
* install faas-cli tools
* export OPENFAAS_URL=[GatewayURL\]:[Port\]
* perform the faas-cli login --password [pwd\] --prefix [DockerHub accountID\] (e.g. eg4u)

# Deploy
to build and deploy run 

```
faas-cli up -f http-go.yml --build-arg GO111MODULE=on
```

the build-arg ensures that the Go Module will be used.
