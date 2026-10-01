# hprofile — Historical Java/DevOps Training Project

> **Status:** Archived / historical learning project. This repository is retained for provenance and engineering reference; it is not an actively maintained production application.

The Maven metadata identifies the application as **Visualpathit VProfile Webapp** (`com.visualpathit:vprofile`). This repository is therefore retained as a training/reference implementation rather than presented as an original commercial product.

## What it demonstrates

- Java/Spring MVC and Spring Security
- Spring Data JPA / Hibernate
- MySQL-backed application architecture
- RabbitMQ, Memcached and Elasticsearch integration concepts
- Maven/Jetty build tooling
- Jenkins pipeline automation
- Docker and Ansible deployment experiments
- AWS-oriented infrastructure/deployment material

## Historical stack

The application targets Java 8-era tooling and includes substantially older framework/dependency versions, including Spring 4.x, Hibernate 4.x, Elasticsearch 5.x and JUnit 4. It should not be used as a current production baseline without a deliberate redesign and security/dependency review.

## Archive hygiene

A committed database dump was removed from the current tree during archival cleanup, and generated/local artefacts are now ignored. The repository may still contain those removed files in older Git history.

The checked-in `target/` directory is historical build output and is retained only as part of the repository record; future generated build output is ignored.

## Archive policy

No feature development is planned here. If a deployment or DevOps pattern remains useful, migrate the specific concept into an actively maintained repository rather than reviving this application wholesale.

Archiving this repository does not imply that its code, dependencies or deployment configuration reflect current engineering or security standards.
