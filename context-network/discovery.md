# Context Network Navigation Guide

## Overview

This context network contains all planning documents, architectural decisions, and team coordination information for the project. It is organized into several key sections to facilitate navigation and information discovery.

## Structure

The context network is organized as follows:

```
context-network/
├── discovery.md                # This navigation guide
├── foundation/                 # Core project information
│   ├── project_definition.md   # Main project purpose and goals
│   ├── architecture.md         # System architecture overview
│   └── principles.md           # Guiding principles and standards
├── domains/                    # Domain-specific information
│   └── [domain-specific folders and files]
├── processes/                  # Process documentation
│   ├── development.md          # Development workflows
│   ├── testing.md              # Testing procedures
│   ├── deployment.md           # Deployment processes
│   └── document_integration.md # Process for integrating inbox documents
├── decisions/                  # Architecture and design decisions
│   ├── decision_index.md       # Index of all decisions
│   └── [individual decision records]
├── planning/                   # Planning documents
│   ├── roadmap.md              # Project roadmap
│   └── milestones.md           # Milestone definitions
├── cross-domain/               # Cross-cutting concerns
│   ├── dependencies.md         # Cross-component dependencies
│   └── interfaces.md           # Interface definitions
├── meta/                       # Information about the network itself
│   ├── updates.md              # Record of network changes
│   └── maintenance.md          # Network maintenance procedures
└── archive/                    # Archived documents from the inbox
```

## Navigation Paths

### For New Team Members
1. Start with `foundation/project_definition.md` to understand the project's purpose
2. Review `foundation/principles.md` to understand guiding principles
3. Explore `foundation/architecture.md` for a system overview
4. Check `planning/roadmap.md` to understand current priorities

### For Feature Development
1. Review relevant domain documentation in `domains/`
2. Check `cross-domain/dependencies.md` for integration points
3. Review applicable decision records in `decisions/`
4. Follow the process in `processes/development.md`

### For Understanding Design Decisions
1. Start with `decisions/decision_index.md`
2. Navigate to specific decision records of interest
3. Review related architecture documentation in `foundation/architecture.md`

### For Document Integration
1. Follow the process outlined in `processes/document_integration.md`
2. Update relevant sections of the context network
3. Record changes in `meta/updates.md`
4. Archive processed documents in `archive/`

## Maintenance

This context network is maintained according to the procedures documented in `meta/maintenance.md`. All changes to the network structure should be recorded in `meta/updates.md`.

## Classification System

Information nodes in this context network are classified along these dimensions:

1. **Domain**: [Primary knowledge area]
   - Valid values: Frontend, Backend, Design, DevOps, Documentation, Business, etc.

2. **Stability**: [Change frequency expectation]
   - Static: Fundamental principles unlikely to change
   - Semi-stable: Established patterns that evolve gradually
   - Dynamic: Frequently changing information

3. **Abstraction**: [Detail level]
   - Conceptual: High-level ideas and principles
   - Structural: Organizational patterns and frameworks
   - Detailed: Specific implementations and examples

4. **Confidence**: [Information reliability]
   - Established: Verified and reliable information
   - Evolving: Partially validated but subject to refinement
   - Speculative: Exploratory ideas requiring validation
