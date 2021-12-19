# Security

![Moderate](https://img.shields.io/badge/Difficulty-■%20Moderate-blue?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you’ll learn how to keep secrets safe and write code that keeps user data private and secure.

<img width="1440" alt="Security Module" src="https://user-images.githubusercontent.com/894178/138358200-0c58972c-1800-4fba-91db-f85d5fa4a4ab.png">


## Topics

<details open>
   <summary><b>OWASP Top 10</b></summary><br/>

   With this topic, you’ll learn about the most common application security issues and how to mitigate them.
   
   #### Learning Outcomes
   * Describe each of the vulnerabilities in the OWASP Top 10
   * Describe what threat modeling is
   * Explain how you might prevent the “Broken Access Control” vulnerability
   * Explain what remediation is, and how you might remediate an “Injection” vulnerability

   #### Resources
   * https://owasp.org/Top10/

   #### Exercises
   * [Remediate the Broken Access Control vulnerability](../exercises/security/broken-access-control.md)
</details>

----

<details open>
   <summary><b>Authentication and Authorization</b></summary><br/>

   With this topic, you’ll learn about identity providers and how to use OAuth 2.0 to manage authentication and authorization in an application.
   
   #### Learning Outcomes
   * Compare authentication with authorization and explain their differences
   * Use an identity provider to authenticate users in an application
   * Explain what “federated identities” are
   * Explain what the OAuth 2.0 standard is

   #### Resources
   * https://auth0.com/
   * https://aws.amazon.com/cognito/
   * [OAuth 2.0](https://tools.ietf.org/html/rfc6749)

   #### Exercises
   * [Setup an Identity Provider](../exercises/security/setup-an-identity-provider.md)
</details>

----

<details open>
   <summary><b>Managing Secrets</b></summary><br/>

   With this topic, you’ll learn about application secrets and how to manage them effectively.
   
   #### Learning Outcomes
   * Describe what an application secret is
   * Explain why you might want to secure an application secret
   * Explain how you might inject secrets into an application using environment variables

   #### Resources
   * https://12factor.net/config

   #### Exercises
   * [Fetch an Application Secret](../exercises/security/fetch-an-application-secret.md)
</details>

----

<details open>
   <summary><b>Continuous Security</b></summary><br/>

   With this topic, you’ll learn about methods to integrate security scanning into a project CI/CD pipeline.
   
   #### Learning Outcomes
   * Describe what continuous security is
   * List out some tools you might you use to to scan a project for vulnerabilities
   * Explain how you might go about remediating vulnerabilities found from automated scanning

   #### Resources
   * https://snyk.io/
   * https://www.npmjs.com/package/sonarqube-scanner

   #### Exercises
   * [Setup Dependency Scanning](../exercises/security/setup-dependency-scanning.md)
</details>

----

<details open>
   <summary><b>Working with Security Engineers</b></summary><br/>

   With this topic, you’ll learn about the role of a security engineer and how to work with them on your team effectively.
   
   #### Learning Outcomes
   * Describe the role of a security engineer
   * Identify what you need from a security engineer to complete software engineering tasks
   * Explain how you might work with a security engineer to remediate vulnerabilities

   #### Resources
   * https://owasp.org/www-community/Threat_Modeling

   #### Exercises
   * [Threat Modeling](../exercises/security/threat-modeling.md)
</details>
