# 🧩 Project Issue Templates & Automation

This repository contains standardized issue templates and GitHub Actions workflows for consistent project management across all repositories.

---

## 📋 Issue Templates

We use **GitHub Issue Forms** (YAML-based) to ensure all issues follow the same structure. The following templates are available:

| Template | Purpose | Labels | Type |
|----------|---------|--------|------|
| **Bug** 🐛 | Report a problem or unexpected behavior | `bug` | `bug` |
| **Feature** 🚀 | Request a new functionality | `feature` | `feature` |
| **Enhancement** 📈 | Improve/extend existing functionality | `enhancement` | `task` |
| **Refactor** ♻️ | Code cleanup with no user-visible change | `enhancement` | `task` |

---

## 🤖 Automation Workflows

### Auto Label Issues and PRs

Automatically adds repository-specific labels to issues and pull requests:

| Repository | Label |
|------------|-------|
| `happahabba` | `backend` |
| `LeggerLegger` | `frontend` |

**Workflow:** `.github/workflows/auto-label.yml`

---

## 🚀 Usage

1. **Create an issue** → Select the appropriate template
2. **Fill in the fields** → Follow the placeholders
3. **Submit** → Labels are automatically applied

---

## 📝 Notes

- All templates use **GitHub Issue Forms** (YAML)
- Labels are applied automatically via GitHub Actions
- Repository-specific labels (`backend`/`frontend`) are set based on the repository

---

## 🔧 Maintenance

To add a new template:
1. Create a new `.yml` file in `.github/ISSUE_TEMPLATE/`
2. Define the form fields using the [GitHub Issue Form Syntax](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms)
3. Commit and push

---

## 📚 License

MIT