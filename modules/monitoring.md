# Monitoring

![Moderate](https://img.shields.io/badge/Difficulty-■%20Moderate-blue?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you'll learn how to use telemetry to measure application performance in production environments.

<img width="1440" alt="Monitoring Module" src="https://user-images.githubusercontent.com/894178/138357785-5c440e7b-6cf5-4886-ad7c-7ab517fb7c58.png">


## Topics

<details open>
   <summary><b>Collecting Logs, Errors, Metrics, and Traces</b></summary><br/>

   With this topic, you’ll learn about the different types of telemetry data that can be collected in an application.
   
   #### Learning Outcomes
   * Describe what a log is
   * Describe what an error is
   * Describe what a metric is
   * Describe what a trace is
   * Explain how you might collect telemetry data in an application

   #### Resources
   * [DataDog `Tool`](https://datadoghq.com/)
   * [Grafana `Tool`](https://grafana.com/)
   * [Sentry `Tool`](https://sentry.io/)
   * [OpenTelemetry `Tool`](https://opentelemetry.io/)
   * [Monitor what matters `Video`](https://www.youtube.com/watch?v=EnvKjTw-xTo)
   * [Grafana Explained in Under 5 Minutes `Video`](https://www.youtube.com/watch?v=lILY8eSspEo)
   * [When to use the different log levels `Thread`](https://stackoverflow.com/questions/2031163/when-to-use-the-different-log-levels/64806781#64806781)

   #### Exercises
   * [Collecting Telemetry](../exercises/monitoring/collecting-telemetry.md)
   * Integrate Sentry.io in an application to collect crash reports
   * Integrate DataDog into an application
</details>

----

<details open>
   <summary><b>The Golden Signals</b></summary><br/>

   With this topic, you’ll learn about four valuable metrics to measure the health of an application.
   
   #### Learning Outcomes
   * List the four golden signals
   * Explain how you might keep track of the golden signals

   #### Resources
   * [Site Reliability Engineering `Book`](https://sre.google/sre-book/table-of-contents/)
   * [The Site Reliability Workbook `Book`](https://sre.google/workbook/table-of-contents/)
   * [Building Secure & Reliable Systems `Book`](https://static.googleusercontent.com/media/sre.google/en//static/pdf/building_secure_and_reliable_systems.pdf)
   * [The History of SRE `Video`](https://www.youtube.com/watch?v=1NF6N2RwVoc)

   #### Exercises
   * [Setup a Dashboard in Grafana](../exercises/monitoring/setup-a-dashboard-in-grafana.md)
</details>

----

<details open>
   <summary><b>Effective Alerting</b></summary><br/>

   With this topic, you’ll learn about signal vs. noise and how to create valuable alerts that raise the alarm when something goes wrong in your application.
   
   #### Learning Outcomes
   * Describe what being on-call means
   * Explain what signal vs. noise is
   * Explain how you might use the golden signals to setup useful alerts

   #### Resources
   * [Monitoring 101: Alerting on what matters](https://www.datadoghq.com/blog/monitoring-101-alerting/)
   * https://aws.amazon.com/cloudwatch/
   
   #### Exercises
   * [Golden Signal Alerting](../exercises/monitoring/golden-signal-alerting.md)
</details>

----

<details open>
   <summary><b>Debugging</b></summary><br/>

   With this topic, you’ll learn about techniques to debug and resolve application issues using telemetry data.
   
   #### Learning Outcomes
   * Describe debugging
   * Explain how you might use telemetry data to help you debug an issue
   * Explain what breakpoints are
   * Setup debugging tools in your IDE

   #### Resources
   * [Snyk `Tool`](https://snyk.io/)

   #### Exercises
   * [Bug Bounty](../exercises/monitoring/bug-bounty.md)
</details>

----

<details open>
   <summary><b>Improving Performance</b></summary><br/>

   With this topic, you’ll learn how to improve the scalability and reliability of an application based on its utilization.
   
   #### Learning Outcomes
   * Explain how you might use metrics to set a performance baseline

   #### Resources
   * [Web Vitals `Article`](https://web.dev/vitals/)

   #### Exercises
   * [Performance Boost](../exercises/monitoring/performance-boost.md)
</details>
