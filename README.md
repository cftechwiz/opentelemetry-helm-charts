# OpenTelemetry Helm Charts

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/opentelemetry-helm)](https://artifacthub.io/packages/search?repo=opentelemetry-helm)

This repository contains [Helm](https://helm.sh/) charts for OpenTelemetry project.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
$ helm repo add cftechwiz https://cftechwiz.github.io/opentelemetry-helm-charts
```

## Helm Charts

You can then run `helm search repo cftechwiz` to see the charts.

### OpenTelemetry Collector

The chart can be used to install [OpenTelemetry Collector](https://github.com/cftechwiz/opentelemetry-collector)
in a Kubernetes cluster. More detailed documentation can be found in
[OpenTelemetry Collector chart directory](./charts/opentelemetry-collector).

### OpenTelemetry Demo

The chart can be used to install [OpenTelemetry Demo](https://github.com/cftechwiz/opentelemetry-demo)
in a Kubernetes cluster. More detailed documentation can be found in
[OpenTelemetry Demo chart directory](./charts/opentelemetry-demo).

### OpenTelemetry Operator

The chart can be used to install [OpenTelemetry Operator](https://github.com/cftechwiz/opentelemetry-operator)
in a Kubernetes cluster. More detailed documentation can be found in
[OpenTelemetry Operator chart directory](./charts/opentelemetry-operator).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

[Apache 2.0 License](./LICENSE).
