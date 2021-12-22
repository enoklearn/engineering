# Exercise: Cloud Environment Replication

## Overview

| Key | Value |
| --- | --- |
| Goal | Using Terraform, create two mirrored environments using the "workspaces" feature |
| Duration | 2-4 hours |

Make sure you have Terraform downloaded and installed on your machine, and a DigitalOcean account created before you get started. It is also important to remember to tear down cloud resources you don't intend to keep araound -- you don't want to get an unwanted bill!

## Steps

Use the following steps to help you progress through the exercise (use your own judgement, these are not precise steps):

1. Create a simple Terraform configuration (you could reuse a previous one if you like)
2. Apply it to a cloud environment (we recommend DigitalOcean)
3. After it has been sucessfully provisioned in one environment, return to the command line
4. Create a new Terraform workspace called "staging"
5. Switch to the "staging" workspace, and apply your infrastructure
6. Tear down your infrastructure
7. Share the results with your mentor!

## Questions

Use these questions to guide your curiosity during the exercise:

- What is DigitalOcean?
- What is a staging environment?
- How do you quickly tear down infrastructure with Terraform?

## Reflection

Use the following questions to reflect on what you learned with this exercise and discuss with your mentor:

- What did this leave you excited to dig further into? 
- Where do you want to go from here?
- What would be your next step? What resources can support you in this next step?
- When you connect with your mentor after this next step, what do you hope to share with them? To celebrate? 

## Need help?

- [Join our Discord to ask questions](https://discord.gg/bDVYvG3Czd)
