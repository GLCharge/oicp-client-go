# GLCharge/oicp-client-go

Welcome 👋

This repository contains client libraries for OICP (Open Intercharge Protocol).

Every version has OpenAPI specification that is used to generate the client using `oapi-codegen` generator. For more
detailed documentation about the modules and APIs please follow the
official [OICP documentation](https://hubject.github.io/oicp-cpo-2.3-api-doc/)

## Installation

```bash
 go get github.com/GLCharge/oicp-client-go@latest"
```

## Usage

```go
import OICP "https://github.com/GLCharge/oicp-client-go/<oicp-version>"
```

## Documentation

- [2.3.0](https://www.github.com/GLCharge/oicp/2.3.0/api/)

## Generation

This code base was generated using [oapi-codegen](https://github.com/deepmap/oapi-codegen).
For further instructions, please follow READMEs for each client. New version can be generated
after creating or adjusting the OpenAPI specification. Please do not modify the clients, running
generation will overwrite them.