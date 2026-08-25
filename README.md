# Gideon Dakore

Backend engineer in Kumasi, Ghana. I build APIs and services in **Java/Spring Boot** and **NestJS**, and run them on **AWS**.

📫 [dakoregideon72@gmail.com](mailto:dakoregideon72@gmail.com) · [LinkedIn](https://www.linkedin.com/in/gideon-dakore)

---

## What I work on

**Identity and authentication** — Built the management console for a multi-domain supply chain platform, acting as its identity provider and single source of truth for user accounts. Four domain applications authenticate through an OIDC-style flow: tokens signed with a private key, public key published at a JWKS endpoint, so each service verifies locally without shared secrets or a callback on every request.

**Real-time systems** — Real-time messaging service in NestJS using Socket.io with the Redis adapter, so socket state is shared across instances and the service scales horizontally. Idempotent delivery via client-supplied message identifiers, which matters when mobile clients retry on flaky connections.

**Cloud and networking** — Spring Boot services deployed across EC2, Application Load Balancer, and Auto Scaling Groups, shipped through Jenkins pipelines gated by SonarQube. Designed an identity-aware VPN architecture for remote access using OpenVPN with an easy-rsa PKI, per-client configuration directives, and iptables routing.

---

## Stack

**Languages** Java · TypeScript · JavaScript · Python · SQL · Bash

**Backend** Spring Boot · NestJS · Node.js · Express · JPA/Hibernate · Prisma · JUnit

**Cloud & DevOps** AWS (EC2, ALB, Auto Scaling, Lambda, IAM, VPC, ECR, CloudFormation) · Docker · Jenkins · SonarQube · Linux

**Data** PostgreSQL · MySQL · MongoDB · Redis

**Also** React · Next.js · Flutter

<img src="https://skillicons.dev/icons?i=java,spring,ts,nestjs,nodejs,python,postgres,redis,aws,docker,jenkins,linux" />

---

## Currently

Studying for **AWS Certified Developer – Associate**. Interested in distributed systems, event-driven architecture, and the security layer underneath both — PKI, TLS, token design.

I read source and specs before reaching for a tutorial. Most of what I learn comes from taking something apart to find out why it works the way it does.
