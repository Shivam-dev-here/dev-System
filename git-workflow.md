P**GitHub**: A cloud platform to **store, manage, and collaborate on code using Git (version control)**.

---

| S no. |           Name           | Description |
| :---: | :----------------------: | :---------: |
|   1   | Git Installation & Setup |      -      |
|   2   |                          |             |
- Git Installation & Setup
- Initialize Repo
- Examples
- Some Keywords
- Different States of file
- Commit Types
- commands
- Other

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
## Example

```
git add -A
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
## Some Keywords

- Stages: ready these files for commit
- Commit: Declared the changes with it's Title

---
## Different States of file

![[Pasted image 20260410004501.png]]

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
## Commands

##### `git add .`
- stages changes at onwards directory
##### `git add -A`
- stages changes 
##### `clear`
- cleans the terminal
##### `ls -lart`
- Shows all folders and file on current directory
##### `ls`
- Shows all files on current directory
##### `git commit -a -m"not a good practice"`
- skips staging and commits

---
##### ==`git status`==
1. Basic
	- after the last commit, does any changes occurred and what else "clean tree". 
	- Red: Non Staged files
	- Green: Ready to Commit 
	- Both Green and Red: g-last time staged file, r-new changes that aren't staged 
2. Advance

##### `git status -s`

<table>
  <tr>
    <th>S.No</th>
    <th>Name</th>
    <th>Definition</th>
  </tr>
  <tr>
    <td>1</td>
    <td><span style="color:red;">M</span></td>
    <td>Non Staged modified file</td>
  </tr>
  <tr>
    <td>2</td>
    <td><span style="color:green;">M</span></td>
    <td>Staged modified file</td>
  </tr>
  <tr><td>3</td>
    <td><span style="color:red;">M</span><span style="color:green;">M</span></td><td>File staged and after modified</td></tr></table>

---
##### ==`git checkout index.html`==
- Example
	1. Earlier: `git status`: tree clean
	2. After: "Someone updated my index.html"    ⇒   Complete Blunder
	3. Solution: `git checkout index.html`: Matched current directory with last commit
- For multiple files
	`git checkout -f`
	
---
##### ==`.gitignore`==

- ignore extension on entire repo  : ` *.env`
- ignore a file on entire repo          : ` mylogs.log`
- ignore a folder on entire repo     : ` mylogs/`
- ignore a folder from root            : `/node_modules/slug/`
---
##### ==`Git Branch`==
- Example: 
- Theory: master running a website with some bugs, feature1 fixed those issues 

- `git branch`   :  shows all branch
- `git branch feature1`    :   creates a new feature1 named branch
- `git checkout feature1` :   switch branch
- `git checkout -b feature2`  :  creates and switch branch
- `git merge feature1`     :  merges with current branch
---
##### ==`Private Repository`==
- Theory: won't be able to push or fetch for private, follow steps after creating a repo
	1. settings
	2. SSH and GPGs keys
	3. Generating SSH keys
	4. Generating a new SSH keys and adding it to the ssh-agent
	5. copy : 



---
##### `git log`
- Shows all commit with committer, author and details
- Limited Commit `git log -p -6`  {6: last 6 commits}
- q: to exit

##### `git diff`
- Compares working directory with Staged file
- Shows: Both old and new code
##### `git diff --staged`
- Compares working directory with last commit

##### `git rm --cached deleteme.md`
- Removes the file from Staging area
##### `git rm deleteme.md`
- Removes the file from Hard disk 

##### `touch about.html`
- creates a file

---
## Other

- Shortcut
	1. Active window of Git bash
	2. `ctrl + +`: Zoom in


echo .obsidian/ >> .gitignore
