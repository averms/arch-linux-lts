Arch Linux LTS kernel with a few changes. Built by GitHub Actions.

To update:

1. `git remote add upstream git@github.com:archlinux/svntogit-packages.git`.
2. `git fetch upstream packages/linux-lts`. Never run just `git fetch upstream` because
   it will download all the branches and take forever.
3. `git rebase upstream/packages/linux-lts` and fix conflicts.
4. `git push -f`.
