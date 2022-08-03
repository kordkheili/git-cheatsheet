## Git Course

#### Preapared by Websila Digital Marketing Academy

---

## Requirements

- [git](https://git-scm.com/downloads)
- [github cli ](https://cli.github.com/)

![Git States](/assets/images/diagram.jpg "Git States")

## 1. Cheatsheet : SETUP

| Commands                       | Description      |
| ------------------------------ | ---------------- |
| git config --global user.name  | add global name  |
| git config --global user.email | add global email |
| gh auth login                  | login to github  |

## 2. Cheatsheet : INIT

| Commands        | Description                        |
| --------------- | ---------------------------------- |
| git init        | create a new git repository        |
| git clone [url] | download a git repository from url |

## 3. Cheatsheet : STAGE & SNAPSHOT

| Commands                             | Description                                 |
| ------------------------------------ | ------------------------------------------- |
| git status                           |                                             |
| git add [file.txt]                   | add file.txt changes to stage               |
| git add -A                           | add all changes to stage                    |
| git reset [file.txt]                 | unstage file.txt                            |
| git clean -fd                        | remove all new staged files and directories |
| git diff                             |                                             |
| git commit -m "your message here..." |                                             |

## 4. Cheatsheet : BRANCH & MERGE

| Commands                  | Description                                                               |
| ------------------------- | ------------------------------------------------------------------------- |
| git branch                |                                                                           |
| git branch [[branch-name] |                                                                           |
| git checkout              | Changes to modified files are discarded but untracked files are untouched |
| git merge [branch-name]   |                                                                           |
| git log                   |                                                                           |

## 5. IGNORING PATTERNS (.gitignore)

| PATTERNS      | Description |
| ------------- | ----------- |
| node_modules/ |             |
| \*.jpg        |             |

## 6. SHARE & UPDATE

| Commands                               | Description                             |
| -------------------------------------- | --------------------------------------- |
| git remote add [new-remote-name] [url] |                                         |
| git push [remote-name] [branch-name]   | submit local commits in remote          |
| git pull                               | fetch and merge any commits from remote |
| git fetch [remote-name]                | fetch all branches from remote          |

## 7. GO BACK & REWRITE HISTORY

| Commands                                | Description                                                    |
| --------------------------------------- | -------------------------------------------------------------- |
| git reset --hard [commit]               | hard reset to selected commit                                  |
| git clean -fd                           | remove untracked files and directories                         |
| git push [remote-name] [branch-name] -f | force submit local commits in remote<br>(remove ahead commits) |

## Related Articles

- [git-checkout-clean-reset](https://remarkablemark.org/blog/2018/10/09/git-checkout-clean-reset/)
