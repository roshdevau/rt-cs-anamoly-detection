# Real-Time Clickstream Anomaly Detection Kinesis Analytics
This lab is provided as part of [AWS Innovate Data Edition](https://aws.amazon.com/events/aws-innovate/data/), click here to explore the full list of hands-on labs.

ℹ️ You will run this lab in your own AWS account and running this lab will incur some costs. Please follow directions at the end of the lab to remove resources to avoid future costs.

## Overview
This lab helps you to use Kinesis Data Analytics to perform Real-Time Clickstream Anomaly Detection. Amazon Kinesis Data Analytics is a managed service that makes it easy to analyse web log traffic that drive business decisions in real-time.

The lab uses the Kinesis Data Generator (KDG) tool to generate data and sends it to Amazon Kinesis. The tool provides a user-friendly UI that runs directly in your browser. 

*Duration* - Approximately 1 hour


With the KDG, you can do the following tasks:

        Create templates that represent records for your specific use cases
        Populate the templates with fixed data or random data
        Save the templates for future use
        Continuously send thousands of records per second to your Amazon Kinesis stream or Firehose delivery stream

## Architecture

[![Architecture](./images/architecture.png)]

## Setup

Prior to starting the lab
Click on link below to deploy you want to deploy pre-lab environment for the Real-Time Clickstream Anomaly Detection Amazon Kinesis Data Analytics lab.

| Region | CloudFormation |
| --- | --- |
| Asia Pacific(Sydney) | [![Launch Stack](images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/new?stackName=rtcs-anamoly-detect&templateURL=https://s3.amazonaws.com/aws-dataengineering-day.workshop.aws/Kinesis_PreLab.yaml)|


