# Terraform-Game-Day-Notifications

"NBA Game Day Notification"

# Technical Architecture

![image_alt](https://github.com/Tatenda-Prince/Terraform-Gama-Day-Notifications-/blob/c2a302281b7d6de8936b89d3397833d9db20c4ca/img/Screenshot%202025-02-10%20200330.png)

## Project Overview

This project is an alert system that sends real-time NBA game day score notifications to subscribed users via SMS/Email. It leverages Amazon SNS, AWS Lambda and Python, Amazon EvenBridge and NBA APIs to provide sports fans with up-to-date game information. The project demonstrates how we can use Infrastructure as Code by leveraging Terraform to automate the deployement and destruction of this solution in seconds.

## Features

1.Fetches live NBA game scores using an external API.

2.Sends formatted score updates to subscribers via SMS/Email using Amazon SNS.

3.Scheduled automation for regular updates using Amazon EventBridge.

4.Designed with security in mind, following the principle of least privilege for IAM roles.

## Prerequisites

1.Free account with subscription and API Key at sportsdata.io

2.Personal AWS account with basic understanding of AWS and Python

3.AWS CLI installed and configured to your personal account

4.Terraform CLI version 1.10.5 installed on your local environment

## Technologies

1.Cloud Provider: AWS

2.Infrastructure as Code tool: Terraform

3.Core Services: SNS, Lambda, EventBridge

4.External API: NBA Game API (SportsData.io)

5.Programming Language: Python 3.x

6.IAM Security:
Least privilege policies for Lambda, SNS, EventBridge and Systems Manager

## Project Structure

```python
game-day-notifications_terraform/
├── nba_notifications.py         # Main Lambda function code
├── nba_notifications.zip        # Main Lambda function zipped file
├── game_day_notifications.tf    # Game Day notification Terraform config file
├── LICENSE                     
├── .gitignore
└── README.md                    # Project documentation
Setup Instructions

```

Step 1:Clone the Repository

1.1.Clone this repository to your local machine

```language

```






