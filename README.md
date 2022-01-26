# distribution

This repository contains the fork of https://github.com/distribution/distribution/tree/v2.7.1 for use in kubernetes

We used the following command to prune the tree to just the things needed by kubernetes (and preserve history)
```bash
git filter-repo --path LICENSE --path reference/ --path digestset/ --force
```