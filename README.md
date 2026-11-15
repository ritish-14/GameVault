# GameVault — Git & GitHub Assignment

**Student:** Ritish B  
**Student ID:** 2024Eb01579

This repository contains the practical files for Question 1 and the test-case documentation for Question 2 of the supplied assignment.

## Project files

- `index.html` — GameVault home page.
- `about.html` — About page and feature description.
- `styles.css` — Shared responsive styling.
- `.gitignore` — Ignores `*.log` files and the `temp/` directory.
- `git_commands.txt` — Git command reference used in the workflow.
- `TEST_CASES.md` — Login System test cases (TC_01 to TC_08).

## Run locally

Open `index.html` in a browser. No build tools or dependencies are required.

## Verify the Git assignment

Run these commands from this folder in PowerShell:

```powershell
git status --short
git branch -a
git log --oneline --graph --decorate --all
git check-ignore debug.log temp/sample.tmp
Test-Path temporary.txt
```

Expected checks: `debug.log` and `temp/sample.tmp` are ignored; `Test-Path temporary.txt` returns `False`; the history contains the feature work, merge, and revert commits. `main` and `feature` are local branches.



## Assignment evidence still to capture

The assignment asks for screenshots of the project folder, branch/merge history, `.gitignore` and `git check-ignore`, the revert and `Test-Path` result, and the public GitHub repository with its commit history. Add your own screenshots to your submission PDF after pushing; they cannot be generated honestly before you perform the GitHub push.
