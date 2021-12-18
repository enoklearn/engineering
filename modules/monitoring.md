# Monitoring

![Moderate](https://img.shields.io/badge/Difficulty-■%20Moderate-blue?style=flat-square)
<a href="https://github.com/engineerkit/engineerkit/discussions">![Ask Questions](https://img.shields.io/badge/Ask%20Questions%20-blue.svg?style=flat-square&logo=discourse&logoWidth=15&labelColor=555&color=4d51cc)</a>

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
   * https://docs.datadoghq.com/

   #### Exercises
   * Integrate Sentry.io in an application to collect crash reports
   * Collect logs using stdout in an application
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
   * https://sre.google/sre-book/table-of-contents/

   #### Exercises
   * Setup a dashboard in DataDog to monitor the golden signals
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
   * https://www.datadoghq.com/
   * https://aws.amazon.com/cloudwatch/
   
   #### Exercises
   * Setup alerts based on one of the golden signals in your DataDog dashboard
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
   * https://snyk.io/

   #### Exercises
   * Pair with a software engineer on a production bug, and use telemetry data to assist in recreating the problem
</details>

----

<details open>
   <summary><b>Improving Performance</b></summary><br/>

   With this topic, you’ll learn how to improve the scalability and reliability of an application based on its utilization.
   
   #### Learning Outcomes
   * Explain how you might use metrics to set a performance baseline

   #### Resources
   * https://web.dev/vitals/

   #### Exercises
   * Pair with a software engineer to improve the performance of a feature using telemetry data
</details>
