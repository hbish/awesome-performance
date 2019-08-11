# Awesome Performance
A collection of videos, talks and tools about performance engineering and testing.

From Wikipedia, [performance testing](https://en.wikipedia.org/wiki/Software_performance_testing) is in general a testing practice performed to determine how a system performs in terms of responsiveness and stability under a particular workload. It can also serve to investigate, measure, validate or verify other quality attributes of the system, such as scalability, reliability and resource usage.

Contributions are always welcome!

## Contents
- [Load Testing Tools](#load-testing-tools)
- [Load Testing Platform](#load-testing-platforms)
- [Application Performance Monitoring Tools](#apm-tools)
- [Browser Performance Testing](#browser-performance-testing)
- [Talks](#talks)
- [Articles](#articles)


## Load Testing Tools

### JVM
- [gatling](http://gatling.io) – highly configurable performance testing framework in scala, support multiple static/dynamic scenarios and html5/csv outputs
- [jmeter](http://jmeter.apache.org/) – Apache JMeter™, complete performance test suite with support for dynamic scenarios and various plugins

### Go
- [bombardier](https://github.com/codesenberg/bombardier) – benchmarking tool using `fasthttp` 
- [fasthttploader](https://github.com/hagen1778/fasthttploader) – simple benchmarking tool with basic charting 
- [goad](https://github.com/gophergala2016/goad) – AWS Lambda powered distributed load testing tool, good for multi-region testing
- [gobench](https://github.com/cmpxchg16/gobench) – HTTP/HTTPS load testing and benchmarking tool, lacks configuration
- [hey](https://github.com/rakyll/hey) – configurable load generator and load test tool, currently only output csv
- [slow_cooker](https://github.com/BuoyantIO/slow_cooker) – load tester focused on lifecycle issues and long-running tests with periodic reports
- [sniper](https://github.com/lubia/sniper) – high-performance http load tester supports large files, support html5 reports
- [vegeta](https://github.com/tsenart/vegeta) – configurable HTTP load testing tool, can also be used as a library for dynamic scenarios, good outputs.

### C
- [ab](http://httpd.apache.org/docs/2.4/programs/ab.html) - the og of benchmarking tools, slow and single threaded
- [apib](https://github.com/apigee/apib) - extension of `ab` with fewer dependencies and non-blocking IO for concurrency
- [curl-loader](http://curl-loader.sourceforge.net/) -  
- [httpref](https://github.com/httperf/httperf) - 
- [weighttp](http://redmine.lighttpd.net/projects/weighttp/wiki) - lightweight benchmarking tool, only support a small fraction of HTTP protocol
- [wrk2](https://github.com/giltene/wrk2) - based on original `wrk` 

### Other
- [yandex-tank](https://github.com/yandex/yandex-tank) (python) - extensible load testing tool, uses yandex's own `phantom` engine in the background, capable of generating ~100000 tps.
- [locust.io](https://locust.io) (python) - configurable load testing tool, can define user behaviour and run across multiple machines or kubernetes cluster
- [artillery](https://artillery.io) (nodejs) - highly configurable load and functional testing toolkit, allows dynamic scenarios and can ship metrics to external monitoring systems
- [tsung](http://tsung.erlang-projects.org) (erlang) - distributed load testing tool, can simulate hundreds of users from single machine or distribute them on clusters
- [postman/newman](https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman/) - using `newman` cli as a postman collection runner
 
## Load Testing Platforms
- [BlazeMeter](https://www.blazemeter.com) - scalable, open source-based performance tests against web apps and services, support multiple performance script jMeter, Gatling etc...
- [Gatling Frontline](https://gatling.io/gatling-frontline/) - enterprise version of gatling.
- [Artillery Pro](http://artillery.io/pro/) 
- [flood.io](https://flood.io/load-performance-testing-tool/) 

## Application Performance Monitoring Tools
https://github.com/bestiejs/benchmark.js
- [New Relic APM](https://newrelic.com) - real time application performance monitoring, end to end transaction tracing
- [New Relic Browser](https://newrelic.com/products/browser-monitoring) - client side error and performance monitoring, observes page loads, response time and establish baseline for ongoing monitoring. 
- [Nginx Amplify](https://amplify.nginx.com/docs/) - a tool for comprehensive NGINX monitoring. With NGINX Amplify it's easy to proactively analyze and fix problems related to running and scaling NGINX-based web applications.
- [jHiccup](https://github.com/giltene/jHiccup) - jvm agent to monitor for 'hiccup' in application

## Browser Performance Testing
- [Pingdom](https://tools.pingdom.com/)
- [Gtmetrix](https://gtmetrix.com/)
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [SiteSpeed](https://www.sitespeed.io/)

## Talks
- [using open source tools for performance testing](https://www.youtube.com/watch?v=k9h51BM2h4w) - Goranka Bjedov
- [Performance tests with Gatling](https://www.youtube.com/watch?v=cRo0G-vpC7c) - Andrzej Ludwikowski

## Articles

### General
- [Fast Load Time](https://web.dev/fast) 

### Performance Budget
- [Performance Budgets Overview](https://addyosmani.com/blog/performance-budgets/) 
- [Performance Budget Calculator](http://www.performancebudget.io) 
- [Performance Budget with Tim Kadlec](https://www.youtube.com/watch?list=PLYo5nh8xQFpkwsu9QNlCpPGkmCCuTTWDJ&v=yqejmZrtmNg) 
