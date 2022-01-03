# Monitoring

![Moderate](https://img.shields.io/badge/Difficulty-■%20Moderate-blue?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you'll learn to use telemetry to measure application performance in production environments.

<img width="1440" alt="Two security cameras" src="https://user-images.githubusercontent.com/894178/138357785-5c440e7b-6cf5-4886-ad7c-7ab517fb7c58.png">


## Topics

<details open>
   <summary><b>Collecting Logs, Errors, Metrics, and Traces</b></summary><br/>

   With this topic, you'll learn about the different types of telemetry data that can be collected in an application.
   
   #### Learning Outcomes
   * List the different types of telemetry data that can be collected
   * Explain how you could collect telemetry data in an application
   * Theorize why you might want to collect telemetry data

   #### Resources
   * [DataDog `Tool`](https://datadoghq.com/)
   * [Docker Container DataDog Agent Installation `Tutorial`](https://docs.datadoghq.com/agent/docker/log/?tab=containerinstallation)
   * [Grafana `Tool`](https://grafana.com/)
   * [Grafana Explained in Under 5 Minutes `Video`](https://www.youtube.com/watch?v=lILY8eSspEo)
   * [Monitor what matters `Video`](https://www.youtube.com/watch?v=EnvKjTw-xTo)
   * [OpenTelemetry `Tool`](https://opentelemetry.io/)
   * [Sentry `Tool`](https://sentry.io/)
   * [When to use the different log levels `Thread`](https://stackoverflow.com/questions/2031163/when-to-use-the-different-log-levels/64806781#64806781)

   #### Exercises
   * [Collecting Telemetry Data](../exercises/monitoring/collecting-telemetry-data.md)
   * Integrate Sentry.io in an application to collect crash reports
   * Integrate DataDog into an application
</details>

----

<details open>
   <summary><b>The Golden Signals</b></summary><br/>

   With this topic, you'll learn about four valuable metrics to measure the health of an application.
   
   #### Learning Outcomes
   * List the four golden signals
   * Explain how you might keep track of the golden signals

   #### Resources
   * [Distributed Monitoring 101 `Article`](https://medium.com/forepaas/distributed-monitoring-101-the-four-golden-signals-305bbbc33d35)
   * [SRE: Monitoring Distributed Systems `Book`](https://sre.google/sre-book/monitoring-distributed-systems/)

   #### Exercises
   * [Golden Dashboard](../exercises/monitoring/golden-dashboard.md)
</details>

----

<details open>
   <summary><b>Effective Alerting</b></summary><br/>

   With this topic, you'll learn about signal vs. noise and how to create valuable alerts that raise the alarm when something goes wrong in your application.
   
   #### Learning Outcomes
   * Describe what being on-call means
   * Explain what signal and noise is
   * Explain how you might use the golden signals to create useful alerts

   #### Resources
   * [What is signal and noise? `Article`](https://conceptually.org/concepts/signal-and-noise)
   * [Alerting on what matters `Article`](https://www.datadoghq.com/blog/monitoring-101-alerting/)
   * [AWS CloudWatch `Tool`](https://aws.amazon.com/cloudwatch/)
   * [Analysis shows pilots often ignore Boeing 737 cockpit alarm `Article`](https://www.travelweekly.com/Travel-News/Airline-News/Analysis-shows-pilots-often-ignore-Boeing-737-cockpit-alarm)
   
   #### Exercises
   * [Golden Signal Alerting](../exercises/monitoring/golden-signal-alerting.md)
</details>

----

<details open>
   <summary><b>Debugging</b></summary><br/>

   With this topic, you'll learn about techniques to debug and resolve application issues using telemetry data.
   
   #### Learning Outcomes
   * Describe debugging
   * Explain how you might use telemetry data to help you debug an issue
   * Explain what breakpoints are
   * Setup debugging tools in your IDE

   #### Resources
   * [Debugging and Profiling `Video`](https://missing.csail.mit.edu/2020/debugging-profiling/)
   * [How do Ruby & Python profilers work? `Article`](https://jvns.ca/blog/2017/12/17/how-do-ruby---python-profilers-work-/)

   #### Exercises
   * [Bug Bounty](../exercises/monitoring/bug-bounty.md)
</details>

----

<details open>
   <summary><b>Improving Performance</b></summary><br/>

   With this topic, you'll learn how to improve the scalability and reliability of an application based on its utilization.
   
   #### Learning Outcomes
   * Describe a performance benchmark
   * Explain how you might use metrics to improve the performance of a feature

   #### Resources
   * [Lighthouse `Tool`](https://developers.google.com/web/tools/lighthouse/)
   * [Web Vitals `Article`](https://web.dev/vitals/)
   * [What is StatsD and how can it help you? `Article`](https://www.datadoghq.com/blog/statsd/)
   * [StatsD `Tool`](https://github.com/statsd/statsd)

   #### Exercises
   * [Performance Boost](../exercises/monitoring/performance-boost.md)
</details>
