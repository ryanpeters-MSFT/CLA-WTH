# What The Hack - AKS Enterprise-Grade

## Introduction

The objective of this hack is to dive deeply into all aspects of integration between Kubernetes, the Azure Kubernetes Service (AKS), and various Azure services. We have included challenges for many components that are required to operate a Kubernetes cluster on Azure (eg: networking, storage, etc)

## Learning Objectives

In this hack you will start by deploying a 3-tier application to AKS with very specific networking requirements.

The challenges progress through networking, monitoring, secrets management, and security, with an optional service mesh challenge to further protect application traffic.

## Challenges

- Challenge 00: **[Prerequisites - Ready, Set, GO!](Student/00-setup.md)**
	 - Prepare your workstation to work with Azure.
- Challenge 01: **[Containers](Student/01-containers.md)**
	 - Get familiar with the sample application for this hack, and roll it out locally or with Azure Container Instances
- Challenge 02: **[AKS Network Integration and Private Clusters](Student/02-networking.md)**
	 - Deploy the application in an AKS cluster with strict network requirements
- Challenge 03: **[AKS Monitoring](Student/03-monitoring.md)**
	 - Monitor the application, either using Prometheus or Azure Monitor
- Challenge 04: **[Secrets and Configuration Management](Student/04-secrets.md)**
	 - Harden secret management with the help of Azure Key Vault
- Challenge 05: **[AKS Security](Student/05-security.md)**
	 - Explore AKS security concepts such as Azure Policy for Kubernetes
- Challenge 07: **[Service Mesh (Optional)](Student/07-mesh.md)**
	 - Explore the usage of a Service Mesh to further protect the application

## Prerequisites

- Access to an Azure subscription (owner privilege is required in some exercises)
- Visual Studio Code
- Windows Subsystem for Linux (Windows-only)
- Azure CLI
- Docker Desktop (Optional)

## Contributors

- Adrian Joian
- Gitte Vermeiren
- Jose Moreno
- Victor Viriya-ampanond
- Peter Laudati
- Pete Rodriguez
