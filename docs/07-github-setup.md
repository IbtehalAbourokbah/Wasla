# GitHub setup for wasla

Last updated: 2026-09-15

## What is connected

- **GitHub account:** `IbtehalAbourokbah` (ibtehalea@gmail.com)
- **Claude GitHub App:** installed on the personal account, repository access = **All repositories**
  (manage at https://github.com/settings/installations)
- **Where it applies:** account-level. Claude Code on the web (https://claude.ai/code) can now
  clone and work on any of these repos. Repos visible in the picker:
  - `IbtehalAbourokbah/Wasla` — **public, currently empty (no commits yet)**
  - `IbtehalAbourokbah/CPIT251-IbtehalAbourokbah` — public, Java
  - `IbtehalAbourokbah/CPIT251` — private

## Notes / limitations

- claude.ai **Projects** do not currently offer GitHub as a knowledge source in this account —
  project Context only accepts PDFs, documents and pasted text, and GitHub does not appear in the
  connector directory. So the GitHub link lives at the account level (Claude Code), not inside the
  wasla project itself.
- The `Wasla` repo has **no commits and no default branch**. It needs at least one commit
  (e.g. a README on `main`) before Claude Code can clone it.

## How to use it

1. Go to https://claude.ai/code
2. Click **Select repository…** next to the prompt box and pick `IbtehalAbourokbah/Wasla`
3. Describe the task — Claude clones the repo in the cloud and opens a pull request.
