# Git Commands

## 01 - Git Init

Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

---

## 02 - git clean

Removes untracked files from the working directory. This is the logical counterpart to git reset, which (typically) only operates on tracked files.

---

## 03 - git config

A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.

---

## 04 - git fetch

Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.

---

## 05 - git log

Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.

---

## 06 - git remote

A convenient tool for administering remote connections. Instead of passing the full URL to the fetch, pull, and push commands, it lets you use a more meaningful shortcut.

---

## 07 - git reset

Undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.

---

## 08 - git revert

Undoes a committed snapshot. When you discover a faulty commit, reverting is a safe and easy way to completely remove it from the code base.

---

## 09 - git status

Displays the state of the working directory and the staged snapshot. You’ll want to run this in conjunction with git add and git commit to see exactly what’s being included in the next snapshot.

---

## 10 - git diff

Displays the differences between the working directory and the last commit.
