# Data

![Hard](https://img.shields.io/badge/Difficulty-◆%20Hard-grey?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you’ll learn about persisting data beyond a process in memory, including binary files and structured data stored in databases.

<img width="1440" alt="Data Module" src="https://user-images.githubusercontent.com/894178/138357282-e49884e2-dd8b-42fd-828f-74c833d3d31a.png">

## Topics

<details open>
   <summary><b>Types of Data</b></summary><br/>

   With this topic, you’ll learn about the spectrum of unstructured to structured data types and how to classify data correctly.
   
   #### Learning Outcomes
   * Describe binary data
   * Compare structured and unstructured data types
   * Theorize what data types you might use in an application

   #### Resources
   * [Structured vs. Unstructured Data `Article`](https://www.ibm.com/cloud/blog/structured-vs-unstructured-data)

   #### Exercises
   * [File to Hex](../exercises/data/file-to-hex.md)
</details>

----

<details open>
   <summary><b>Data Storage</b></summary><br/>

   With this topic, you’ll learn techniques to store data of all types for usage in an application.
   
   #### Learning Outcomes
   * Compare storing data in a relational and non-relational database
   * Explain storing data using object storage providers such as AWS S3
   * Describe three different approaches to persist data for an application

   #### Resources
   * [7 Database Paradigms `Video`](https://www.youtube.com/watch?v=W2Z7fbCLSTw)
   * [Cloud Firestore `Tool`](https://firebase.google.com/products/firestore)
   * [AWS Databases `Resource`](https://aws.amazon.com/products/databases)
   * [AWS Storage `Resource`](https://aws.amazon.com/products/storage)

   #### Exercises
   * [Database Provisioning](../exercises/data/database-provisioning.md)
</details>

----

<details open>
   <summary><b>Data Manipulation</b></summary><br/>

   With this topic, you’ll learn how to interact with and manipulate data from storage providers using techniques such as SQL or SSH. 
   
   #### Learning Outcomes
   * Explain what CRUD operations are
   * Explain what relational database schema is
   * Retrieve data from a database using a SELECT query
   * Use an ORM to retrieve data from a database in an application
   * Download a file from a server using SSH
   * Create a new item in a database table using an INSERT INTO query
   * Update an existing item in a database table using an UPDATE query
   * Delete an existing item in a database table using a DELETE query
   * Use migrations to update the schema of a database

   #### Resources
   * [SQL Explained in 100 Seconds `Video`](https://www.youtube.com/watch?v=zsjvFFKOm3c)
   * [SQL playground `Tool`](https://sql-playground.wizardzines.com/)

   #### Exercises
   * [ORM Utilization](../exercises/data/orm-utilization.md)
</details>

----

<details open>
   <summary><b>Data Wrangling</b></summary><br/>

   With this topic, you’ll learn to convert data from one type to another using data wrangling techniques.
   
   #### Learning Outcomes
   * Describe the ETL (extract, transform, load) process
   * Use a regular expression (Regex) to grep for IP addresses in log files
   * Convert a WAV audio file to an MP3 audio file using ffmpeg

   #### Resources
   * [Missing Semester: Data Wrangling `Video`](https://missing.csail.mit.edu/2020/data-wrangling/)

   #### Exercises
   * [FFmpeg Conversion](../exercises/data/ffmpeg-conversion.md)
</details>

----

<details open>
   <summary><b>Managing State</b></summary><br/>

   With this topic, you’ll learn about effectively using different patterns to manage the state in an application.
   
   #### Learning Outcomes
   * Describe application "state"
   * Explain the factors to consider when caching data
   * Describe the purpose of offline data storage
   * Compare using global and local state in an application
   * Compare eventual and strong consistency and explain their differences

   #### Resources
   * [What do you mean by "Event-Driven"? `Article`](https://www.martinfowler.com/articles/201701-event-driven.html)

   #### Exercises
   * [Cache Buster](../exercises/data/cache-buster.md)
</details>
