# Enterprise IAM Engineering Portfolio

### Identity & Access Management | Identity Governance | Access Security | IAM Engineering

**Hakan Silitalay**

**Professional Experience:** 5 Years in Identity & Access Management Functions

**GitHub:** https://github.com/silitalayhakan

**Portfolio:** https://github.com/silitalayhakan/enterprise-iam-engineering

---

## Professional Profile

Identity and Access Management professional with approximately five years of hands-on access management experience in a university environment, supporting an access scope of approximately 100 users.

My professional responsibilities included user provisioning and deprovisioning, account administration, password resets, role-based access restrictions, least-privilege enforcement, time-bound access management, activity reviews, and access termination.

My experience also includes working with SQL and Python for reporting and operational analysis.

I combine practical access management experience with technical exposure to enterprise IAM and Identity Governance and Administration (IGA) technologies.

My current technical focus includes Microsoft Entra ID, midPoint, Active Directory, PowerShell automation, identity lifecycle management, access governance, and authentication protocols.

This portfolio documents technical implementations, configuration exercises, architectural analysis, and security controls related to enterprise identity management.

---

## Core IAM Competencies

### Identity Lifecycle Management

- User Provisioning
- User Deprovisioning
- Account Administration
- Access Modification
- Joiner, Mover, Leaver (JML) Processes
- Time-Based Access Management
- Access Termination
- Account Activity Reviews

### Access Control & Security

- Role-Based Access Control (RBAC)
- Least Privilege
- User Access Restrictions
- Access Scope Management
- Account Security
- Password Administration
- Access Review
- Identity Security Controls

### Technical & Operational Skills

- Identity and Access Administration
- SQL Reporting
- Python-Based Reporting
- User Activity Analysis
- Access Documentation
- Operational Access Controls
- Account Lifecycle Procedures

---

## Enterprise IAM Technologies

The following technologies are included in my technical implementation and validation portfolio.

| Technology | Technical Focus |
|------------|-----------------|
| Microsoft Entra ID | Identity Management, RBAC, Conditional Access |
| Microsoft Active Directory | User and Group Administration |
| PowerShell | IAM Automation and Account Management |
| midPoint | Identity Governance and Administration |
| OpenLDAP | Directory Services and Provisioning |
| Auth0 | Authentication, SSO and Federation |
| OAuth 2.0 | Delegated Authorization |
| OpenID Connect | Identity Federation |
| SAML 2.0 | Enterprise Single Sign-On |
| SQL | Identity Data Analysis and Reporting |
| Python | Reporting and Automation |

Enterprise platform experience is documented through individual technical projects and supporting evidence.

---

# IAM Engineering Projects

This repository contains a structured collection of enterprise IAM implementation and validation projects.

Each project documents the technical objective, configuration approach, security considerations, and supporting evidence.

Project documentation and evidence are added as implementations are completed.

---

## 1. IAM Architecture and Stakeholder Mapping

### Objective

Understand and document how enterprise identity systems integrate across HR platforms, identity governance solutions, directories, and authentication services.

### Architecture

```text
HR System
    |
    v
Identity Governance Platform
    |
    |---- Identity Lifecycle
    |---- Provisioning
    |---- Role Management
    |---- Access Reviews
    |---- Audit Records
    |
    v
Enterprise Directory
    |
    v
Applications and Services
```

### Technical Scope

- Identity architecture
- Source-of-truth identification
- Identity lifecycle processes
- Governance responsibilities
- Application access requirements
- Security and audit requirements

### Enterprise Technologies

midPoint, OpenLDAP, Microsoft Entra ID, Active Directory

### Evidence

Architecture diagrams and configuration documentation will be included with the implementation.

---

## 2. HR-Driven Identity Onboarding

### Objective

Implement identity creation processes based on employee information maintained by an authoritative HR source.

### Architecture

```text
SimplifyHR
    |
    v
midPoint
    |
    v
Identity Creation
    |
    v
Target Directory
```

### Technical Scope

- HR source integration
- Identity correlation
- Attribute mapping
- Automated identity creation
- Duplicate identity prevention
- Provisioning validation

### Evidence

Connector configurations, screenshots, and validation results will be documented.

---

## 3. Provisioning to a Target Directory

