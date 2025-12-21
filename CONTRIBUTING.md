# Contributing to SubSentry

Thanks for your interest in contributing to **SubSentry** 🚀

This project is part of **Geekhaven OpenCode** and follows a **simple, beginner-friendly workflow**.

---

## 🧩 Contribution Workflow

1. Browse open issues and comment to get assigned
2. Fork the repository to your GitHub account
3. Create a feature branch in your fork

   ```bash
   git checkout -b feature/short-description
   ```

4. Make your changes locally
5. Commit with a clear message
6. Open a Pull Request to the **`main`** branch

---

## ✅ Contribution Rules

- **One PR = One Issue**
- Do **NOT** commit directly to `main`
- Keep PRs small and focused
- Add screenshots or screen recordings for UI changes
- Follow existing project structure and code style

PRs that do not follow these rules may be requested to change or closed.

---

## 🏷️ Issue Labels Explained

- `good first issue` – Beginner-friendly tasks
- `frontend` – UI, components, styles
- `backend` – APIs, database, logic
- `dashboard` – Analytics and widgets
- `documentation` – Docs-only improvements
- `OpenCode` – Official OpenCode issues

---

## 🧪 Local Development Tips

### Frontend

```bash
cd client
npm run dev
```

### Backend

```bash
cd server
npm run dev
```

Make sure both servers are running when working on full-stack features.

---

## 🔍 Code Quality Guidelines

- Use meaningful variable and function names
- Avoid large files; refactor into smaller components/modules
- Handle errors gracefully
- Avoid committing commented-out code

---

## 📌 Pull Request Checklist

Before opening a Pull Request, make sure:

- [ ] You are assigned to the issue
- [ ] Your PR addresses **only one issue**
- [ ] Code builds and runs locally without errors
- [ ] No console errors or warnings
- [ ] UI changes include screenshots or screen recordings
- [ ] API changes are tested with valid & invalid data
- [ ] Commit messages follow the project convention
- [ ] No sensitive data or `.env` files committed
- [ ] PR title and description are clear

---

## 🤝 Need Help?

- Ask questions in the issue thread
- Be respectful and collaborative
- Maintainers will try to respond within 24 hours

Happy contributing 💙

---

## 🧠 How to Choose an Issue (Important)

- Read the full issue description carefully
- Comment "I would like to work on this" to get assigned
- Do **not** start work without assignment
- Prefer `good first issue` if you are new

---

## 🛠️ Branch Naming Convention

Use clear and consistent branch names:

```
feature/add-subscription-form
fix/api-validation-error
docs/update-readme
```

---

## 📝 Commit Message Guidelines

Use short, meaningful commit messages:

```
feat: add subscription form UI
fix: handle invalid subscription id
refactor: extract api service layer
docs: update contributing guide
```

---

## 🚫 What NOT to Do

- Do not push directly to `main`
- Do not open large PRs touching multiple issues
- Do not submit incomplete or broken code
- Do not copy code without understanding it

---

## 🧪 Testing Expectations

- Ensure frontend pages load without errors
- Ensure APIs work with valid and invalid inputs
- Manually test your feature before submitting PR

---

## 🎯 Definition of Done

An issue is considered **done** when:

- Feature works as described
- Code is clean and readable
- No console errors
- PR is reviewed and merged

---

## ❤️ Community Guidelines

- Be respectful to all contributors
- Help others if you can
- Feedback should be constructive

We are here to learn and build together.
