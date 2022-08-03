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

| Commands                             | Description                                                                  |
| ------------------------------------ | ---------------------------------------------------------------------------- |
| git status                           |                                                                              |
| git add -A                           | stage all files                                                              |
| git reset                            | unstage all                                                                  |
| git reset --hard                     | 1-unstage all <br> 2-discard all changes compare to last commit              |
| git clean -fd                        | Untracked files and directories are removed but modified files are unchanged |
| git diff                             |                                                                              |
| git commit -m "your message here..." |                                                                              |

## 4. Cheatsheet : BRANCH & MERGE

| Commands                 | Description                                                               |
| ------------------------ | ------------------------------------------------------------------------- |
| git branch               |                                                                           |
| git branch [branch-name] |                                                                           |
| git checkout [commit]    | Changes to modified files are discarded but untracked files are untouched |
| git merge [branch-name]  |                                                                           |
| git log                  |                                                                           |

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

| Commands                                | Description                                                                  |
| --------------------------------------- | ---------------------------------------------------------------------------- |
| git reset                               | unstage all                                                                  |
| git reset --hard                        | 1-unstage all <br> 2-discard all changes compare to last commit              |
| git clean -fd                           | Untracked files and directories are removed but modified files are unchanged |
| git push [remote-name] [branch-name] -f | force submit local commits in remote<br>(remove ahead commits)               |

## Related Articles

- [git-checkout-clean-reset](https://remarkablemark.org/blog/2018/10/09/git-checkout-clean-reset/)
