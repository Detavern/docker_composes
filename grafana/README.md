# README

## GRAFANA

if `~/Docker/etc/grafana:/etc/grafana` is active in volume mapping,
you should prepare your own `grafana.ini` (grafana configuration ini file)

## INFLUXDB

use `docker run --rm influxdb influxd config > influxdb.conf` to generate
influxdb configuration file.
