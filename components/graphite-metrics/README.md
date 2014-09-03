graphite-metrics
================

A Polymer element to fetch Graphite metrics data.

[Documentation](http://guardian.github.io/element-graphite-metrics/)

## Example

``` html
<graphite-metrics baseUri="https://graphite.example.com"
                  target="ganglia.__SummaryInfo__.requests_latency-MyApp.sum"
                  since="{{timeStart}}"
                  until="{{timeEnd}}"
                  sink="{{data}}"></graphite-metrics>
```
