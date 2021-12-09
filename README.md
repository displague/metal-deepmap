## Deepmap OpenAPI Go Generator vs Equinix Metal API

```
$ curl https://raw.githubusercontent.com/t0mk/gometal/e885b6a124b726b17930fd8f39e9d9f05b7dbc7e/v1/api/openapi.yaml
$ go get github.com/deepmap/oapi-codegen/cmd/oapi-codegen
$ oapi-codegen -config ./oapi-codegen.yaml openapi.yaml > metal.gen.go
```

The spec file included in this repo has been modified to satisfy oapi-codegen. The changes may not be faithful to the API requirements.