### Objective

Configure identity provisioning between an IGA platform and a directory service.

### Technical Scope

- midPoint resource configuration
- OpenLDAP integration
- Account attribute mapping
- Role-driven provisioning
- Account creation validation
- Provisioning event analysis

### Architecture

```text
midPoint
    |
    v
Provisioning Connector
    |
    v
OpenLDAP
    |
    v
User Account
```

### Evidence

Resource configurations, provisioning results, and supporting screenshots will be added.

---

## 4. Joiner and Leaver Lifecycle

### Objective

Validate identity lifecycle processes for employee onboarding and termination.

### Joiner Process

```text
New Employee
    |
    v
HR Record Created
    |
    v
Identity Provisioned
    |
    v
Access Assigned
```

### Leaver Process

```text
Employee Termination
    |
    v
HR Status Updated
    |
    v
Identity Lifecycle Process
    |
    v
Access Disabled or Removed
    |
    v
Audit Record
```

### Security Considerations

- Timely access termination
- Prevention of orphaned accounts
- Preservation of required audit records
- Access revocation validation
- Lifecycle event documentation

### Evidence

Joiner and leaver workflow results will be documented.

---

## 5. Role-Based Access Control (RBAC)

### Objective

Implement role-based access assignments aligned with organizational responsibilities.

### Technical Scope

- Role definitions
- Department-based access
- Automatic role assignment
- Manual role requests
- Least-privilege enforcement
- Role assignment validation

### Example

```text
User
 |
 v
Department
 |
 v
Assigned Role
 |
 v
Authorized Resources
```

### Security Focus

Role-based access helps organizations manage permissions consistently and reduce unnecessary privileges.

### Evidence

Role configurations and access validation results will be included.

---

## 6. Mover Lifecycle Management

### Objective

Validate access modifications when employees change departments or responsibilities.

### Process

```text
Department Change
    |
    v
Identity Attribute Updated
    |
    v
Role Recalculation
    |
    v
Previous Access Reviewed
    |
    v
New Access Assigned
```

### Security Considerations

- Excessive access accumulation
- Removal of outdated permissions
- Department-based role changes
- Access reassessment
- Separation of Duties considerations

### Evidence

Before-and-after role assignments and lifecycle validation results will be documented.

---

## 7. Access Request and Approval Workflow

### Objective

Implement controlled access requests requiring authorization before access is granted.

### Process

```text
Access Request
    |
    v
Manager or Application Owner
    |
    v
Approval Decision
    |
    v
Provisioning
    |
    v
Audit Record
```

### Technical Scope

- Access request configuration
- Approval workflow
- Authorization controls
- Provisioning after approval
- Request tracking
- Audit evidence

### Evidence

Workflow configuration and approval validation will be documented.

---

## 8. Access Certification and Identity Governance

### Objective

Implement periodic reviews to determine whether existing access remains appropriate.

### Process

```text
Access Review Campaign
    |
    v
Assigned Reviewer
    |
    v
Access Evaluation
    |
    |---- Approve
    |
    |---- Revoke
    |
    v
Remediation and Audit
```

### Governance Focus

- User access reviews
- Role certification
- Excessive privilege identification
- Access revocation
- Reviewer accountability
- Audit trail documentation

### Evidence

Certification configurations, review decisions, and remediation results will be included.

---

# Authentication and Federation Projects

## 9. OpenID Connect (OIDC) Single Sign-On

### Objective

Configure and validate application authentication through an identity provider using OpenID Connect.

### Technical Scope

- Identity provider configuration
- Application integration
- Authentication flow
- ID token inspection
- Identity claims validation

### Technologies

Auth0, OpenID Connect, OAuth 2.0

### Evidence

Authentication configurations and token validation results will be documented.

---

## 10. OAuth 2.0 Authorization

### Objective

Examine delegated authorization and controlled API access.

### Technical Scope

- Authorization flows
- Access tokens
- API permissions
- OAuth scopes
- Consent
- Token validation

### Security Focus

Understanding how applications obtain limited access to protected resources.

### Evidence

Authorization flow configurations and validation results will be included.

---

## 11. SAML Enterprise Single Sign-On

### Objective

Configure and validate federated authentication between an identity provider and an enterprise application.

