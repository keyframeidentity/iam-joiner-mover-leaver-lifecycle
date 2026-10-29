# Joiner-Mover-Leaver (JML) Identity Lifecycle Management

## Project Overview

This project demonstrates Identity and Access Management (IAM) practices for managing employee identities throughout the employment lifecycle: onboarding (Joiner), role or department changes (Mover), and offboarding (Leaver).

The project uses a fictional organization and a hands-on lab environment to demonstrate identity lifecycle workflows, role-based access control (RBAC), least privilege, and hybrid identity concepts using Microsoft Active Directory and Microsoft Entra ID.

Developed as part of the **Keyframe Identity** IAM portfolio.

## Objectives

- Implement structured joiner, mover, and leaver workflows.
- Organize users and access using Active Directory organizational units and security groups.
- Apply role-based access control and least-privilege principles.
- Document approval steps, access changes, and audit evidence.
- Explore synchronization between on-premises Active Directory and Microsoft Entra ID.
- Develop repeatable procedures for secure identity lifecycle management.

## Planned Lab Environment

- Windows Server with Active Directory Domain Services
- Windows 11 client
- Microsoft Entra ID
- Active Directory users, organizational units, and security groups
- Hybrid identity synchronization, subject to tenant eligibility and licensing

## Project Scenarios

### 1. Joiner — Employee Onboarding
Create a fictional employee account, assign the correct organizational unit and security groups, and document the access granted.

### 2. Mover — Department or Role Change
Update an employee's role, review existing permissions, remove access that is no longer required, and assign the new role's access.

### 3. Leaver — Employee Offboarding
Disable the employee account, document access removal and verification, and record the actions taken.

## Security Principles

- Least privilege
- Role-based access control
- Separation of duties where appropriate
- Approval and verification of access changes
- Auditability and documentation
- Secure handling of credentials and lab data

## Project Status

**Status:** Initial setup and documentation

The project will be expanded with implementation steps, workflow diagrams, test cases, and sanitized evidence as the lab is developed.

## Disclaimer

This is an educational portfolio project using a
