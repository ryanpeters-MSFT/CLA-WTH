<!-- {% comment %} -->
# What The Hack - Repo

Welcome to the What The Hack repo on GitHub. This repo contains Coach content designed for people planning to host a What The Hack event with students in an organization. 

If you are an organization that is interested in attending or hosting a What The Hack event, please visit the [What The Hack website](https://aka.ms/wth) at: **https://aka.ms/wth**

**If you are a student attending a What The Hack event, please go to the [What The Hack website](https://aka.ms/wth).**

![What The Hack Website](/assets/images/wth-logo.png)
<!-- {% endcomment %} -->

# What is a "What The Hack"?

"What the Hack" is a set of challenge based hackathons that can be hosted in-person or virtually via Microsoft Teams.

Attendees work in squads of 3 to 5 people to solve a series of technical challenges for a given technology or solution scenario. Challenges describe high-level tasks and goals to be accomplished. Challenges are not step-by-step labs.

What The Hack is designed to be a collaborative learning experience.  Attendees "learn from" and "share with" each other. Without step-by-step instructions given for the challenges, attendees have to "figure it out" together as a team.  This results in greater knowledge retention for the attendees. 

The attendee squads are not alone in solving the challenges. Coaches work with each squad to provide guidance for, but not answers to, the challenges.  The coaches may also provide lectures and demos to introduce the challenges, as well as review challenge solutions throughout the event.

# About These Hacks

These challenges have been specially developed for Clifton Larson Allen and consist of the following challenges over the next two days:


- [Advanced Kubernetes](#advanced-kubernetes)
- [AKS Enterprise-Grade](#aks-enterprise-grade)

## Advanced Kubernetes

[Explore the hack](023-AdvancedKubernetes/README.md). Independent challenges covering advanced Kubernetes features and day-two operational practices; teams can prioritize the topics most relevant to them.

| Challenge | Description |
| --- | --- |
| [01: Setup](023-AdvancedKubernetes/Student/01-setup.md) | Prepare the tools, container registry, and AKS cluster with system and user node pools. |
| [02: Helm](023-AdvancedKubernetes/Student/02-helm.md) | Create and deploy a Helm chart, then expose the application using managed Istio application routing and Gateway API. |
| [03: Resiliency](023-AdvancedKubernetes/Student/03-resiliency.md) | Configure readiness and liveness probes, then simulate failures to test application recovery. |
| [04: Scaling](023-AdvancedKubernetes/Student/04-scaling.md) | Configure resource requests, limits, and pod and cluster autoscaling, then validate scaling under load. |
| [05: GitOps](023-AdvancedKubernetes/Student/05-gitops.md) | Use Flux or Argo CD to synchronize Kubernetes deployments with configuration stored in GitHub. |

## AKS Enterprise-Grade

[Explore the hack](039-AKSEnterpriseGrade/README.md). Deploy and harden a three-tier application while exploring AKS networking, monitoring, security, and an optional service mesh challenge.

| Challenge | Description |
| --- | --- |
| [00: Prerequisites](039-AKSEnterpriseGrade/Student/00-setup.md) | Prepare your workstation and Azure tooling for the challenges. |
| [01: Containers](039-AKSEnterpriseGrade/Student/01-containers.md) | Build and publish the sample application's container images, then run it locally or with Azure Container Instances. |
| [02: AKS Network Integration and Private Clusters](039-AKSEnterpriseGrade/Student/02-networking.md) | Deploy the three-tier application to AKS with network isolation, private endpoints, and managed Istio ingress. |
| [03: AKS Monitoring](039-AKSEnterpriseGrade/Student/03-monitoring.md) | Monitor the cluster and application with Azure Monitor and Application Insights, and validate autoscaling. |
| [04: Secrets and Configuration Management](039-AKSEnterpriseGrade/Student/04-secrets.md) | Manage application settings with ConfigMaps and protect secrets using Azure Key Vault. |
| [05: AKS Security](039-AKSEnterpriseGrade/Student/05-security.md) | Harden the application and cluster with network policies, node pool isolation, TLS ingress, and identity-based access. |
| [07: Service Mesh (Optional)](039-AKSEnterpriseGrade/Student/07-mesh.md) | Use a service mesh to encrypt traffic between the application's ingress, web, and API components. |

# Using GitHub Codespaces

GitHub Codespaces provides a cloud-hosted development environment with the tools for these labs already configured. Launch your codespace from the [main CLA-WTH GitHub repository](https://github.com/ryanpeters-MSFT/CLA-WTH).

1. In the repository, select **Code**, then the **Codespaces** tab.
2. Open the **…** menu and select **New with options...** so you can choose the correct lab configuration.
3. Under **Dev container configuration**, select the configuration for the lab you are working on:
	- **023-AdvancedKubernetes** for the Advanced Kubernetes challenges.
	- **039-AKSEnterpriseGrade** for the AKS Enterprise-Grade challenges.
4. Review the remaining options and select **Create codespace**.

Once the environment is ready, it opens a **Visual Studio Code IDE in your browser**, where you can edit files and run commands in the integrated terminal.

## Work in Desktop Visual Studio Code

You can also connect to the same codespace from the desktop version of VS Code. In the browser IDE, open the Command Palette (**Ctrl+Shift+P** on Windows or **Cmd+Shift+P** on macOS) and select **Codespaces: Open in VS Code**. Follow any prompts to install the GitHub Codespaces extension and sign in to GitHub. Your files and tools remain in the cloud-hosted codespace; only the editor runs locally.

When you finish working, stop the codespace from the [GitHub Codespaces page](https://github.com/codespaces) to avoid unnecessary compute usage.

# License
This repository is licensed under MIT license. More info can be found [here](https://github.com/Microsoft/WhatTheHack/blob/master/LICENSE).
