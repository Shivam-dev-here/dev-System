**GitHub**: A cloud platform to **store, manage, and collaborate on code using Git (version control)**.


| S no. | Name | Description |
| ----- | ---- | ----------- |
| 1     |      |             |
- Commit Types
- Examples
- Initialize Repo

---
## Git Installation & Setup

- Download : [Click Me ](https://git-scm.com/install/windows) 
- Install
- First Time Git Setup
	1. Open Git Bash
	2. Linking with name and Email ID
		- ` git config --global user.name "Shivam Srivastava"`
		- ` git config --global user.email mypersonalishere.mypersonal@gmail.com`
	3. Check
		- `git config --global user.name`  :  ⇒ Shivam Srivastava
		- `git config --global user.email`

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

- On Website 
	1. Add a new repo in GitHub, Copy the 
	2. `git remote add origin https://github.com/Shivam-dev-here/test-repo.git`
- Open file with Git bash
	 1. `git init`
	 2. `git add .`
	 3. `git commit -m"Docs: Initialize repo`
	 4. `git remote add origin https://github.com/Shivam-dev-here/dev-System.git`
	 5. `git push -u origin master`
	 6. Refer Example for future commits
---



echo .obsidian/ >> .gitignore
