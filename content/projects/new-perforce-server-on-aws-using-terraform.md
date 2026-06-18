---
title: "New Perforce Server on AWS Using Terraform"
draft: false
tags: ["Infrastructure as Code", "Infrastructure", "Cloud", "AWS", "Perforce"]

description: "Terraform configuration that provisions a fully functional Perforce (P4) server on AWS."
---

**Source: [nightclucker/perforce-server-on-aws](https://github.com/nightclucker/perforce-server-on-aws)**

[Overview](#overview) | [Tech Stack](#tech-stack) | [Intended Workflow](#intended-workflow) | [Implementation](#implementation) | [Issues Faced](#issues-faced) | [Takeaway](#takeaway)

## Overview

This project uses Terraform to provision a fully functional Perforce (P4) server on AWS. It replaces the original Perforce CloudFormation‑based deployment with a modern, modular Terraform implementation, enabling consistent, repeatable, and automated P4 server creation in the cloud.

### Problem Statement

Can I use terraform to provision new Perforce servers?

## Tech Stack

Here's a list of tools and technologies that was used in the construction of this pipeline.

| **Category** | **Technology/Tool** |
| :--- | :--- |
| *Source Control* | Git, GitHub |
| *IDE* | VS Code |
| *Infrastructure* | AWS, Terraform, Terraform Cloud (tfcloud) |
| *AI* | Co-Pilot |

## Intended Workflow

All work is done on the main branch.  Developers write and iterate on Terraform configurations locally, validate with `terraform plan`, and push to GitHub.  When ready to provision, the developer triggers a run in Terraform Cloud which automatically plans and applies the changes.

**Steps:**

1. **Development** — Write or update the Terraform configuration locally.  This includes the full AWS stack: VPC, subnets, security groups, EBS volumes, and the EC2 instance itself.
2. **Local Validation** — Run `terraform plan` locally to catch syntax errors, misconfigurations, and review what resources will be created, modified, or destroyed before pushing any changes.
3. **Push to GitHub** — Once the plan looks correct, commit and push the changes to the main branch on GitHub.
4. **Update Variables (if needed)** — If any tags, keys, or other environment-specific values need to change, update the secret variables in Terraform Cloud.  This is how sensitive values like the instance key are injected into the Terraform run without being stored in source control.
5. **Trigger Run in Terraform Cloud** — When ready to provision, manually trigger a new run from Terraform Cloud.  The run automatically executes a plan and apply in sequence, provisioning or updating the AWS infrastructure.

## Implementation

...

---

## Issues Faced

This may be a simple project but I did face a few issues and bugs that I had to figure out.

---

## Takeaway

...

[Back to Top](#overview)
