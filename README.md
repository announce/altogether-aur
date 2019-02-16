Altogether AUR Package
===

[![Build Status](https://dev.azure.com/announce/altogether/_apis/build/status/announce.altogether-aur?branchName=master)](https://dev.azure.com/announce/altogether/_build/latest?definitionId=5&branchName=master)


```
Host aur.archlinux.org
  IdentityFile ~/.ssh/aur
  User aur
```

```bash
git remote add aur ssh://aur@aur.archlinux.org/altogether.git
git push aur master
```
