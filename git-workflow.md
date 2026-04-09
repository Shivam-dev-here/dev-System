**GitHub**: A cloud platform to **store, manage, and collaborate on code using Git (version control)**.

- Commit Types

---
## Commit types

- `feat` → new feature
- `fix` → bug fix
- `refactor` → improve code
- `docs` → documentation
- `test` → add/update tests
- `chore` → minor tasks (config, setup)
- `perf` → performance improvement

---
## Example

```
git add .
git commit -m "init: setup project with Node.js"

git add .
git commit -m "feat: implement fs readFile"

git add .
git commit -m "feat: implement fs writeFile"

git add .
git commit -m "feat: implement fs appendFile"

git add .
git commit -m "refactor: clean code and structure"
```

---


## Initialize Repo



echo .obsidian/ >> .gitignore
git add .
git commit -m "First commit"
