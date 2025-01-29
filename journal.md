# PPE2-2024
## 1ER Séance 29/01/2025
### Git branche
- `(origin/main, origin/HEAD, main)` the two first text are red, the first is on Internet, what users will observe, it tells us they are in main branch, the Head commit (the last commit pushed), the third zone is all branches we have locally. 
- `git branche <name> [reference]` copy a branch from a certain commit id and create
- `git branche -d <name>`  delete
- `git branche -m/-c <name>` create a branch from the head
- `git checkout [-b] <branche>` swith to another branche, -b can create a new branche and swith to it en passage.
- `git switch [-c] <branche>` more simple, once swith to another git, it will switch to the branche distance synchronized.
- `git push --set-upstream origin <branche>` this will create the new branche from origin branch and pushi
- `git rebase <commit>` copy the commit and send it to main branche
- `git merge <branche>` actulize current branche with other branches in <>
