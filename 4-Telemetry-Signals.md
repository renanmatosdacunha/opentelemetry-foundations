## Telemetry Signals

Data collected from a system to monitor its behaviour & performance
* Metrics
* Logs
* Traces
* Baggage

### Metrics

How Open Telemetry collects metrics
* Initialize Meter provider
* Meter creates metric instruments which captures measurements
* Metric exporter sends metrics to a consumer

Metrics dfinitions:
* Name
* Kind
* Unit(optional)
* Description(optional)

Metrics kinds:
* Counter
* Asynchronous Counter
* UpDownCounter
* Asynchronous UpDownCounter
* Gauge
* Histogram

