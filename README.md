# EKS Production Platform Demo

## Overview

This project demonstrates a production-style Kubernetes platform on Amazon EKS using GitOps, ArgoCD, External Secrets Operator, AWS Load Balancer Controller, IRSA, and GitHub Actions.

## Architecture

Developer  
↓  
GitHub  
↓  
GitHub Actions  
↓  
Amazon ECR  
↓  
ArgoCD  
↓  
Amazon EKS  
↓  
AWS ALB  
↓  
Application Pods

## Features

- Amazon EKS
    
- ArgoCD GitOps
    
- External Secrets Operator
    
- AWS Secrets Manager
    
- IRSA
    
- AWS Load Balancer Controller
    
- Cluster Autoscaler
    
- GitHub Actions CI/CD
    

## Components

### Application

Flask application containerized using Docker.

### GitOps

ArgoCD continuously synchronizes Kubernetes resources from GitHub.

### Secrets Management

Secrets are stored in AWS Secrets Manager and synchronized using External Secrets Operator.

### Ingress

AWS Application Load Balancer exposes the application externally.

### Autoscaling

Cluster Autoscaler dynamically adjusts worker node count based on scheduling requirements.

## Skills Demonstrated

- Kubernetes Administration
    
- Amazon EKS
    
- GitOps
    
- ArgoCD
    
- IRSA
    
- External Secrets
    
- AWS Networking
    
- CI/CD Pipelines
    
- Docker
    
- GitHub Actions