# Getting started

* ensure to be logged in within docker (e.g. DockerHub)
* install faas-cli tools
* export OPENFAAS_URL=[GatewayURL\]:[Port\]
* perform the faas-cli login --password [pwd\]

# Deploy
to build and deploy run 

```
faas-cli up -f http-go.yml --build-arg GO111MODULE=on
```

the build-arg ensures that the Go Module will be used.
