# wemo-exporter: A Prometheus exporter for the Belkin Wemo Insight

## Introduction

This is a python-based [Prometheus][1] exporter for the [Belkin Wemo
Insight][2] power adaptor. It leverages the LAN [API][3] for these
devices to export metrics compatable with Prometheus via a proxy.

## Installation

## Default Port

The [default port][4] of 9632 has been reserved for this exporter.

[1]: https://prometheus.io/
[2]: https://www.belkin.com/us/p/P-F7C029/
[3]: https://github.com/iancmcc/ouimeaux
[4]:https://github.com/prometheus/prometheus/wiki/Default-port-allocations
