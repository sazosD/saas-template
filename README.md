# saas-template

Starting point for new SaaS projects. Click **Use this template** on GitHub to spin up a new repo with everything pre-wired.

## What's pre-installed

- **Claude Security Review** — AI-powered security scan on every PR via `.github/workflows/claude-security-review.yml`
- `.gitignore` tuned for Next.js + Node
- Placeholder `.env.example`

## One-time setup after creating a new repo from this template

1. Add `ANTHROPIC_SECRET` to repo secrets: `Settings → Secrets and variables → Actions → New repository secret`
2. That's it — security review runs on every PR automatically.
