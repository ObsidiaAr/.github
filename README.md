# ObsidiaAr GitHub Defaults

This public repository contains shared GitHub community health files and contribution templates used across repositories in the **ObsidiaAr** organization.

## Purpose

The goal of this repository is to provide consistent defaults for work tracking and pull request quality across ObsidiaAr projects.

Repositories may inherit these templates when they do not define their own local versions. Individual repositories can override these defaults when their workflow requires something more specific.

## Shared templates

The repository provides default templates for:

- Epics — long-lived platforms or major delivery surfaces.
- Features — modules or broad product capabilities.
- Tasks — atomic user stories suitable for implementation.
- Bugs — defects that require traceable diagnosis and resolution.
- Pull Requests — implementation review, validation and traceability.

## Repository structure

```text
.github/
├── ISSUE_TEMPLATE/
│   ├── epic.yml
│   ├── feature.yml
│   ├── task.yml
│   ├── bug.yml
│   └── config.yml
└── pull_request_template.md
```

## Scope

This repository contains only organization-wide defaults that are safe to publish publicly.

Product-specific documentation, architecture decisions, specifications, credentials, internal URLs, business-sensitive information and implementation details belong in their respective private repositories.

## Conventions

The templates are designed around a traceable delivery flow:

```text
Product decision
→ Specification
→ Feature
→ Task or Bug
→ Branch
→ Pull Request
→ Validation
→ Release
```

Not every ObsidiaAr repository is required to use the full hierarchy. Repositories should adopt only the elements that fit their product and delivery model.

## Overrides

A repository can define its own Issue Forms or Pull Request template when its needs differ from these organization defaults. Local templates take precedence over the shared defaults.

## Maintenance

Changes to these defaults should remain generic, reusable and free of private project information.