### Technical Scope

- Identity Provider (IdP)
- Service Provider (SP)
- SAML assertions
- Signing certificates
- Attribute mapping
- Authentication validation

### Architecture

```text
User
 |
 v
Enterprise Application
 |
 v
Identity Provider
 |
 v
SAML Authentication
 |
 v
Application Access
```

### Evidence

SAML configurations, authentication results, and sanitized assertion details will be documented.

---

## 12. Custom Claims and JWT Security

### Objective

Examine identity claims, token contents, and secure transmission of identity attributes.

### Technical Scope

- JWT structure
- Token claims
- Custom attributes
- Identity metadata
- Token validation
- Sensitive information handling

### Security Focus

Understanding how applications consume identity information and how claims influence access decisions.

### Evidence

Token analysis and configuration examples will be included.

---

# Additional Enterprise IAM Projects

## 13. Microsoft Entra ID and Identity Governance

### Technical Focus

- Microsoft Entra ID administration
- User and group lifecycle management
- Role-Based Access Control
- Conditional Access
- Identity Governance
- Access Reviews
- Privileged Identity Management concepts
- Authentication and authorization controls

### Project Objectives

Configure and validate identity management and governance capabilities in Microsoft Entra ID.

### Evidence

Configuration documentation and technical validation results will be added.

---

## 14. Active Directory and PowerShell Automation

### Technical Focus

- Active Directory user administration
- Group membership management
- PowerShell scripting
- Account provisioning
- Account deprovisioning
- Automated JML processes
- Access reporting

### Project Objectives

Develop repeatable account management procedures and automation scripts for identity lifecycle operations.

### Evidence

PowerShell scripts, test results, and technical documentation will be included.

---

## 15. IAM Audit and Access Controls

### Technical Focus

- Identity Governance Controls
- User Access Reviews
- Privileged Access Reviews
- Access Provisioning Controls
- Access Termination Controls
- Audit Evidence
- Segregation of Duties
- IAM Risk Assessment

### Project Objectives

Evaluate identity management processes from an access control, governance, and audit perspective.

### Security Frameworks

- NIST Cybersecurity Framework
- NIST SP 800-53
- COBIT
- SOX IT General Controls

### Evidence

Control assessments, access review examples, and audit documentation will be added.

---

# Professional Experience

## Identity & Access Management Functions
### University Environment | Approximately 5 Years

Provided operational support for identity and access management functions involving approximately 100 users.

### Key Responsibilities

- Managed user provisioning and deprovisioning activities.
- Supported user account administration.
- Performed password reset operations.
- Applied role-based access restrictions.
- Enforced least-privilege principles within assigned access scopes.
- Managed time-based access requirements.
- Reviewed account activities.
- Removed access at the end of authorized periods.
- Supported access-related reporting using SQL and Python.
- Maintained operational oversight of user access requirements.

### Experience Highlights

**Identity Lifecycle:** Account creation, modification, and access termination.

**Access Administration:** User permissions, access restrictions, and password management.

**Security Controls:** Least privilege, authorization boundaries, and time-based access.

**Operational Analysis:** Account activity reviews and reporting.

This experience provides a practical foundation for enterprise IAM engineering, identity governance, and access security responsibilities.

---

# Technical Documentation and Evidence

Each implementation project may include:

- Architecture diagrams
- Configuration screenshots
- Technical documentation
- PowerShell scripts
- Identity lifecycle workflows
- Access control configurations
- Validation results
- Security observations
- Audit evidence examples

Sensitive information, credentials, and production data are excluded from public documentation.

---

# Professional Focus

My professional focus is on enterprise Identity and Access Management, combining operational access management experience with technical implementation and identity governance capabilities.

Areas of particular interest include:

- IAM Engineering
- Identity Governance and Administration
- Identity Lifecycle Automation
- Microsoft Entra ID
- Active Directory
- Access Provisioning
- IAM Security Controls
- Identity Governance and Audit

---

# Contact

**Hakan Silitalay**

**GitHub:** https://github.com/silitalayhakan

**Portfolio:** https://github.com/silitalayhakan/enterprise-iam-engineering

---

*Enterprise IAM Engineering | Identity Governance | Access Security*
