Altogether AUR Package
===

[![Build Status](https://dev.azure.com/announce/altogether/_apis/build/status/announce.aur-altogether?branchName=master)](https://dev.azure.com/announce/altogether/_build/latest?definitionId=7&branchName=master)


```
Host aur.archlinux.org
  IdentityFile ~/.ssh/aur
  User aur
```

```bash
git remote add aur ssh://aur@aur.archlinux.org/altogether.git
git push aur master
```
