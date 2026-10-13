# Sunshine Realty Brokerage Inc.

This is the organization-wide configuration repository for the
**sunshine-realty-brokerage-inc** GitHub organization.

**Website:** [sunshinerealtybrokerage.ca](https://sunshinerealtybrokerage.ca)

## What This Repository Contains

| Path                                     | Purpose                                                                 |
| ---------------------------------------- | ----------------------------------------------------------------------- |
| `profile/README.md`                      | Public profile shown on the organization's GitHub page                  |
| `LICENSE.md`                             | Proprietary license covering all Materials in the organization          |
| `SECURITY.md`                            | How to report vulnerabilities and leaked secrets privately              |
| `CODE_OF_CONDUCT.md`                     | Expected professional conduct and how it is enforced                    |
| `CONTRIBUTING.md`                        | Branching, commit, pull request, and confidentiality rules              |
| `SUPPORT.md`                             | Where to get help                                                       |
| `GOVERNANCE.md`                          | Roles, teams, and the access and repository lifecycle                   |
| `.github/ISSUE_TEMPLATE/`                | Default bug report and feature request forms                            |
| `.github/PULL_REQUEST_TEMPLATE.md`       | Default pull request checklist                                          |
| `.github/CODEOWNERS`                     | Requires admin approval for changes to this repository                  |
| `.github/dependabot.yml`                 | Keeps this repository's GitHub Actions up to date                       |
| `workflow-templates/`                    | Starter workflows offered to every repository (license check)           |
| `README.md`                              | This file: how the organization is set up and governed                  |

Community health files placed here, such as `SECURITY.md`, `CODE_OF_CONDUCT.md`,
`CONTRIBUTING.md`, issue templates, and pull request templates, become the default for
every repository in the organization that does not define its own.

## Ownership & Licensing

All code, documentation, designs, data, and other Materials in this organization are the
**exclusive property of Sunshine Realty Brokerage Inc.** and are covered by the
[proprietary license](LICENSE.md).

- **Not open source.** No rights are granted to anyone outside the company without
  written permission.
- **Company ownership of contributions.** Work done by employees, contractors, and
  partners in this organization belongs to the company.
- **Every repository must carry the license.** Each new repository should include a copy
  of [`LICENSE.md`](LICENSE.md), or a `LICENSE` file that refers to it, and keep the
  copyright notice: `Copyright © <year> Sunshine Realty Brokerage Inc. All rights reserved.`

## Access Control Policy

Organization administrators maintain these settings to prevent unauthorized access:

### Organization Settings

- [ ] **Two-factor authentication required** for all members and outside collaborators.
- [ ] **Base permissions** for members set to **No permission**. Access is granted
      through teams only.
- [ ] **Repository creation** restricted to **private** repositories, or to owners only.
- [ ] **Forking of private repositories** disabled.
- [ ] **Changing repository visibility** restricted to organization owners.
- [ ] **Repository deletion and transfer** restricted to organization owners.
- [ ] **Outside collaborators** can be invited by owners only.
- [ ] **GitHub Pages** public publishing disabled for private repositories.
- [ ] **Third-party application access** restricted. OAuth and GitHub Apps must be
      approved by an owner.
- [ ] **Personal access tokens:** fine-grained tokens require approval; classic tokens
      are restricted.

### Repository Defaults

- [ ] All repositories are **private** by default. This `.github` repository is the only
      exception: it must be public for the organization profile to display, so it must
      never hold confidential information.
- [ ] **Branch protection or rulesets** on `main`: pull request reviews required, status
      checks required, force pushes and deletions blocked.
- [ ] **Secret scanning** and **push protection** enabled.
- [ ] **Dependabot** alerts and security updates enabled.
- [ ] **CODEOWNERS** defined for sensitive areas of the code.

### Members & Teams

- Grant access by **least privilege**, through teams such as `engineering`, `admins`,
  and `contractors`.
- Owners review access **every quarter** and remove inactive or departed members right away.
- Contractors and partners must have a **signed NDA or agreement** before they receive access.
- Credentials, API keys, client data, and personal information (PIPEDA) must **never**
  be committed to any repository.

## Reporting a Security Issue

Do **not** open a public issue. Report suspected vulnerabilities or unauthorized access
privately to the organization owners, or through
[sunshinerealtybrokerage.ca](https://sunshinerealtybrokerage.ca).

---

© 2026 Sunshine Realty Brokerage Inc. All rights reserved. See [LICENSE.md](LICENSE.md).
