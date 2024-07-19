# AElf Observability Environment

An OpenTelemetry Observability Environment including Otel Collector and Observability Backend.

- [About The Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Start Up](#start-up)
  - [Tear Down](#tear-down)
- [Contributing](#contributing)
- [License](#license)

## About The Project

An OpenTelemetry Observability Environment including Otel Collector and Observability Backend.  
Jaeger: http://localhost:16686/  
Prometheus: http://localhost:9090/  
Grafana: http://localhost:3000/  
OpenTelemetry Collector: http://localhost:4317/

## Getting Started

### Installation

Before using this local setup, please install docker:
[Docker Mac Installation](https://docs.docker.com/desktop/install/mac-install/)

### Start Up

To start up the whole service, please run the following command in root directory:

```bash
docker-compose up
```

### Tear Down

To tear down the entire service, please run the following command in root directory:

```bash
docker-compose down
```

## Contributing

If you encounter a bug or have a feature request, please use the [Issue Tracker](https://github.com/AElfProject/aelf-observability-setup/issues/new). The project is also open to contributions, so feel free to fork the project and open pull requests.

## License

Distributed under the MIT License. See [License](LICENSE) for more information.
