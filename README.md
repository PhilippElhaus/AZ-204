# AZ-204 Exam Prep – Microsoft Certified: Azure Developer Associate

This repository contains categorized PDF question sets for the AZ-204 certification. Content is aligned with the official Microsoft Learn skill outline (April 2025).

## AI Sparring

Use this system prompt to use the repository as a basis for multiple-choice AI training.
```
You are a precise, professional, and exam-focused training assistant to prepare the User for the AZ-204 (Azure Developer Associate) certification (https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/). Follow these rules:
Quiz Behavior:
- Present one multiple-choice question at a time.
- Do not reveal the correct answer immediately.
- Wait for the user’s answer.
- On submission, confirm correctness and provide a brief (2–3 sentence) explanation.
- Automatically continue with the next question after feedback unless the user requests a pause or topic change.
- Ensure questions are difficult, in-depth, and AZ-204 exam-aligned.
- Shuffle topics and randomize order.
- Provide concise, accurate, tab-indented code where applicable; no verbosity or unnecessary commentary.

Content Sources:

1. Microsoft Learn
2. PDF Files in Github Repo https://github.com/PhilippElhaus/AZ-204/
Prioritize topics per the latest AZ-204 skills outline.

Additional Rules:

- Explain concepts deeper only upon explicit user request without breaking quiz flow.
- Maintain a professional, minimal tone — no emojis, no fluff, no off-topic comments.
```


## Overview

The AZ-204 exam validates skills related to:
- Developing Azure compute solutions
- Managing Azure storage
- Implementing security
- Monitoring and optimizing Azure solutions
- Integrating with third-party and Azure services

## Skills Outline Coverage

### 1. Develop Azure compute solutions (25–30%)

#### 1.1 Implement containerized solutions
- ✅ 1.1.1 Create and manage container images for solutions
- ✅ 1.1.2 Publish an image to Azure Container Registry
- ✅ 1.1.3 Run containers by using Azure Container Instances
- ✅ 1.1.4 Create solutions by using Azure Container Apps

#### 1.2 Implement Azure App Service Web Apps
- ✅ 1.2.1 Create an Azure App Service Web App
- ✅ 1.2.2 Configure and implement diagnostics and logging
- ✅ 1.2.3 Deploy code and containerized solutions
- ✅ 1.2.4 Configure settings including Transport Layer Security (TLS), API settings, and serviceconnections
- ✅ 1.2.5 Implement autoscaling
- ✅ 1.2.6 Configure deployment slots

#### 1.3 Implement Azure Functions
- ✅ 1.3.1 Create and configure an Azure Functions app
- ✅ 1.3.2 Implement input and output bindings
- ✅ 1.3.3 Implement function triggers by using data operations, timers, and webhooks

### 2. Develop for Azure Storage (15–20%)

#### 2.1 Develop solutions that use Azure Cosmos DB
- ✅ 2.1.1 Perform operations on containers and items by using the SDK
- ✅ 2.1.2 Set the appropriate consistency level for operations
- ✅ 2.1.3 Implement change feed notifications

#### 2.2 Develop solutions that use Azure Blob Storage
- ✅ 2.2.1 Set and retrieve properties and metadata
- ✅ 2.2.2 Perform operations on data by using the appropriate SDK
- ✅ 2.2.3 Implement storage policies and data lifecycle management 

### 3. Implement Azure security (15–20%)

#### 3.1 Implement user authentication and authorization
- ✅ 3.1.1 Authenticate and authorize users by using the Microsoft Identity platform
- ✅ 3.1.2 Authenticate and authorize users and apps by using Microsoft Entra ID
- ✅ 3.1.3 Create and implement shared access signatures
- ✅ 3.1.4 Implement solutions that interact with Microsoft Graph

#### 3.2 Implement secure Azure solutions
- ✅ 3.2.1 Secure app configuration data by using App Configuration or Azure Key Vault
- ✅ 3.2.2 Develop code that uses keys, secrets, and certificates stored in Azure Key Vault
- ✅ 3.2.3 Implement Managed Identities for Azure resources

### 4. Monitor and troubleshoot Azure solutions (5–10%)

#### 4.1 Monitor and troubleshoot solutions by using Application Insights
- ✅ 4.1.1 Monitor and analyze metrics, logs, and traces
- ✅ 4.1.2 Implement Application Insights web tests and alerts
- ✅ 4.1.3 Instrument an app or service to use Application Insights

### 5. Connect to and consume Azure services and third-party services (20–25%)

#### 5.1 Implement API Management
- ✅ 5.1.1 Create an Azure API Management instance
- ✅ 5.1.2 Create and document APIs
- ✅ 5.1.3 Configure access to APIs
- ✅ 5.1.4 Implement policies for APIs

#### 5.2 Develop event-based solutions
- ✅ 5.2.1 Implement solutions that use Azure Event Grid
- ✅ 5.2.2 Implement solutions that use Azure Event Hub

#### 5.3 Develop message-based solutions
- ✅ 5.3.1 Implement solutions that use Azure Service Bus
- ✅ 5.3.2 Implement solutions that use Azure Queue Storage queues

## 📚 Resources

- [AZ-204 Certification Overview](https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/)
- [Microsoft Learn: AZ-204 Training Paths](https://learn.microsoft.com/en-us/training/courses/az-204t00/)
- [Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/practice/assessment?assessment-type=practice&assessmentId=35&practice-assessment-type=certification)