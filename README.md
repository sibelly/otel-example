## OpenTelemetry

[OpenTelemetry](https://opentelemetry.io/docs/instrumentation/go/getting-started/) is an [Observability](https://opentelemetry.io/docs/concepts/observability-primer/#what-is-observability) framework and toolkit designed to create and manage telemetry data such as [traces](https://opentelemetry.io/docs/concepts/signals/traces/), [metrics](https://opentelemetry.io/docs/concepts/signals/metrics/), and [logs](https://opentelemetry.io/docs/concepts/signals/logs/).

### OpenTelemetry Contribution Extensions

A very nice differencial of opentelemetry is the [contribution repository] that the community keep on track, making possible to integrate with a lot of already products on market, like the biggest clouds (GCP, AWS, Azure).

- [opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib/tree/main/exporter)

## Zipkin

[Zipkin](https://zipkin.io/) is a distributed tracing system. It helps gather timing data needed to troubleshoot latency problems in service architectures. Features include both the collection and lookup of this data.

![zipkin dashboard showing traces](https://github.com/sibelly/otel-example/blob/main/.github/assets/show-trace.png)

![zipkin dashboard showing dependencies services](https://github.com/sibelly/otel-example/blob/main/.github/assets/dependencies-services.png)

## Commands

- Inside directory `goapp`
```bash
docker compose up -d # to start a zipkin container
go run ./main.go 
```

- Inside directory `nodejs`

[README.md](https://github.com/sibelly/otel-example/blob/main/nodejs/README.md)