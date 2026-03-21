# .github

Organization-wide CI/CD workflows, templates, and security policies for Trojan Online.

## Reusable Workflows

| Workflow | Description | Usage |
|----------|-------------|-------|
| `python-ci.yml` | Lint, typecheck, test, security scan for Python projects | `uses: trojanonline/.github/.github/workflows/python-ci.yml@main` |
| `dotnet-ci.yml` | Build, test, format check, security scan for .NET projects | `uses: trojanonline/.github/.github/workflows/dotnet-ci.yml@main` |
| `codeql.yml` | CodeQL static analysis | `uses: trojanonline/.github/.github/workflows/codeql.yml@main` |
| `dependency-review.yml` | Dependency vulnerability review on PRs | `uses: trojanonline/.github/.github/workflows/dependency-review.yml@main` |

## Organization Defaults

- **PR Template**: Standardized pull request template with security checklist
- **CODEOWNERS**: Requires org owner review
- **SECURITY.md**: Responsible disclosure policy
- **Dependabot**: Weekly GitHub Actions updates
