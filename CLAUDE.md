# Repository rules

## Git: always push directly to `main`

The repository owner has given standing, explicit permission to commit and push directly to `main`.

- Do not create `claude/...` feature branches and do not open pull requests unless the owner asks for one.
- Before pushing, run `git fetch origin main` and make sure the commit sits on top of the latest `origin/main`. If it does not, rebase onto it, then push with `git push origin HEAD:main`.
- Never force-push `main`.

## Layout

- `mgt6046yaokaoshi/`: MGT6046 Operations and Supply Chain Management, the examined module
  - `lecture/`: weekly lecture slides
  - `tutorial/`: tutorial slides and solutions
  - `pastexam/`: past exam papers with answers
  - `MGT6046_Formula_Sheet_1.docx`: exam formula sheet
- `mgt650organize3000/`: MGT650 lecture slides and readings
