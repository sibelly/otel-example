## Open Telemetry Example
[OpenTelemetry](https://opentelemetry.io/docs/instrumentation/go/getting-started/) is an [Observability](https://opentelemetry.io/docs/concepts/observability-primer/#what-is-observability) framework and toolkit designed to create and manage telemetry data such as [traces](https://opentelemetry.io/docs/concepts/signals/traces/), [metrics](https://opentelemetry.io/docs/concepts/signals/metrics/), and [logs](https://opentelemetry.io/docs/concepts/signals/logs/).

#### Comands

- Inside `goapp`
```bash
docker compose up -d # to start a zipkin container
go run ./main.go 
```

- Inside `nodejs`

[README.md](https://github.com/sibelly/otel-example/blob/main/nodejs/README.md)