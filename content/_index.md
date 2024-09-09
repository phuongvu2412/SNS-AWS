+++
title = "Amazon SNS (Simple Notification Service) Topic and Email Subscription"
date = 2024
weight = 0
chapter = false

+++

# Amazon SNS (Simple Notification Service) Topic and Email Subscription

#### Overview

**Amazon Simple Notification Service (SNS)** is a fully managed messaging service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SNS allows you to create "topics" which are communication channels to send messages or notifications to a large number of subscribers.

#### Key Steps to Create an SNS Topic and Subscribe an Email

##### 1. Create an SNS Topic:

-   An SNS topic is a logical access point that acts as a communication channel.
-   You can create a topic using the AWS Management Console, AWS CLI, or SDKs.
-   When creating a topic, specify a name and configure settings such as access policies, delivery retry policies, and more.

##### 2. Subscribe an Email Address to the Topic:

-   Once the topic is created, you can add subscriptions to it. In this case, the subscription type is "email."
-   The specified email address will receive a confirmation request. The subscription is only active after the recipient confirms it by clicking on the link in the email.

#### Main Content

1. [Creating a SNS Topic](1-Creating-a-SNS-Topic/)
2. [Creating a subscription](2-Creating-a-subscription/)
3. [Confirming a subscription](3-Confirming-a-subscription/)
4. [Publishing message to the topic](4-Publishing-message-to-the-topic/)
