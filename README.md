# GKE Enterprise Custom Policy Bundle

## Purpose
This bundle enforces enterprise-specific governance and security policies across all GKE clusters in our fleet.

## Structure
- `templates/` → Contains ConstraintTemplates
- `constraints/` → Contains Constraints

##  Fetch
```bash
kpt pkg get https://github.com/<your-org>/<your-repo>.git@main gke-enterprise-custom-policy-bundle
cd gke-enterprise-custom-policy-bundle

