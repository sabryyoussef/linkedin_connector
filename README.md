# LinkedIn Connector

Odoo module for LinkedIn integration workflows.

## Supported Versions
- 19.0
- 18.0
- 17.0
- 16.0

## Branch Mapping
- Odoo 19 -> `19.0`
- Odoo 18 -> `18.0`
- Odoo 17 -> `17.0`
- Odoo 16 -> `16.0`

## Installation as Submodule
```bash
git submodule add -b 19.0 https://github.com/sabryyoussef/linkedin_connector.git addons/linkedin_connector
```

## Notes

This repository is maintained as a standalone Odoo module repository and is intended to be reused in other Odoo projects as a Git submodule.

## Public notes
This repository contains Odoo modules related to LinkedIn connectivity and job-search orchestration.

### Problem
Personal and partner workflows need structured job discovery and application tracking inside Odoo without leaking private credentials into public docs.

### Scope
- Odoo models and services for LinkedIn-related workflows
- Job intake / orchestration helpers
- Operator-facing configuration in Odoo

### Limitations
- Not a drop-in “production SaaS” package without environment-specific credentials and policy configuration.
- Do not commit tokens, cookies, or private CV files.

### License / ownership
Review repository license and attribution before reuse.

