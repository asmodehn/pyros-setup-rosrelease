Build a deb locally
-------------------
From a final branch (ie. `debian/indigo/trusty`):

```
git-buildpackage -uc -us --git-ignore-branch --git-ignore-new --git-upstream-tree=tag
```

