# Contributing Guidelines

These guidelines apply to every repository in the **sunshine-realty-brokerage-inc**
organization. A repository may add its own `CONTRIBUTING.md` with project-specific details.

> **Only authorized contributors.** Contributions are accepted only from employees and
> contracted partners of Sunshine Realty Brokerage Inc. All contributions become the
> property of the company under the [LICENSE](LICENSE.md).

## Before You Start

1. Make sure your account has **two-factor authentication** enabled.
2. Get access through your team lead. Do not request access to repositories you do not need.
3. Read the repository's README and setup instructions.

## Workflow

1. **Create an issue**, or pick up an existing one, that describes the work.
2. **Create a branch** from `main` using this naming convention:

   | Type          | Pattern                       | Example                           |
   | ------------- | ----------------------------- | --------------------------------- |
   | Feature       | `feature/<issue>-short-name`  | `feature/42-listing-search`       |
   | Bug fix       | `fix/<issue>-short-name`      | `fix/57-map-pin-offset`           |
   | Hotfix        | `hotfix/<short-name>`         | `hotfix/login-timeout`            |
   | Chore / docs  | `chore/<short-name>`          | `chore/update-dependencies`       |

3. **Commit** in small, focused steps using
   [Conventional Commits](https://www.conventionalcommits.org):

   ```text
   feat(listings): add price range filter
   fix(auth): handle expired session tokens
   docs: update local setup steps
   ```

4. **Open a pull request** into `main` using the PR template. Link the issue
   (for example, `Closes #42`).
5. **Get it reviewed.** At least one approval from a code owner is required. All status
   checks must pass.
6. **Merge** with squash merge unless the repository says otherwise. Delete the branch
   after merging.

## Code Standards

- Follow the linter and formatter configured in each repository.
- Write tests for new behaviour and bug fixes.
- Keep pull requests small enough to review in one sitting.
- Update documentation when behaviour changes.

## Security & Confidentiality

- **Never commit secrets.** That includes API keys, passwords, tokens, certificates, and
  `.env` files. Use the approved secrets manager or GitHub Actions secrets.
- **Never commit real client data.** Use anonymized or synthetic data only.
- **Do not copy code** from this organization into personal repositories, gists, public
  forums, or unapproved AI tools.
- **Third-party code** may be added only under a license compatible with proprietary use
  (for example MIT, BSD, or Apache-2.0). Ask before adding GPL or AGPL dependencies.
- Report security issues according to the [Security Policy](SECURITY.md).

## Code of Conduct

All contributors must follow the [Code of Conduct](CODE_OF_CONDUCT.md).
