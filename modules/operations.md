# Operations

![Moderate](https://img.shields.io/badge/Difficulty-■%20Moderate-blue?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you'll learn the discipline of change management, automated techniques to distribute your product, and how to monitor product health.

<img width="1440" alt="NASA control room" src="https://user-images.githubusercontent.com/894178/138357853-527268e0-eb25-447b-bf1f-c1f654ab3e70.png">

## Topics

<details open>
   <summary><b>Managing Releases</b></summary><br/>

   With this topic, you'll learn about change management and how to release new versions of an application with as little downtime as possible.
   
   #### Learning Outcomes
   * Describe what release management is
   * Create a release checklist with release and rollback steps
   * Theorize what approval you'd need to get before releasing a change

   #### Resources
   * [12 Factor App: Build, release, run `Resource`](https://12factor.net/build-release-run)
   * [Build pipelines, deployment, and immutable artifacts `Article`](https://www.brunton-spall.co.uk/post/2016/08/23/Build-pipelines-deployment-and-immutable-artifacts-48ae926178a5/)
   * [How we managed 49 monthly releases [at GitLab] `Article`](https://about.gitlab.com/blog/2015/12/17/gitlab-release-process/)
   * [Release Frequency and the Adoption of Agile Practices `Article`](https://telegraphhillsoftware.com/release-frequency-agile-practices/)
   * [Release Frequency: A Need for Speed `Article`](https://dzone.com/articles/release-frequency-a-need-for-speed)
   * [The Rust Release Process `Article`](https://forge.rust-lang.org/release/process.html)
   * [What Is Release Management? `Article`](https://www.productplan.com/glossary/release-management/)

   #### Exercises
   * [Artifact Deployment](../exercises/operations/artifact-deployment.md)
</details>

----

<details open>
   <summary><b>Managing Incidents</b></summary><br/>

   With this topic, you'll learn to keep calm under the stress of resolving production application incidents.
   
   #### Learning Outcomes
   * Describe what incident management is
   * Describe what a runbook is
   * Explain what an SLO means
   * Explain what an SLA means
   * Create a runbook with step-by-step instructions to solve a common problem
   
   #### Resources
   * [DataDog Incident Management `Tool`](https://docs.datadoghq.com/monitors/incident_management/)
   * [Gitlab Runbooks `Resource`](https://gitlab.com/gitlab-com/runbooks)
   * [Service-level agreement `Article`](https://en.wikipedia.org/wiki/Service-level_agreement)
   * [SLA vs. SLO vs. SLI: What's the difference? `Article`](https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli)
   * [What is incident management? `Article`](https://www.atlassian.com/incident-management)

   #### Exercises
   * [Create a Runbook](../exercises/operations/create-a-runbook.md)
</details>

----

<details open>
   <summary><b>Continuous Integration and Deployment</b></summary><br/>

   With this topic, you'll learn to automate the release process using continuous integration and deployment (CI/CD) pipelines.
   
   #### Learning Outcomes
   * Describe what a CI/CD pipeline is
   * Create a CI pipeline to run automated tests and compile build artifacts
   * Create a CD pipeline to deploy build artifacts for development, staging, and production environments

   #### Resources
   * [CircleCI `Tool`](https://circleci.com/)
   * [ContinuousDelivery `Article`](https://martinfowler.com/bliki/ContinuousDelivery.html)
   * [DevOps CI/CD Explained in 100 Seconds `Video`](https://www.youtube.com/watch?v=scEDHsr3APg)
   * [GitHub Actions `Tool`](https://docs.github.com/en/actions)
   * [Gitlab Pipelines `Tool`](https://docs.gitlab.com/ee/ci/pipelines/)
   * [What's DevOps? `Article`](https://jvns.ca/blog/2016/10/16/whats-devops/)
   * [DevOps Handbook `Book ($)`](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations-ebook/dp/B01M9ASFQ3)

   #### Exercises
   * [Setup a CI/CD pipeline](../exercises/operations/setup-a-ci-cd-pipeline.md)
</details>

----

<details open>
   <summary><b>Performance Testing</b></summary><br/>

   With this topic, you'll learn how to verify the performance of an application using load tests, smoke tests, and black-box testing.
   
   #### Learning Outcomes
   * Describe what performance testing is
   * Explain how you might create a performance test for an application
   * Integrate performance testing into your CI/CD pipeline

   #### Resources
   * [Artillery `Tool`](https://artillery.io/)
   * [K6 `Tool`](https://k6.io/)
   * [Writing your first artillery test `Resource`](https://www.artillery.io/docs/guides/getting-started/writing-your-first-test)

   #### Exercises
   * [Zombie Horde](../exercises/operations/zombie-horde.md)
</details>

----

<details open>
   <summary><b>Working with Site Reliability Engineers</b></summary><br/>

   With this topic, you'll learn about the role of a site reliability engineer and how to work with them on your team effectively.
   
   #### Learning Outcomes
   * Describe what toil is
   * Describe the role of a site reliability engineer
   * Identify what you need from a site reliability engineer to complete software engineering tasks
   * Explain how you might collaborate with a site reliability engineer to maintain resilience for an application

   #### Resources
   * [Building Secure & Reliable Systems `Book`](https://static.googleusercontent.com/media/sre.google/en//static/pdf/building_secure_and_reliable_systems.pdf)
   * [Site Reliability Engineering `Book`](https://sre.google/sre-book/table-of-contents/)
   * [The History of SRE `Video`](https://www.youtube.com/watch?v=1NF6N2RwVoc)
   * [The Site Reliability Workbook `Book`](https://sre.google/workbook/table-of-contents/)
   * [What's the Difference Between DevOps and SRE? `Video`](https://www.youtube.com/watch?v=uTEL8Ff1Zvk)

   #### Exercises
   * [Reduce Toil](../exercises/operations/reduce-toil.md)
</details>
