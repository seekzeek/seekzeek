# Hey, I'm Isaac 👋

**Senior Software Engineer**

I build products people rely on, and the systems that keep them running.

Over 7 years I've designed and shipped web, mobile, and backend products for millions of users, across fintech, trading, automotive, logistics, e-commerce, and blockchain. I take end-to-end ownership: from architecture and code to cloud infrastructure, CI/CD, and automation.

I'm now focused on platform engineering and DevOps: designing and operating the self-service infrastructure and golden paths that let teams ship reliably.

---

## What I'm building

### [fleetctl](https://github.com/seekzeek/fleetctl)
I design and operate self-managed Kubernetes clusters where everything, from the machine image to the running workload, is defined in code.

- **How it's built:** Packer bakes the node images, Terraform provisions the infrastructure, Ansible bootstraps the control plane, and ArgoCD deploys everything else through GitOps.
- **Faster worker provisioning:** Reduced from 12 minutes to 65 seconds by baking images instead of configuring nodes at boot. New workers join automatically when the Auto Scaling Group launches them.
- **Secrets management:** External Secrets Operator syncs secrets from AWS SSM Parameter Store into the cluster at runtime, so nothing sensitive lives in Git or in a manifest. Swapping in Secrets Manager or another backend is a config change.
- **Access & observability:** Keycloak and oauth2-proxy for single sign-on. Prometheus and Grafana for monitoring.

---

## Writing

I write about platform engineering, Kubernetes, GitOps, and Terraform: how the pieces actually fit together, and what breaks when they don't.

<!-- BLOG-POST-LIST:START -->
- [Enterprise GitOps at Scale: Build, Package, Configure, Deploy](https://medium.com/@ukatanetech/enterprise-gitops-at-scale-build-package-configure-deploy-3e7a350c3b2f?source=rss-b7f0b3648ba4------2)
- [Centralizing Authentication and Identity in Kubernetes with Keycloak: Setup and Core Concept](https://medium.com/@ukatanetech/centralizing-authentication-and-identity-in-kubernetes-with-keycloak-setup-and-core-concept-3a78d0c4d395?source=rss-b7f0b3648ba4------2)
- [3 Patterns for Kubernetes TLS: Why I Settled on NLB Passthrough and cert-manager](https://medium.com/@ukatanetech/3-patterns-for-kubernetes-tls-why-i-settled-on-nlb-passthrough-and-cert-manager-78931b2d5271?source=rss-b7f0b3648ba4------2)
- [Calico BGP: Resolving “BIRD Not Ready” and Node Readiness Failures](https://medium.com/@ukatanetech/calico-bgp-resolving-bird-not-ready-and-node-readiness-failures-e582ab2dca3c?source=rss-b7f0b3648ba4------2)
- [Build a Production-Grade Kubernetes Homelab with kubeadm](https://medium.com/@ukatanetech/build-a-production-grade-kubernetes-homelab-with-kubeadm-d561a4fbf1c8?source=rss-b7f0b3648ba4------2)
<!-- BLOG-POST-LIST:END -->

More on [Medium](https://medium.com/@ukatanetech)

---

## Skills

**Languages & Frameworks:** TypeScript · JavaScript · Python · SQL · Node.js · React · React Native · Next.js · GraphQL

**Databases:** PostgreSQL · MongoDB · Microsoft SQL Server (MSSQL)

**Cloud:** AWS (EC2, ECS, EKS, Lambda, S3, IAM, VPC, SQS, ASG, CloudWatch) · DigitalOcean · Linux

**IaC & Configuration Management:** Terraform · Packer · Ansible

**Kubernetes & GitOps:** Kubernetes (K8s) · managed (EKS) and self-managed (kubeadm) · ArgoCD · Argo Rollouts · Helm · Docker

**CI/CD & Observability:** GitHub Actions · GitLab CI/CD · AWS CodePipeline · Prometheus · Grafana · Sentry

---

## Let's talk

Open to conversations about platform engineering, Kubernetes, and reliability.

[LinkedIn](https://linkedin.com/in/ukatane-zeek) · [Medium](https://medium.com/@ukatanetech) · isaac@ukatane.com
