# Governance

This document explains how the **sunshine-realty-brokerage-inc** GitHub organization is
owned and managed.

## Ownership

The organization and everything in it are the property of **Sunshine Realty Brokerage Inc.**
See [LICENSE.md](LICENSE.md).

## Roles

| Role                     | Who                                   | Responsibilities                                                                 |
| ------------------------ | ------------------------------------- | -------------------------------------------------------------------------------- |
| Organization owner       | Designated company leadership / IT    | Billing, security settings, membership, repository creation/deletion/visibility  |
| Maintainer               | Technical leads                       | Review and merge pull requests, manage branch rules, triage issues               |
| Member                   | Employees                             | Contribute to the repositories they are assigned to through their team           |
| Outside collaborator     | Contractors and partners under NDA    | Limited, time-bound access to specific repositories only                         |

Keep at least **two** organization owners at all times so the company never loses
control of the organization.

## Teams

Access is granted through teams, never by default membership:

- `admins` — organization owners and lead engineers
- `engineering` — application developers
- `contractors` — external developers with limited, time-bound access

## Access Lifecycle

1. **Onboarding:** a manager requests access; an owner adds the person to the right team.
   Contractors must have a signed agreement and NDA first.
2. **Review:** owners review every member, collaborator, team, deploy key, and installed
   app each quarter.
3. **Offboarding:** access is removed on the person's last day, and any secrets they could
   see are rotated.

## Repository Lifecycle

- New repositories are **private**, include `LICENSE.md`, a `README.md`, and a `CODEOWNERS`
  file, and have branch protection on `main`.
- Only owners may make a repository public, transfer it, or delete it.
- Unused repositories are **archived**, not deleted.

## Changes to This Policy

Changes to the files in this repository require a pull request approved by an organization owner.
