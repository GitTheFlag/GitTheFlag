# 🚩 Git The Flag

> **Investigate the repo. Find the truth.**

A game where the challenge *is* the git repository itself.
No web app. No special tools. Just you, your terminal, and `git`.

---

## How it works

1. Clone a case repo to your computer
2. Explore it using git commands in your terminal
3. Find hidden flags that look like `GTF{...}`
4. Submit each flag by opening a GitHub Issue — a bot validates it instantly
5. Complete the final task and open a Pull Request to close the case

---

## How to play

**Step 1 — clone the repo**

```bash
git clone https://github.com/GitTheFlag/case-01
cd case-01
```

This downloads the entire repo — all files, all branches, all history — to your machine.

**Step 2 — look around**

```bash
ls
cat README.md
```

Read everything. Flags can be in files, in commit messages, in branches you have not opened yet.

**Step 3 — explore branches**

```bash
git branch -a
git checkout <branch-name>
```

Each branch is a parallel version of the project. Switch between them and look at the files on each one.

**Step 4 — read the history**

```bash
git log --oneline
```

Every commit is a saved snapshot. Read the messages — they tell a story, and sometimes the story contains the flag.

**Step 5 — submit a flag**

When you find a flag (it looks like `GTF{...}`), open a new [Issue](https://github.com/GitTheFlag/case-01/issues/new) and use the flag as the title. A bot replies in seconds.

**Step 6 — close the case**

Each case ends with a hands-on task: edit a file, commit it, push it, and open a Pull Request. CI validates it automatically.

---

## Cases

| # | Name | Level | What you learn |
|---|------|-------|----------------|
| [Case 01](https://github.com/GitTheFlag/case-01) | Welcome to the Team | 🟢 Beginner | `clone` · `branch` · `checkout` · `log` · `diff` |
| [Case 02](https://github.com/GitTheFlag/case-02) | The Vanishing Feature | 🟡 Rookie | `log` forensics · `show` · `tag` · `ls-remote` |
| [Case 03](https://github.com/GitTheFlag/case-03) | The Rewritten Past | 🔴 Mid | `stash` · `reflog` · `rebase` · `cherry-pick` |
| [Case 04](https://github.com/GitTheFlag/case-04) | The Inside Job | ⚫ Advanced | `bisect` · `blame` · merge conflicts · `notes` |

> **New to git?** Start with Case 01. It explains everything from scratch.

---

## Get started

```bash
git clone https://github.com/GitTheFlag/case-01
cd case-01
cat README.md
```

---

## What you will learn

- What git is and why developers use it
- How to clone, explore, and navigate a repository
- How to read history and compare branches
- How to find hidden information in a git repo
- How to contribute using branches and pull requests

---

## Resources

- [Command Cheatsheet](https://github.com/GitTheFlag/cheatsheet) — every command taught across all cases
- [Discussions](https://github.com/GitTheFlag/case-01/discussions) — community, questions, leaderboard

---

*Built with ❤️ and `git log --all`*
