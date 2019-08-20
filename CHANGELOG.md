## 1.0.0 [unreleased]

### Features
1. [#2](https://github.com/bonitoo-io/influxdb-client-python/issues/2): The write client is able to write data in batches (configuration: `batch_size`, `flush_interval`, `jitter_interval`, `retry_interval`)
1. [#5](https://github.com/bonitoo-io/influxdb-client-python/issues/5): Added support for gzip compression of query response and write body 
 

### Bugs
1. [#3](https://github.com/bonitoo-io/influxdb-client-python/issues/3): The management API correctly supports inheritance defined in Influx API