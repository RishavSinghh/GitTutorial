# Git & GitHub Tutorial

## Public repository to getting started with Git and GitHub for any project.

## Author

- Rishav Singh [@RishavSinghh](https://github.com/RishavSinghh)

---

## Git :

---

### Step 1:

Create the project folder and initialize Git using the following command :

```bash
  git init
```

### Step 2:

Make changes to your project file. Add the files to staging area using the following command :

```bash
  git add .
```

### Step 3:

Commit the changes using the following command (add your own message in place of 'commit message' ) :

```bash
  git commit -m "commit message"
```

## Using multiple branches in Git

---

\***\*follow the step number 1 from above then follow the below mentioned steps**

### Step 1:

Same as above

### Step 2:

Create a new branch (just remove the 'branch name' placeholder and add whatever name you like ):

```bash
  git branch <branch name>
```

### Step 3:

Switch to your newly created branch ( make sure to use the same name used in Step 2 ) :

```bash
  git checkout <branch name>
```

### Step 4:

Make changes to your project file. Add the files to staging area ( this change is being performed on the newly created branch ) :

```bash
  git add .
```

### Step 5:

Commit the changes (add your own message in place of 'commit message' ) :

```bash
  git commit -m "commit message"
```

---

**if you want to merge the newly created branch back to the 'main / master branch'**

### Step 6:

Switch back to the main branch :

```bash
  git checkout main
```

OR

Switch back to the master branch :

```bash
  git checkout master
  git merge <branch name>
```

**if you have a remote repository then after switching make sure to 'git pull' to avoid any conflicts**

### Step 7:

Merge the newly created branch to main / master branch ( make sure to use the same name used in Step 2 to create the new branch ) :

```bash
  git merge <newly created branch name>
```

**if you have a remote repository then after merging make sure to 'git push' to avoid any conflicts**

**to be continued...**
