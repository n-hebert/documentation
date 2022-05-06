---
id: metrics-basic-authentication
title: Metrics Basic Authentication
keywords:
- reference
- Metrics Basic Authentication
---


# Metrics Basic Authentication
- Environmental Variable: `METRICS_BASIC_AUTH`
- Config File Key: `metrics_basic_auth`
- Type: base64 encoded `string` of `username:password`
- Example: `eDp5` (for username: x, and password: y)
- Default: ``
- Optional

Require [Basic HTTP Authentication](https://tools.ietf.org/html/rfc7617) to access the metrics endpoint.

To support this in Prometheus, consult the `basic_auth` option in the [`scrape_config`](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#scrape_config)
documentation.
