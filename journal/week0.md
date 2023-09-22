# Week 0 — Billing and Architecture

## Table of Contents
- [Installing AWS CLI](#installing-aws-cli)
- [Setting Up Billing](#setting-up-billing)
    - [AWS Budgets](#aws-budgets)
    - [Billing Alarms](#billing-alarms)
    - [Cost Explorer](#cost-explorer)
- [AWS Organisations](#aws-organisations)
- [Well Architected Tool](#well-architected-tool)
- [Created Cruddur LucidChart](#created-cruddur-lucidchart)


## Installing AWS CLI
Bash script written to automate AWS CLI installation using `.gitpod.yml` file.

Generated access keys within AWS Console to pass AWS credentials as Environment Variables (Env Vars) so they persist for each new gitpod workspace. Aswell as providing the means to interface with the AWS API services.


## Setting Up Billing

`AWS Budgets` and `Billing Alarms` can be used to manage spend within AWS. Allowing for notifications to be sent regarded your AWS infrastructure usage spend.

### AWS Budgets

Added a budget in AWS using Console. Monthly Budget of $10 set:

![Monthly Budget](assets/budget.png)

We can edit the budget and creating it by selecting the box to the left of the budget and using the `actions` dropdown to select `edit`.
From here we can adjust the threshold alerts to be notified when a given percentage of spend is reached.

### Billing Alarms

AWS Billing Alarms are a cost monitoring and alerting feature. These alarms allow us to set up thresholds and notifications based on their AWS spending.

### Cost Explorer

AWS Cost Explorer is a cost analysis tool provided that allows users to visualize and understand their AWS spending patterns. It offers insights into past, present, and projected AWS costs, helping users make informed decisions to optimize their cloud expenses.


## AWS Organisations
.


## Well Architected Tool
.


## Created Cruddur LucidChart
.

