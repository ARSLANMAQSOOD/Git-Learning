**GIT BASIC COMMANDS**

create new repository with specified file name

```
git init [project name]
```

clone the existing project and its entire history

```
git clone [url]
```

**Make Changes**

list all new or modified file to be comitted

```
git status
```
show the file difference yet no staged

```
git diff
```
snapshot the file in preparation for versioning

```
git add [filename]
```
show the difference between the staged file and the last version file

```
git diff \-\-staged
```
record file snapshorts permanent in file history

```
git commit -m "[descriptive message]"
```

**Group Changes**

list all the branches in the current repository

```
git branch
```

create a specified branch

```
git brnach [branch-name]
```

switch to the specified branch and update the working directory

```
git checkout [branch-name]
```

merge the specified branch hisotry into the current branch

```
git merge [branch]
```

Delete the specified branch

```
git brnach \-d[branch]
```

**Review History**

list version history for the current branch

```
git log
```

get version history of a file including renaming

```
git log \-\-fellow [file-name]
```

show the difference between the first and second branch

```
git log [first-branch]...[second-branch]
```

Output the metdata of the specified commit... it require the commit SHA-1 code

```
git show [commit-SHA-1 CODE]
```

**REDO COMMITS**

Undo all commits after all [commit], preserving changes locally

```
git reset [commit]
```
**SYNCHRONIZE CHANGES**

Download all the history from the repository bookmark

```
git fetch [bookmark]
```
Upload all the local barnch commits to Github

```
git push [alias] [branch]
```
Download bookmark history and incorporate changes
```
git pull
```
