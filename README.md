# new-project


Create&go to DIR

```bash
mkdir new-project && cd new-project
```

Initialize Git repository

```bash
git init
```

connect to remove github repository

```bash
git remote add origin https://github.com/alwis-education/new-project.git
```

create file README.md. add some text

```bash
echo "# new-project" >> README.md
```

Make file README.md ready to commit. Commit changes.

```bash
git add README.md && git commit -m "init"
```
Create new Branch "development" and switch to it

```bash
git checkout -b development
```

Add instruction to README.md.

```bash
vim README.md
```

Make file README.md ready to commit. Commit changes to branch "development".

```bash
git add README.md && git commit -m "add instruction"
```

merge changes from branch "development" to "main"

```bash
git checkout main && git merge development
```

push changes to github repo

```bash
git push origin main
```
