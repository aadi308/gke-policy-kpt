# GKE Enterprise Custom Policy Bundle

## Purpose
This bundle enforces enterprise-specific governance and security policies across all GKE clusters in our fleet.

## Structure
- `templates/` → Contains ConstraintTemplates
- `constraints/` → Contains Constraints

##  Fetch
```bash
kpt pkg get https://github.com/aadi308/gke-policy-kpt.git gke-policy
cd gke-policy

