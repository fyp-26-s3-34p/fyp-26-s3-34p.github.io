# Rules for editing this site

This repo is the NutriKaki website. GitHub Pages publishes it at https://fyp-26-s3-34p.github.io/.

## This repo is public

Anyone on the internet can read every file and every commit here. Never add:

- course material: the subject outline, task sheets, lecture slides, marking guides
- personal data: student IDs, emails, phone numbers, photos of people. A member's name goes on
  the site only as that member agreed to show it.
- keys, passwords, tokens, server addresses or the app's `.env` values
- files or text from the team's private app repo, unless the team means that text to be public

Commit with your GitHub noreply address, not a personal email: check `git config user.email`
before your first commit. GitHub shows the address on every commit.

Undoing a commit does not remove it: the old version stays in the history, and rewriting the
history is blocked. If something from the list above gets pushed, tell the team at once, and
change any password or key that was in it.

## How the site works

- Plain HTML, CSS and images, with JavaScript only where a page needs it. No framework and no
  package manager: GitHub Pages serves the files as they are (`.nojekyll` turns off its Jekyll
  step).
- The home page is `index.html` at the top of the repo. Images go in `images/`. Link files with
  relative paths (`images/logo.png`), so a page also works when opened from your own computer.
- Every push to `main` goes live, usually within a few minutes. Force-pushing and deleting `main`
  are blocked. Fix a bad change with a new commit (`git revert`).

## Before you push

1. Open each changed page in a browser, also at phone width.
2. Check every link and image loads.
3. Read your changes against the "Never add" list above.
