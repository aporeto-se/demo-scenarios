# Scenarios for Microsegmentation
## Introduction

The purpose of this repo is to document the demo scenarios for microsegmentation. Each of the demo scenarios follow the pattern of understanding the customer, identifying the use cases and then providing a demo of the future state using Prisma Microsegmentation. 

- CI/CD Automated Workflow
- Discovery Mode Workflow





## CI/CD Automated Workflow

The purpose of this CI/CD Automated workflow is to showcase microsegmentation using Jenkins pipeline. Use this workflow for a customer who is familiar with CI/CD, and would like to use automation to deploy applications and security policies. 

This is the ideal future state of operationalizing microsegmentation. The customer has devops culture and developers are pushing code continuously using  CI/CD workflow. 

Ideally, the security team or the devscops team would like to move at the same speed as the devops team, but if they are using network based controls for microsegmentation, they are the bottleneck for speed. 

The use cases for this workflow are adopting automation, removing the dev/secops discord and security/policy as code vs click button configuration. 



### Demo Application

For this demo, we use the k8s demo app in this git repo (https://github.com/aporeto-se/k8s-simple-apps)



### Prerequisites

<< Document all the Prerequisites here>>>

The demo environment requires a kubernetes cluster, Jenkins setup. 



### Setup/Installation

<< Document the setup here, if this is a canned/in a box demo/existing demo on prisma - how do SE's access it>>



### Demo Steps and Script

<< Document the demo steps, and for each step the script>>



### Slide Deck/Messaging

<< Provide the slides/messaging for the start and the end of the demo>>





## Discovery Mode Workflow

The purpose of this Discovery Mode workflow is to showcase microsegmentation using discovery mode, where we are allowing all the traffic without enforcing the policies. Use this workflow for a customer who is not familiar with the applications, application topology, and would like to observe the network flow before enforcing security policies. 

This is the first step for getting started on the microsegmentation. The customer is either a network architect or security team member, and they are entrusted with creating the east-west microsegmentation. Ideally, the security team or the devscops team would like to move at the same speed as the devops team, but if they are using network based controls for microsegmentation, they are the bottleneck for speed. 

The use cases for this workflow are creating east-west microsegmentation for complex , removing the dev/secops discord and security/policy as code vs click button configuration. 

### Demo Application

For this demo, we use the k8s hipster/shop app in this git repo (<< >>)

### Prerequisites

<< Document all the Prerequisites here>>>

The demo environment requires a kubernetes cluster. 



### Setup/Installation

<< Document the setup here, if this is a canned/in a box demo/existing demo on prisma - how do SE's access it>>



### Demo Steps and Script

<< Document the demo steps, and for each step the script>>



### Slide Deck/Messaging

<< Provide the slides/messaging for the start and the end of the demo>>





