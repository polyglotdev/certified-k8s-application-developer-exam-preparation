# Certified Kubernetes Application Developer (CKAD) Exam Preparation

[Course Link](https://dominiquehallan-links.com/4eDHxnn)

[[TOC]]

## Learning Objectives

- Understand what you will learn in the CKAD Exam Preparation course
- Understand who should take the CKAD Exam Preparation course
- Understand the course prerequisites
- Understand what CKAD exam domains are covered by each piece of content in the course

## CKAD Exam Preparation Course Overview

The CKAD exam is a practical exam

The exam tests your ability to work with live Kubernetes clusters and covers Kubernetes skills in the following domains:

- Application Design and Build
- Application Deployment
- Application Observability and Maintenance
- Application Environment, Configuration, and Security
- Services and Networking

## Overview of Intro to Kubernetes

- Kubernetes
  - Overview
    - What is it?
    - Why is it successful?
    - How you can start
    - Deploying Containerized Applications
  - Hands on
    - Deploy Microservices
    - [Github Link](https://dominiquehallan-links.com/3VZCO8q)
  - Intro to Kubernetes Lab
  - Personal Topics to Introduce

## Learning Objectives

- [ ] Describe Kubernetes and what it's used for
- [ ] Deploy single and multi-container
applications
- [ ] Kubernetes Services
- [ ] Manage Application Deployments and
Rollouts
- [ ] Ensure container preconditions are met and
keep containers healthy
- [ ] Manage configuration maps, secrets, and
how to control persistent data
- [ ] Discuss the popular tools


## Introduction to Kubernetes

Kubernetes is an open-source platform designed to automate deploying, scaling, and operating application containers. It groups containers that make up an application into logical units for easy management and discovery.

## Kubernetes Overview

- Open-source container orchestration tool designed to automate, deploying, scaling, and operating containerized applications
- Born out of Google's experience running production workloads at scale
- Allows organizations to increase their velocity by releasing and recovering faster

## More on Kubernetes

- Kubernetes is a distributed system
- Machines may be physical, virtual, on-prem, or in the cloud
- Schedules containers on machines
- Moves containers as machines are added/removed
- Can use different container runtimes
- Modular, extensible design

## Using Kubernetes

- Declarative Configuration
- Deploy Containers
- Wire up networking
- Scale and Expose Services

## Kubernetes for Operations

- Automatically recover from machine failure
- Replace and reschedule containers
- Built in support for maintenance
- Join clusters with federation

## Kubernetes Feature Highlights

- Automated deployment rollout and rollback
- Seamless horizontal scaling
- Secret management
- Service discovery and load balancing
- Linux and Windows container support
- Simple log collection
- Stateful application support
- Self-healing
- Persistent Volume management
- CPU and memory quotas
- Batch job processing
- Role-based access control

## Container Orchestration Landscape

- There has been a surge in tools to support enterprises adopting containers in production
- We will compare Kubernetes with other tools to get a better understanding
- Compare to: DCOS, Amazon ECS, and Docker swarm mode

## DCOS

- Distributed Cloud Operating System
- Pools compute resources into a uniform task pool
- Supports many different types of workloads
- Attractive to organizations not only using containers
- Includes package manager to easily deploy popular systems
- Can even run Kubernetes on DC/OS
- [DC/OS](https://dcos.io/)

## Amazon ECS

- Elastic Container Service
- AWS first entry in container orchestration
- Create pools of compute resources
- API calls to orchestrate containers
- EC2 compute instance managed by you or AWS Fargate
- Only available on AWS
- Useful if you are deep in the AWS ecosystem
- [Amazon ECS](https://aws.amazon.com/ecs/)

## Docker Swarm Mode

- Docker's native clustering tool
- Builds a cluster from multiple docker hosts
- Works with Docker Compose command
- Enterprise features available
- Docker also provides full suport of K8's

## Deploying Kubernetes
