# Hosting

* Status: Proposed
* Deciders: Habib Ullah, Casey Cheung, Rami Kotaiche
* Date: 2024-10-14

Technical Story: The hosting solution must handle variable user loads efficiently, provide high availability, and support disaster recovery.

## Context and Problem Statement

The system must be scalable to handle simultaneous requests from users across web, phone, and in-branch platforms.

## Considered Options

* AWS Cloud
* Google Cloud Platform (GCP)
* On-Premises Hosting

## Decision Outcome

Chosen option: "AWS Cloud", because Why did we choose option

### Positive Consequences

* Highly scalable and supports global deployment.
- Offers extensive managed services for databases, authentication, etc.
- Pay-as-you-go model optimizes costs.

### Negative Consequences

* Dependence on a single cloud provider can lead to vendor lock-in.
- Initial learning curve for configuring AWS services efficiently.

## Pros and Cons of the Options

### AWS Cloud

Option1 Description

* Good, because Comprehensive service offerings and global infrastructure.
* Bad, because Vendor lock-in risk.

### Google Cloud Platform

Option2 Description

* Good, because Strong AI/ML integrations.
* Bad, because Smaller ecosystem compared to AWS.

### On-Premises Hosting

* Good, because Full control over infrastructure.
* Bad, because High initial setup and maintenance costs.
