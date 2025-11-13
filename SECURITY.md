Thank you for helping me make this repository safe for everyone to use.

---

# Security Policy

## 🔒 Purpose

This policy outlines how security is managed across this repository. It ensures that all source code, configurations, and workflows are protected from unauthorized access, data leakage, or malicious actions.

## 🐛 Reporting a Vulnerability

If you discover a security vulnerability within the repository:

1. **Do not disclose the issue publicly.**
2. Immediately report it by emailing `security@nextlevel.com`.
3. Provide the following details:
   - Repository name
   - Description of the vulnerability/issue
   - Steps to reproduce
   - Any potential impact or risk identified

Our security team will investigate promptly, apply necessary patches and notify the relevant personnels.

---

## 🧠 Security Best Practices

All contributors must follow these practices:

- **Never commit sensitive data** such as API Keys, Passwords or Private tokens.
- Store all secrets securely using **Github Secrets** or environment variables.
- Use **branch protection rules** to prevent unauthorized direct commits to protected branches.
- Require **pull requests (PRs)** for all changes to the main branch.
- Enable two-factor authentication (2FA) on your **Github** account.
- Use `.gitignore` to exclude sensitive or local files.
- Review pull requests carefully before merging.

---

## Dependency and Package Management

- Use only **trusted, version-pinned dependencies** from verified sources.
- Regularly update dependencies to patch known vulnerabilities.
- Automated dependency scanning (e.g. **Dependabot**) must be enabled.
- Do not use external scripts or packages unless approved by maintainers.

---

## 🎬 Github Actions and Workflows

When creating or modifying workflows:

- Store all secrets in **Github repository or organization secrets**, not directly in yml files.
- Limit permissions using the `permissions:` field in workflows and avoid using `write-all`.
- Review logs regularly for unexpected behavior or failed runs.
- Use pinned versions for all third-party actions (e.g. `actions/checkout@v3`) to prevent unexpected changes.

---

## 🪪 Access Control

- Access to repositories should follow the principle of least privilege.
- Roles and Permissions are managed by organization owners only.
- Access reviews occur quarterly and upon user departure or role change.

---

## 📝 Policy Enforcement

Non-compliance may result in:

- Immediate suspension of **Github** access.
- Removal from the organization or team.
- Reporting to management or legal as necessary.

---

## 📘 Additional Resources

- [GitHub Security Policy Documentation](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
- [Prevention of Secret Leaks](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/preventing-secret-leaks)
