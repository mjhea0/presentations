# Running Django on Kubernetes

## Submitted by

Michael Herman

## Description

Kubernetes is a powerful open source container orchestration tool that allows you to quickly deploy containerized applications.

In this tutorial, we’ll first take a look at Kubernetes and container orchestration in general and then we’ll walk through deploying a Django RESTful API to a Kubernetes cluster.

## Audience

This is an intermediate-level tutorial geared toward those that have experience with Django, Django Rest Framework, and Docker.

## Objectives

By the end of this tutorial, you will be able to...

1. Explain what container orchestration is and why you may need to use an orchestration tool
2. Discuss the pros and cons of using Kubernetes over other orchestration tools like Docker Swarm and Elastic Container Service (ECS)
3. Explain the following Kubernetes primitives - Node, Pod, Service, Label, Deployment, Ingress, and Volume
4. Spin up Django-based microservice locally with Docker Compose
5. Configure a Kubernetes cluster to run on Digital Ocean
6. Set up a volume to hold Postgres data within a Kubernetes cluster
7. Use Kubernetes Secrets to manage sensitive information
8. Run Django, Gunicorn, and Postgres on Kubernetes
9. Expose the DRF Restful endpoints to external users via a Load Balancer

## Outline

Introduction and Theory (20 minutes - (100% lecture))

1. About Me
2. Objectives
3. What is Container Orchestration?
4. Kubernetes Concepts

Digital Ocean Setup and Deployment (1.5 hours (100% hands-on))

1. Kubernetes Cluster
2. Docker Registry
3. Django Deployment
4. Secrets
5. Volume
6. Postgres Setup


Additional Challenges (1 hours (100% hands-on))

1. Static Assets
2. Transactional Emails
3. Batch processing

What's next? (10 minutes)

1. Next Steps
2. Questions

## Additional notes

A few things...

1. This tutorial comes from a modified version of the course at http://testdriven.io/
2. You can see my past speaking history at http://mherman.org/talks (I spoke at PyTennessee, PyCon, and DockerCon in 2018)
3. I run the NodeJS Meetup in the Denver + Boulder area - https://www.meetup.com/Node-js-Denver-Boulder/
4. I am a former lead web development instructor for Galvanize, where I taught full-stack JavaScript
