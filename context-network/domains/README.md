# Domain-Specific Information

This directory contains domain-specific information organized by domain. Each domain has its own subdirectory with relevant documentation.

## Adding a New Domain

To add a new domain:

1. Create a new subdirectory with the domain name (e.g., `frontend`, `backend`, `data`, etc.)
2. Create an `overview.md` file in the domain directory that follows the standard information node template
3. Add domain-specific documentation files as needed
4. Update relationships in existing documents to reference the new domain

## Domain Structure

Each domain directory should follow this structure:

```
domains/
├── [domain-name]/
│   ├── overview.md              # Overview of the domain
│   ├── architecture.md          # Domain-specific architecture
│   ├── interfaces.md            # Domain interfaces
│   ├── components/              # Documentation for domain components
│   │   ├── [component-1].md
│   │   ├── [component-2].md
│   │   └── ...
│   └── processes/               # Domain-specific processes
│       ├── [process-1].md
│       ├── [process-2].md
│       └── ...
```

## Domain Overview Template

Use this template for the `overview.md` file in each domain:

```markdown
# [Domain Name] Overview

## Purpose
This document provides an overview of the [Domain Name] domain, including its scope, responsibilities, and key components.

## Classification
- **Domain:** [Domain Name]
- **Stability:** [Static/Semi-stable/Dynamic]
- **Abstraction:** [Conceptual/Structural/Detailed]
- **Confidence:** [Established/Evolving/Speculative]

## Content

### Domain Scope

[Describe the scope of this domain]

### Key Responsibilities

[List and describe the key responsibilities of this domain]

### Components

[List and describe the key components in this domain]

### Interfaces

[Describe the interfaces this domain exposes and consumes]

### Domain-Specific Patterns

[Describe any patterns specific to this domain]

## Relationships
- **Parent Nodes:** [foundation/architecture.md]
- **Child Nodes:** [List of child nodes]
- **Related Nodes:** [List of related nodes]

## Navigation Guidance
- **Access Context:** [When to use this information]
- **Common Next Steps:** [Typical navigation paths from here]
- **Related Tasks:** [Activities where this information is relevant]
- **Update Patterns:** [How and when this information changes]

## Metadata
- **Created:** [Date]
- **Last Updated:** [Date]
- **Updated By:** [Agent ID/Task]

## Change History
- [Date]: [Brief description of changes]
