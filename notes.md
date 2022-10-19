## Rebase

- changing of parent
- At feature branch, run: `git rebase parentBranch`, the `parentBranch` is usually the main/master branch

Rebase in shared {feature} branch? DO NOT REBASE! IT WILL CAUSE CONFLICTS! THERE ARE CHANCES THAT YOU WILL ERASE OTHERS' WORK! DON'T BE A DICK!

2 steps

1. git checkout main
2. git pull
3. git checkout topic-1
4. git rebase main

OR

`git pull -r origin {source}` at {destination} branch
