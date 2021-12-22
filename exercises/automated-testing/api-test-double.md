# Exercise: API Test Double

## Overview

| Key | Value |
| --- | --- |
| Goal | Using the proper test double, create a unit test that covers features that consumes an API |
| Duration | 2-4 hours |

## Steps

Use the following steps to help you progress through the exercise (use your best judgment, these are not precise steps):

1. Investigate a codebase and find some code (`code_block`) that makes a call to a REST API (`api`)
2. Create a unit test that invokes `code_block` and simulates a "success" response from the `api` using the proper test double
3. Next, create a unit test that invokes `code_block` and simulates an "error" response from the `api` using the proper test double
4. Repeat the same process with an end-to-end test suite
5. Share with your mentor!

## Questions

Use these questions to guide your curiosity during the exercise:

- What is a test double?
- What is the proper test double to use to simulate an API call from your 
- How did `code_block` handle an `api` call that succeeded?
- How did `code_block` handle an `api` call that failed?
- What [HTTP status codes](https://httpstatuses.com/) did you simulate? 
- What was different when you created an end-to-end test and a unit test?

## Reflection

Use the following questions to reflect on what you learned with this exercise and discuss with your mentor:

- If you were to mentor someone in the future, what highlights would you make sure they captured from this exercise? 
- How did this exercise build upon the learning outcomes from this topic? What would you change about the exercise to better suit your context for the next apprentice?
- What did this leave you excited to dig further into? 
- When you connect with your mentor after this next step, what do you hope to share with them? To celebrate? 

## Need help?

- [Join our Discord to ask questions](https://discord.gg/bDVYvG3Czd)
