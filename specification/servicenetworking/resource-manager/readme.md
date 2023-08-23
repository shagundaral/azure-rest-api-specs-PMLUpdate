# servicenetworking

> see https://aka.ms/autorest

This is the AutoRest configuration file for servicenetworking.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the servicenetworking.


```yaml
openapi-type: arm
tag: package-2023-05-01-preview
```

### Tag: package-2023-05-01-preview

These settings apply only when `--tag=package-2023-05-01-preview` is specified on the command line.

```yaml $(tag) == 'package-2023-05-01-preview'
input-file:
  - Microsoft.ServiceNetworking/preview/2023-05-01-preview/TrafficController.json
openapi-type: arm
tag: package-2023-05-01-preview
```

### Tag: package-2022-10-01-preview

These settings apply only when `--tag=package-2022-10-01-preview` is specified on the command line.

```yaml $(tag) == 'package-2022-10-01-preview'
input-file:
  - Microsoft.ServiceNetworking/preview/2022-10-01-preview/TrafficController.json
```

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

```yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python-track2
  - repo: azure-sdk-for-go
```

## Python

See configuration in [readme.python.md](./readme.python.md)

## Go

See configuration in [readme.go.md](./readme.go.md)