
# Contributing Guidelines

Thanks for collaborating on this repository. This project follows a **collaborator-based workflow** (no forks). All contributors are added as collaborators and are expected to follow the rules below to keep the codebase clean, scalable, and production-ready.

---

## 📌 Core Principles

* Write **clean, readable, and maintainable code**
* Optimize for **scalability and performance** where relevant
* Prefer **clarity over cleverness**
* Small, focused changes > large unscoped PRs
* Every change goes through a Pull Request (PR)

---

## 🧑‍💻 Getting Started

### Clone the Repository

```bash
git clone https://github.com/<owner>/<repo-name>.git
cd <repo-name>
```

Make sure you can run the project locally before making changes.

---

## 🌿 Branching Strategy

⚠️ **Never commit directly to `main`.**

Create a new branch for every piece of work:

```bash
git checkout -b feature/short-description
```

### Branch Naming Conventions

* `feature/*` → new features
* `fix/*` → bug fixes
* `perf/*` → performance improvements
* `refactor/*` → internal refactoring
* `docs/*` → documentation changes
* `chore/*` → tooling / config / maintenance

Examples:

* `feature/auth-refresh-tokens`
* `fix/api-null-check`
* `perf/db-query-optimization`

---

## 🔄 Keeping Your Branch Updated

Before starting work:

```bash
git pull origin main
```

If your branch lives longer than a day or two:

```bash
git fetch origin
git rebase origin/main
```

Resolve conflicts carefully and test again after rebasing.

---

## ✍️ Coding Guidelines

* Follow existing **project architecture and patterns**
* Do not introduce breaking changes without discussion
* Avoid unnecessary dependencies
* Keep functions and components focused
* Add comments only where logic is non-obvious
* Ensure linting and tests (if present) pass

---

## 🧾 Commit Message Convention

Use clear, conventional commit messages:

```bash
git commit -m "feat: add request-level caching"
```

### Allowed Prefixes

* `feat:` new feature
* `fix:` bug fix
* `perf:` performance improvement
* `refactor:` code restructuring (no behavior change)
* `docs:` documentation only
* `chore:` tooling / config / cleanup

Avoid vague messages like `update`, `fix stuff`, or `changes`.

---

## 🚀 Pushing Changes

Push your branch to the main repository:

```bash
git push origin feature/short-description
```

---

## 🔍 Pull Request (PR) Guidelines

All changes **must** go through a Pull Request.

### A good PR includes:

* Clear title and description
* What problem it solves
* What was changed and why
* Screenshots/logs if applicable
* Linked issue (if one exists)

### PR Rules

* At least **one approval** required
* The author should **not self-merge** (unless agreed beforehand)
* Squash merge is preferred for a clean history

Draft PRs are encouraged for early feedback.

---

## 🔐 Security & Secrets

* ❌ Never commit API keys, secrets, or credentials
* Use environment variables where required
* Report security issues privately to the repo owner

---

## 🚫 What Not To Do

* Push directly to `main`
* Merge without review
* Submit large unscoped PRs
* Break existing functionality without notice
* Commit generated or build files unless required

---

## 🧠 Collaboration Etiquette

* Be respectful and technical in discussions
* Ask questions early if unsure
* Assume positive intent in reviews
* Prefer async discussion via PR comments

---

## ✅ After Your PR Is Merged

```bash
git checkout main
git pull origin main
git branch -d feature/short-description
```

---

Thanks for contributing.
Quality code > fast code- always.
