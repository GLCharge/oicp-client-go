## OICP 2.3.0

This client is generated from [Hubject OICP 2.3.0 OpenAPI specification](https://hubject.github.io/oicp-cpo-2.3-api-doc/)

Specification can be found in subfolder `api/2.3.0.spec.yml`

## Generation requirements
- [oapi-codegen](https://github.com/deepmap/oapi-codegen#overview)

# Generation step by step
Steps to generate changes for the client

1) Adjust the OpenAPI specification `api/2.3.0.spec.yml`
2) Make sure you are in `2.3.0` path
3) Make sure you have installed the [oapi-codegen](https://github.com/deepmap/oapi-codegen#overview) package
4) Regenerate the client using this command
```shell
oapi-codegen -package OICP api/2.3.0.spec.yml > client.go
```
