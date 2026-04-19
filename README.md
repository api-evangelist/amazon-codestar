# Amazon CodeStar (amazon-codestar)
AWS CodeStar provides a unified user interface enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire continuous delivery toolchain in minutes, allowing you to create and manage projects, add team members with role-based access control, and integrate with other AWS developer tools including CodeCommit, CodeBuild, CodeDeploy, and CodePipeline.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Developer Tools, DevOps, Project Management, Team Collaboration

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### AWS CodeStar API
The AWS CodeStar API provides a unified interface for managing software development activities in one place. It enables you to quickly set up continuous delivery toolchains, create and manage projects, add team members with role-based access, and integrate with other AWS developer tools.

**Human URL:** [https://aws.amazon.com/codestar/](https://aws.amazon.com/codestar/)

#### Tags:

 - AWS, Developer Tools, DevOps, Project Management, Team Collaboration

#### Properties

- [Documentation](https://docs.aws.amazon.com/codestar/)
- [OpenAPI](openapi/amazon-codestar-openapi.yml)
- [Pricing](https://aws.amazon.com/codestar/pricing/)
- [GettingStarted](https://aws.amazon.com/codestar/getting-started/)
- [FAQ](https://aws.amazon.com/codestar/faqs/)
- [JSONSchema](json-schema/codestar-openapi-project-schema.json)
- [JSONStructure](json-structure/codestar-openapi-project-structure.json)
- [JSON-LD](json-ld/amazon-codestar-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/codestar/)
- [Documentation](https://docs.aws.amazon.com/codestar/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/codestar/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Project Creation from Templates | Create projects from pre-built templates that automatically provision AWS resources including CodeCommit repositories, CodeBuild build projects, and CodePipeline pipelines. |
| Team Management with Role-Based Access | Add team members with Owner, Viewer, or Contributor roles, integrating directly with AWS IAM for secure access control. |
| Integrated Developer Toolchain | Automatically connects CodeCommit, CodeBuild, CodeDeploy, and CodePipeline into a unified continuous delivery pipeline. |
| Project Resource Dashboard | Unified dashboard to view and manage all AWS resources associated with a project. |
| User Profile Management | Cross-project user profiles storing display names, email addresses, and SSH public keys. |
| Project Tagging | Tag projects with key-value pairs for resource organization, cost allocation, and filtering. |

## Use Cases

| Name | Description |
|------|-------------|
| CI/CD Pipeline Setup | Rapidly provision a complete continuous integration and delivery pipeline for application development teams. |
| Team Onboarding | Quickly add new developers to project teams with appropriate role-based permissions across all project resources. |
| Multi-Project Management | Manage multiple software development projects from a single interface with centralized team and resource visibility. |
| Developer Collaboration | Enable distributed development teams to collaborate on AWS-hosted projects with shared toolchains and access controls. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodeCommit | Source control integration for hosting Git repositories within CodeStar projects. |
| AWS CodeBuild | Build service integration for compiling source code and running tests in CodeStar projects. |
| AWS CodeDeploy | Deployment automation integration for deploying applications to AWS resources. |
| AWS CodePipeline | CI/CD orchestration integration for automating build, test, and deployment pipelines. |
| AWS IAM | Identity and access management integration for team member authentication and authorization. |
| AWS CloudFormation | Infrastructure provisioning integration for creating and managing project AWS resources. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS CodeStar OpenAPI](openapi/amazon-codestar-openapi.yml)

### JSON Schema

92 schema files extracted from the OpenAPI specification covering all request/response models.

### JSON Structure

92 JSON Structure files converted from JSON Schema using the json-structure.org specification.

### JSON-LD

- [Amazon CodeStar Context](json-ld/amazon-codestar-context.jsonld)

### Examples

92 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AWS CodeStar API](capabilities/shared/codestar.yaml) — 18 operations for project management, team collaboration, and user profiles

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeStar Project Management](capabilities/project-management.yaml) | AWS CodeStar API | 12 | Development Team Lead, Platform Administrator |

## Vocabulary

- [Amazon CodeStar Vocabulary](vocabulary/amazon-codestar-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 9 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon CodeStar Spectral Rules](rules/amazon-codestar-spectral-rules.yml) — 25 rules across 13 categories enforcing Amazon CodeStar API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
