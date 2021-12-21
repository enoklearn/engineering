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
   * [OWASP Top 10:2021 `Resource`](https://owasp.org/Top10/)
   * [OWASP Top 10:2021 Overview `Video`](https://youtu.be/uLBCDBnMEt0?t=929)

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
   * [Auth0 `Tool`](https://auth0.com/)
   * [Firebase Authentication `Tool`](https://firebase.google.com/products/auth)
   * [AWS Cognito `Tool`](https://aws.amazon.com/cognito/)
   * [Auth0 in 100 Seconds `Video`](https://www.youtube.com/watch?v=yufqeJLP1rI)
   * [Introduction to Identity `Video`](https://auth0.com/docs/videos/learn-identity-series/introduction-to-identity)
   * [Calling an API `Video`](https://auth0.com/docs/videos/learn-identity-series/calling-an-api)
   * [OpenID Connect and OAuth2 `Video`](https://auth0.com/docs/videos/learn-identity-series/openid-connect-and-oauth2)
   * [OWASP Authentication Cheatsheet `Resource`](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
   * [OWASP Authorization Cheatsheet `Resource`](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
   * [OAuth 2.0 Protocol `Resource`](https://tools.ietf.org/html/rfc6749)
   * [Ethereum Accounts `Article`](https://ethereum.org/en/developers/docs/accounts/)
   * [Signing in with Ethereum `Video`](https://youtu.be/f9XRH7bjV8M?t=1479)
   * [Identity and Reputation in Web 3 `Article`](https://sinahab.com/identity-and-reputation-in-web-3/)

   #### Exercises
   * [Setup an Identity Provider](../exercises/security/setup-an-identity-provider.md)
</details>

----

<details open>
   <summary><b>Managing Secrets</b></summary><br/>

   With this topic, you’ll learn about application secrets and how to manage them effectively.
   
   #### Learning Outcomes
   * Describe what an application secret is
   * Describe what an environment variable is
   * Explain why you might want to secure an application secret
   * Explain how you might inject secrets into an application using environment variables

   #### Resources
   * [7 Cryptography Concepts EVERY Developer Should Know `Video`](https://www.youtube.com/watch?v=NuyzuNBFWxQ)
   * [1Password Secrets Automation `Tool`](https://1password.com/secrets/)
   * [AWS Systems Manager (check out Parameter Store) `Tool`](https://aws.amazon.com/systems-manager/features/)
   * [Removing sensitive data from a repository `Resource`](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository)
   * [Working with AWS Parameter Store `Resource`](https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-working-with.html)
   * [Security and Cryptography `Video`](https://missing.csail.mit.edu/2020/security/)
   * [12 Factor App: Config `Resource`](https://12factor.net/config)

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
   * [Snyk Code `Tool`](https://snyk.io/product/snyk-code/)
   * [Sonarqube `Tool`](https://www.sonarqube.org/)
   * [GitHub Security `Tool`](https://github.com/features/security)

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
   * [What is Threat Modeling and Why Is It Important? `Video`](https://www.youtube.com/watch?v=h_BC6QMWDbA)
   * [Threat Modeling 101 `Video`](https://www.youtube.com/watch?v=xSk7JrxOMGE)
   * [Threat Modeling Worksheet `Resource`](https://saweis.net/threatworksheet/)
   * [Threat Modeling `Article`](https://owasp.org/www-community/Threat_Modeling)

   #### Exercises
   * [Threat Modeling](../exercises/security/threat-modeling.md)
</details>
