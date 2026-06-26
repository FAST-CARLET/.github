# FAST-CARLET GitHub Organization

## Overview

This repository contains the shared GitHub configuration for the **FAST-CARLET** organization.

It is used to centralize templates, standards and collaboration rules that are automatically applied across all repositories belonging to the organization.

This repository does **not** contain application source code.

---

## Purpose

The objective of this repository is to ensure a consistent development workflow across all FAST products by providing common GitHub resources.

These resources include:

* Pull Request templates
* Issue templates
* Contribution guidelines
* Security policy
* Shared GitHub configuration

---

## Development Workflow

All FAST repositories follow the same development process.

```text
Developer Branch
        │
        ▼
Pull Request
        │
        ▼
PRE
        │
        ▼
Validation
        │
        ▼
Pull Request
        │
        ▼
PRO
        │
        ▼
Release
        │
        ▼
GitHub Packages
```

Direct modifications to protected branches are not allowed.

---

## Repository Structure

```text
.github/
│
├── PULL_REQUEST_TEMPLATE.md
├── ISSUE_TEMPLATE/
├── CONTRIBUTING.md
├── SECURITY.md
└── ...
```

---

## Applicable Repositories

The shared configuration is intended to be used by repositories such as:

* FASTRU
* FASTFM
* FASTFR
* FASTIT

and any future repositories created within the FAST-CARLET organization.

---

## Maintained by

FAST Developers S.L.

Copyright © FAST Developers S.L.
