# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability |  Total successful requests / total requests	  | 99%                                                                                                         |
| Latency      |  requests shows 90th percentile over the last 30 seconds	   | 90% of requests below 100ms                                                                                 |
| Error Budget |  Comparison of the percentage of all unsuccessful requests to the percentage of all failed requests used   | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   |   sum of all requests that were successful for more than five minutes  | 5 RPS indicates the application is functioning                                                              |
