# SaarIT Solutions - GitHub Repository Guidelines

Welcome to **SaarIT Solutions'** official GitHub workspace!  
This document outlines our best practices and standards for creating, managing, and maintaining repositories under the SaarIT Solutions organization.

---

## 📁 Repository Creation Guidelines

Before creating a new repository, ensure:
- The project is not already represented by an existing repo.
- You have approval from your team lead or project manager.
- The repo serves a clear, defined purpose.

### ✅ Steps to Create a Repository:
1. Use the **SaarIT Solutions GitHub organization** account.
2. Click **"New Repository"**.
3. Select appropriate **visibility**:
   - **Private**: Internal/team projects.
   - **Public**: Open-source or client-approved public work.
4. Add a descriptive **README.md**.
5. Add a **`.gitignore`** suited for your tech stack.
6. Set up a default **branch (`main`)**.

---

## 🧾 Naming Conventions

Consistency is critical across all projects. Follow these naming standards:

### 🔹 Repository Names:
- Use **kebab-case** (lowercase, hyphen-separated)
- Be descriptive but concise

```bash
✅ client-dashboard-frontend
✅ mobile-api-backend
❌ ClientDashboard
❌ myRepo123
```

### 🔹 Branch Names:
- Use **feature/**, **bugfix/**, **hotfix/**, or **release/** prefixes

```bash
feature/login-authentication
bugfix/null-pointer-exception
release/v1.0.0
```

### 🔹 Commit Messages:
Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

```
feat: add user login component
fix: resolve login crash on iOS
docs: update API usage in README
refactor: clean up dashboard logic
```

---

## 📄 Folder & File Structure

- Follow **modular and scalable** project architecture
- Common folders:
  ```
  /docs         → documentation
  /src          → main source code
  /tests        → unit and integration tests
  /scripts      → automation or deployment scripts
  ```

---

## 🔒 Security & Access

- Only team leads and senior developers can grant repo access.
- Use **branch protection rules** (e.g., code reviews before merging).
- Avoid committing secrets, keys, or sensitive data.

---

## 🧪 Code Quality

- Code must follow our language-specific linting & formatting rules.
- PRs should be reviewed by **at least one peer** before merging.
- Automated CI checks must pass (if applicable).

---

## 🚀 Deployment & CI/CD

- Use GitHub Actions or integrated CI tools.
- Define deployment configurations in `/deploy` or `.github/workflows/`.

---

## 📬 Contact & Support

For repo-related issues or requests:
- Email: githubsaarit@gmail.com
- Internal: Use our team Slack/Teams channel

---

**Let's build reliable, scalable, and clean software — the SaarIT way!**
