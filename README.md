# Git Bootcamp: Day 2 

Welcome to Day 2 of the Git & GitHub Bootcamp training intensive! This repository contains the reference materials, hands-on labs, and homework tasks designed to take you from a single-developer workflow to fluid team collaboration.

## Day 2 Learning Objectives
* Master isolated feature development using branches.
* Resolve merge conflicts safely without destroying code.
* Use time-travel commands (`reset`, `revert`) to recover from mistakes.
* Collaborate via standard GitHub Pull Request workflows.

---

## Course Milestones & Progress Checklist

Complete the tasks below in chronological order during today's workshop.

### Phase 1: Local Mastery & Time Travel
- [x] **Step 1:** Configure your local workspace environment and sync upstream repository tracking.
- [x] **Step 2:** Create an isolated feature branch named `feature/login-validation`.
- [x] **Step 3:** Use `git diff` to audit untracked modifications prior to staging a commit.
- [ ] **Step 4:** Execute a `git commit --amend` to repair a faulty commit message typo.
- [ ] **Step 5:** Safely rollback a broken commit using `git revert` to preserve shared history.

### Phase 2: Team Collaboration & Conflict Resolution
- [ ] **Step 6:** Configure and link the official remote repository (`origin`).
- [ ] **Step 7:** Pull down downstream updates via `git fetch` and perform a fast-forward merge.
- [x] **Step 8:** Intentionally simulate and manually resolve a structural merge conflict.
- [ ] **Step 9:** Leverage `git stash` to save local modifications when hotfixing a production issue.

### Phase 3: GitHub Advanced Workflows
- [ ] **Step 10:** Push your finalized topic branches up to your GitHub forks.
- [ ] **Step 11:** Draft and open a structured GitHub Pull Request (PR) targeted at the `main` branch.
- [ ] **Step 12:** Review a peer's incoming PR, leave constructive comments, and approve changes.

---

## Sandbox Execution Guide

To complete today's lab checklist locally, clone this repository to your system:

```bash
# Clone this bootcamp repository
git clone https://github.com

# Move into the workspace folder
cd git-bootcamp-day-2
```

### Useful Cheat Sheet Commands
* Check branch states and untracked files: `git status`
* View a graphical tree of your commit history: `git log --oneline --graph --all`
* Abandon uncommitted directory changes: `git checkout -- <file>`

---

##  Contributing & Assistance
Stuck on a merge conflict during a checklist step? Do not panic! 
* Open a detailed item inside the repository's **GitHub Issues** tab.
* Reference your problem by attaching a terminal output log or screenshot.

